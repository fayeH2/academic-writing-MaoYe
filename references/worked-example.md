# 同一研究在不同章节中怎样写

本例完全是教学场景，由本次整理新写，不是叶茂论文的摘录，也不是建议学生采用的新算法。所有结果槽位必须由真实实验填写。不能把这个例子当作已经完成的研究。

## 1. 假设学生交来的研究材料

- 任务：source-free classification adaptation。可用源分类器参数和无标签目标样本；不可用源数据或目标训练标签。
- 初步诊断：学生声称高置信错误预测存在于其目标数据，但还没有提供诊断图和具体比例。
- 核心原则：降低两个视图下不一致预测对学生学习的影响。
- 方法：冻结的源预测器产生两个保持语义的视图预测；以预测分布差异构造连续权重，作用于学生的伪标签损失；目标推理使用适应后的学生。
- 缺失：具体视图变换、权重函数、伪标签来源细则、停止梯度位置、训练配置、结果、失败条件。

在这个输入上可以组织叙述，但不能写成完整可复现的 Method，也不能宣布性能或可靠性得到提升。先保留“冻结源预测器”“连续降权”“学生最终预测”三项事实，不能为了英文流畅而写成教师也被更新、离散样本筛选或集成推理。

## 2. Abstract：完整工作的信息压缩

下面是约 180–220 词目标摘要的结构稿；槽位长度变化会改变实际词数。一个连续段落，不标注功能标题。

> Source-free domain adaptation transfers a source classifier to an unlabeled target domain without access to the source training data. Confidence-based pseudo-labeling can retain incorrect predictions when the source classifier is overconfident on shifted inputs. Our diagnostic analysis on 〔target domain and diagnostic evidence〕 identifies 〔verified relationship between prediction inconsistency and labeling errors〕. Motivated by this finding, we introduce 〔method name〕 to control the contribution of inconsistent predictions during adaptation. For each target image, a frozen source predictor produces class distributions for two label-preserving views. We measure the discrepancy between these distributions and convert it into a continuous reliability weight. This weight scales the pseudo-label loss used to update the student, while 〔exact pseudo-label construction and any additional objective〕. The source predictor remains fixed throughout adaptation, and inference uses only the adapted student. Experiments on 〔verified benchmarks and protocol〕 show 〔supported result against a named comparable baseline〕. Further analysis of 〔completed reliability and control experiments〕 supports 〔specific interpretation within the evaluated settings〕.

写作判断：开头只给必要设置；中间把“可靠性”展开为可辨认的动作；结尾预留主结果和机制证据。**目前诊断和实验尚缺，因此这是一份待补事实的结构稿，不能原样提交。** 若诊断尚未开展，删除 “Our diagnostic analysis … identifies …”，将下一句改为设计假设的表达，不能保留一个虚构的发现。

## 3. Introduction：展开为什么这样设计

这里示范引言中间的两个段落。完整引言还需要任务背景、经过核验的研究路线、方法概览与贡献；不把这两个段落当作完整 Introduction。

> A common adaptation strategy uses the source classifier to assign pseudo labels to target images and then trains a target model on the selected predictions 〔verified references〕. Confidence provides a convenient selection criterion, but its reliability depends on the behavior of the source classifier after the domain shift. A confident prediction need not be correct when the target input differs from the source training distribution. In our preliminary analysis, 〔state the measured failure pattern and refer to its figure〕. This observation suggests that confidence alone does not adequately distinguish 〔the specific cases established by the analysis〕.
>
> We therefore consider prediction consistency across two label-preserving views as an additional signal for weighting target supervision. The idea is to reduce the influence of predictions that change substantially under these transformations. This does not imply that consistent predictions are necessarily correct: a source classifier may make the same mistake on both views. Accordingly, our method uses consistency to modulate the pseudo-label loss through a continuous weight, rather than treating agreement as a ground-truth label. The resulting adaptation procedure keeps the source predictor fixed and updates the student with 〔the specified weighted objective〕. Section 〔analysis section〕 evaluates whether this weighting improves 〔the measured quantity〕 and examines cases in which consistency remains misleading.

写作判断：第一段把“方法有限”拆成依赖条件、失效机制和待补的实际诊断；第二段推出原则，并交代其不能解决什么。这里需要解释与推理，因此比摘要多；仍不展开权重函数的所有符号。

如果材料只支持“不一致的预测可能有问题”，就不能改成“一致性可以识别错误预测”。两个命题的强弱不同。最后一句是实验安排承诺：论文未做该分析时，应先列为待完成事项，不写成已存在章节。

## 4. Method：从原则变成明确计算

弱写法：

> We introduce an effective reliability module to improve pseudo-label quality and enhance adaptation robustness.

可用的技术段落起稿：

> Let \(x\) denote an unlabeled target image and \(g_s\) the frozen source predictor. We construct two views \(t_1(x)\) and \(t_2(x)\) using 〔specified label-preserving transformations〕. Their class distributions are \(p_1=g_s(t_1(x))\) and \(p_2=g_s(t_2(x))\). We compute a discrepancy score \(d(p_1,p_2)\) using 〔exact discrepancy definition〕 and obtain the sample weight \(w(x)=h(d(p_1,p_2))\), where 〔define h, its range, and its parameters〕. The weight is applied to 〔exact student objective and pseudo-label source〕. During this update, 〔identify the differentiated parameters and detached quantities〕.

接着才解释为什么选择该差异和权重函数，与直接丢弃样本或只用置信度相比有什么预期差别。没有函数定义时，就停留在带槽位的技术稿；不能擅自选 KL、JS、cosine 或某个温度函数。

这里的公式定义的是对象和操作，因此不需要在每个等号前重复一遍空泛“直觉”。真正的实现仍必须补齐：预测分布怎样归一化、教师标签怎样构造、哪一张视图输入学生、权重是否反传。

## 5. Experiments：结果、解释、边界分别写

在写段落前列三个不同问题：

1. 加权方法是否优于相同骨干与相同预算的直接伪标签学习？对应主比较。
2. 是否因为一致性权重起作用，而非额外视图或计算量？对应保持视图和预算相同的替代/关闭实验。
3. 一致性是否真的与错误关系有关？对应离线诊断及高一致性错误案例；离线使用标签应明确说明。

可填结果分析：

> Table 〔number〕 compares 〔methods〕 under the same 〔backbone, data access, and adaptation budget〕. Replacing uniform sample weights with 〔specified weights〕 changes 〔metric〕 from 〔A〕 to 〔B〕. Because both variants use 〔controlled view generation and training schedule〕, this comparison tests the contribution of the weighting rule under a fixed adaptation procedure. The separate diagnostic in Fig. 〔number〕 shows 〔measured relation〕. Together, these results support 〔bounded inference〕. On 〔observed failure condition〕, however, 〔actual exception〕.

不能用主结果表直接“证明伪标签更准确”。这需要伪标签本身的测量，且应同时考虑覆盖率和类别分布。不能把调节权重温度的曲线作为整个模块的唯一消融。

## 6. Conclusion：回收已经证实的认识

下面是约 80–110 词目标结论的结构稿，只能在相应实验完成后填写。

> This work studied source-free adaptation with supervision derived from a fixed source classifier. We introduced 〔method name〕, which uses cross-view prediction discrepancy to weight the student’s pseudo-label loss. The evaluation shows 〔specific supported result〕 under 〔tested data and model conditions〕. The accompanying analysis indicates 〔verified finding about the weighting mechanism〕. The method remains limited by 〔observed or clearly justified boundary, such as consistently incorrect teacher predictions〕, which defines a direction for further investigation.

写作判断：不重讲整个领域背景，不再分类介绍前人；保留中心机制与所得认识，不罗列全部模块或逐个报告数据集。没有验证的机制推断应删除，不能为了结尾完整而保留。

## 7. 实际调用时怎样提出任务

可直接使用以下请求方式：

- “请按本技能修改下面的 Introduction。保留现有研究主张和术语，先检查问题与方法是否匹配，再给完整英文修订稿；没有证据的观察请标出。”
- “下面是方法事实、实验表和投稿模板。请分别写 Abstract 与 Conclusion，并解释两者的信息取舍；不要复制整句，不添加未给出的结果。”
- “请审查这段 Method 的信息流、变量和更新次序。先补齐叙述中遗漏的定义；实现未知的地方保留待确认标记，不替我发明算法。”

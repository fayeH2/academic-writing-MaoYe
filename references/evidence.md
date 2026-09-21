# 写作规则的证据与适用范围

检索整理日期：2026-09-20。本文件用于核查 SKILL 中的写作判断；不是要求每次写作都加载的提示词。

## 1. 作者识别与检索范围

研究对象为电子科技大学计算机科学与工程学院叶茂教授。身份以[学校主页](https://faculty.uestc.edu.cn/yemao/en_EN/index.htm)为锚点，以 [DBLP Mao Ye 0001](https://dblp.org/pid/36/2301-1.html)作书目骨架，并与[合作者 UP Lab 论文列表](https://x-up-lab.github.io/publications/)、会议论文页面、论文 PDF 和出版元数据交叉检查。学校主页明确是代表性成果，不等于完整论文全集。

已整理 DBLP 的 257 条版本记录，其中 2022 年及以后 140 条、这些近期记录中第二作者 44 条。数字包括预印本与正式版本，不能当作去重后的独立论文数。学校主页 98 个编号条目另作交叉核查，部分有重复、题名差异或年份差异。完整记录与新增线索见 [publications.md](publications.md)。

OpenAlex 对应作者聚合页返回 501 条记录，但混入宾州州立大学、UT Austin、金融领域及电子科大光电学院的同名作者。不能把这些记录整体归给本研究对象。未能进一步核实的相关候选单列，未用于推断写作风格。Google Scholar 未取得完整可遍历书目。因此，本次结果是可复核的公开来源汇编，**不能保证无遗漏，也没有逐篇阅读全部论文全文**。

## 2. 核心阅读样本与作者身份

页码指本次取得 PDF 的物理页码，从 1 开始；网页、正式出版版与预印本排版可能不同。全文可访问表示已提取全文，并对结构、关键论证段落及对应章节作重点阅读，不代表逐项复现全部实验或核证全部数学证明。

| 标识 | 论文、版本及来源 | Mao Ye 的作者顺序与通讯证据 | 本次阅读层级 |
|---|---|---|---|
| LODS | [Source-Free Object Detection by Learning to Overlook Domain Style，CVPR 2022](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Source-Free_Object_Detection_by_Learning_To_Overlook_Domain_Style_CVPR_2022_paper.pdf)；另有用户标注版 | 第 2；第 8 页致谢明确 Mao Ye、Xiatian Zhu 为通讯作者 | 用户 PDF 全文、29 条批注；关键章节重点阅读 |
| KUNet | [KUNet: Imaging Knowledge-Inspired Single HDR Image Reconstruction，IJCAI 2022](https://www.ijcai.org/proceedings/2022/0196.pdf) | 第 2；首页标明与 Xiatian Zhu 共同通讯 | 全文及关键章节 |
| MetaTeacher | [MetaTeacher: Coordinating Multi-Model Domain Adaptation for Medical Image Classification，NeurIPS 2022](https://papers.nips.cc/paper_files/paper/2022/file/8313b1920ee9c78d846c5798c1ce48be-Paper-Conference.pdf) | 第 2；首页通讯标记 | 全文及关键章节 |
| HMA | [Homeomorphism Alignment for Unsupervised Domain Adaptation，ICCV 2023](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhou_Homeomorphism_Alignment_for_Unsupervised_Domain_Adaptation_ICCV_2023_paper.pdf) | 第 2；首页通讯脚注 | 全文及关键章节 |
| DIFO | [Source-Free Domain Adaptation with Frozen Multimodal Foundation Model，CVPR 2024／作者预印本](https://arxiv.org/abs/2311.16510) | 第 3；所读 PDF 首页标明与 Xiatian Zhu 共同通讯 | 全文及关键章节 |
| ProDe | [Proxy Denoising for Source-Free Domain Adaptation，ICLR 2025／arXiv v3](https://arxiv.org/abs/2406.01658) | 所读 2025 版本第 4，与 Xiatian Zhu 共同通讯；旧预印本书目为第 3 | 全文及关键章节；不混用版本作者顺序 |
| BCA | [Bayesian Test-Time Adaptation for Vision-Language Models，CVPR 2025／arXiv v2](https://arxiv.org/abs/2503.09248) | 第 2；所读首页标记的通讯作者是 Zhen Lei，不是 Mao Ye | 全文及关键章节 |
| DisCo | 用户文件 `MM_Lirenjie.pdf`，题名为 Reliable Pseudo-Labeling via Pairwise Discriminative Comparison for Unsupervised Prompt Tuning；[公开作者列表线索](https://openreview.net/forum?id=MxtfVNc0NZ) | 用户 PDF 匿名，不能由它确定作者或通讯身份；UP Lab 同题记录列 Mao Ye 第 2，并标注 ACM MM 2026 | 用户匿名 PDF 全文及关键章节；公开题录与本地稿件版本关系未完全核验 |
| GAN regulator | [Training generative adversarial networks by auxiliary adversarial example regulator，Applied Soft Computing 136 (2023), 110086](https://www.sciencedirect.com/science/article/abs/pii/S1568494623001047) | Yan Gan、Mao Ye、Dan Liu、Yiguang Liu；第 2；通讯身份未核验 | 出版方摘要、引言及部分章节片段；未取得完整 PDF |
| Cloud VLM | [Black-Box Domain Adaptation for Cloud Vision-Language Model by Exploring Optimization Directions，IEEE TMM 2026](https://ieeexplore.ieee.org/abstract/document/11627659/) | Shuaifeng Li、Mao Ye、Luping Ji、Lihua Zhou、Nianxin Li、Jian Yue、Xiatian Zhu；第 2；通讯身份未核验 | [出版方提交的 Crossref 元数据](https://api.crossref.org/works/10.1109/TMM.2026.3718256)及合作者列表；公开 PDF 链接失效，未完成全文分析 |

作者顺序不能代替通讯标记；通讯作者身份也不能证明某段英文出自其本人。这里提炼的是这一合作论文样本中反复出现的写作方式。

## 3. 从论文中提炼出的实际写作决策

### LODS：围绕可用学习信号展开

定位：摘要；Introduction 第 1–2 页；§2 Related Work；§3.1–3.3；§4.1–4.2；第 8 页 Conclusion。引言先交代 source-free 设置与现有路线，再把域风格问题转成学习原则；方法由整体框架进入风格增强、关系建模及目标函数；实验分别验证比较结果和具体设计。

转成规则：先定义限制下能获得什么信号，再解释为何需要它；方法名称出现后必须给动作；小节标题与概览部件对应；主实验、消融、敏感性分别回答不同问题。不能把“使用新信号”自动写成“消除全部域偏移”。

### KUNet：知识分析可先于网络设计

定位：§3 Analysis of HDR Image Reconstruction；§4 Proposed Method（head/tail、KIB、KIC、loss）；§5.3；第 6 页结论。论文先分析重建任务中的成像关系，再解释这些关系怎样落实到网络。

转成规则：当贡献是知识约束时，先把假设与可用关系说清，再介绍结构。不要将所有论文强制排成“问题定义—三个模块—总损失”；独立分析节有其合理用途。

### MetaTeacher：多角色方法需要清楚的优化叙述

定位：§3.1–3.3；§4.2；第 10 页结论。任务允许少量目标标签，不能误归类为完全无监督设置；技术叙述围绕教师协调与学习过程的依赖展开。

转成规则：先说明每个模型拥有什么信息、被什么信号更新，然后写协同与双层关系。论证“协调有效”不能只报总分，还要检验协调机制。

### HMA：结构诊断与方法实现分工

定位：§3 Analysis of Distribution Alignment；§4；§5.3；§6；第 9 页结论。分析、方法和性质讨论分别承担不同责任。用于说明机制的 oracle 信息不能混入通常的无监督训练协议。

转成规则：把经验诊断、研究假设、结构设计与理论保证分开；如果中心主张涉及结构保持，就比较相关替代映射，不能仅靠特征可视化声称已证明该性质。

### DIFO：用更新关系解释框架

定位：摘要与引言；§3 Methodology；§4；第 8 页结论。框架通过定制与蒸馏两个过程交代基础模型知识怎样进入适应过程。

转成规则：概览写信息流和优化次序，模块名与后文一致；清楚区分冻结基础模型、可训练部分和最后用于预测的模型。结果优势须结合骨干及额外信息权限解释。

### ProDe：把外部模型知识的可靠性作为独立问题

定位：§3.1 Problem Formulation、§3.2 Proxy Confidence Theory、§3.3 Capitalizing Corrected Proxy；§4.3；第 10 页结论。叙述没有把外部模型输出直接等同于正确标签，而是先分析其可靠性，再落实到利用方式。

转成规则：写出失误条件及其后果，再说明纠偏信号与实现；区分理论对象与实际近似。作者顺序按所读版本核验，不能沿用旧网页的三作信息覆盖正式版本四作信息。

### BCA：按预测因素组织贡献

定位：引言贡献段；§3；§4.3；第 8 页结论。所读文本按决策分解组织技术，贡献概括为两项，并非统一三项。文中的条件先验需要按其条件变量解释，不能随意简化成类别频率。

转成规则：先定义各因素，指出已有方法改变哪个因素，再逐项解释更新及联合效果。贡献数量服从实际科学内容，不能硬凑“认识、模块、实验”三条。

### DisCo：错误结构到可实施判别过程

定位：本地 PDF 摘要、引言；§3.1–3.5；§4.1–4.3；第 8 页结论；附录 C。正文从候选类别混淆问题推进到成对判别，再解释高效实现、提示学习、推理及总体训练；附录单列局限。

转成规则：从识别到的错误结构推导操作；高效近似应说明节省的是哪一部分成本；训练与推理都要闭合。匿名稿只作为用户提供的写作样本，不据此推定录用、通讯作者或出版状态。

### GAN regulator：仅从已见章节提取有限规则

定位：出版方可访问摘要、引言、章节片段。文章以已有稳定训练策略的分类建立位置，并把生成器与判别器的相互关系引向辅助调节设计。

转成规则：对于相互依赖的优化角色，分别交代其目标及作用路径；如果宣称训练更稳定，证据应包括过程或多次运行表现。没有完整 PDF，未将其完整公式顺序、段落长度或图表组织当作已核实规律。

Cloud VLM 本次只提供题录及身份定位，不作为其具体章节风格已被证实的依据。SKILL 中云端查询、黑盒权限、适应/推理成本的检查属于针对该任务的执行建议。

## 4. 用户标注版对技能的直接贡献

LODS 标注 PDF 共提取 29 条 FreeText 批注，元数据作者名为 `apple`，真实身份未知。以下保留其教学含义，同时区分适用范围：

| 批注位置 | 教学含义 | 落到 SKILL 的动作 |
|---|---|---|
| 第 1 页 | 问题、策略、动机和中心论点要匹配 | 用研究说明与主张—证据表消除孤立动机 |
| 第 1–2 页 | 不要一边写方法一边空泛评论；不能用好处代替思路 | 先写操作对象、步骤与输出，再讨论作用 |
| 第 1–2 页 | 分类介绍已有方法，避免逐篇罗列 | Related Work 按策略归纳，并详述最近工作的差异 |
| 第 2 页 | 贡献用紧凑的段内编号形式 | 作为该标注范例偏好；不扩大为普遍禁止项目符号 |
| 第 2–4 页 | 问题定义、整体到部件、标题对应、变量解释 | Method 有任务权限、整体信息流、组件及更新过程 |
| 第 3 页 | 图中文字、箭头、损失说明；图注解释不明显记号 | 框架图表达计算关系；图注不重复整段方法 |
| 第 4 页 | 方法说清后，可以比较直接替代方案 | 用有条件的局部讨论代替赞美式评价 |
| 第 5–7 页 | 数据、实现、评估协议先交代，再分析结果 | 每组实验先定义控制条件与问题 |
| 第 7 页 | 参数讨论与消融不同 | 参数敏感性与组件必要性单列 |

批注提及用会议标志介绍强基线；技能采用“说明基线来源与协议”的有效部分，不把发表场所当作优劣或公平性的证明。

## 5. 对初稿的实质修正

| 初稿中的统一规定 | 完善后的可执行规则 | 修正理由 |
|---|---|---|
| 摘要五句话 | 五类信息，可分成多句，重点给关键实现留空间 | 已读摘要并不服从统一句数；信息比句数重要 |
| 引言 4–5 段 | 按功能组织，默认约 5–7 段，可拆合 | 路线分类、机制诊断与方法概览的复杂度不同 |
| 必须三条贡献 | 两至四项独立、可检验贡献 | BCA 即为两项；常规实验不一定是独立贡献 |
| 每个公式前必须有直觉 | 先让读者理解数学对象；定义式可直接进入 | 避免形式化定义前反复添加空话 |
| 每个模块独立优化 | 解释计算/更新；无训练模块无需编造 loss | 解析步骤、推理算法不必有独立损失 |
| Conclusion 150–250 词 | 默认 80–150 词，集中回收认识和边界 | 所读结论多为紧凑段落，不应扩成第二摘要 |
| 固定偏好短语决定风格 | 用具体主语、动作和依赖关系保持风格 | 重复 “We observe / This motivates us” 不能替代逻辑 |
| 改善 reviewer acceptance | 提升可核验性、清楚性和证据对应 | 无法保证录用，不应为了说服而扩大主张 |

篇幅与句长是编辑预算，不是基于全部论文计算出的统计结论。约 4,000 词的示范分配仅便于起稿，最终以目标年份官方模板、图表占页和研究复杂度调整。

## 6. 使用这些证据时的限制

不要从某篇成功发表论文中复制未经检验的夸张句式、引用错误或推断越界。已发表和已录用不等于每一处表达都值得模仿。保留的是问题收窄、机制解释、从整体到细节的组织及实验问答方式；不是复制句子，也不是声称完整还原某位合著者的个人语言。

本包不包含或再分发原论文 PDF。书目、分析和教学例句为本次整理材料；需要核验时打开链接或使用用户原始文件。

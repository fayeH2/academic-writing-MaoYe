# 🏫 Academic Writing Skill

本仓库提供一个面向**计算机视觉研究论文写作**的 Academic Writing Skill，主要用于辅助学生起草、修改和审查英文科研论文。

它并不是一个简单的英文润色 prompt，而是试图帮助作者建立完整的科研论证链：

**Problem → Mechanism → Method → Evidence**

即：

> 研究问题是什么 → 现有方法为什么在特定条件下存在不足 → 方法设计如何针对这一机制 → 实验如何验证对应主张。

该 Skill 主要参考一位**资深教授**参与的计算机视觉研究论文中可以观察到的共同写作方式，并结合论文写作中的结构化分析方法整理而成。

---

## ✨ What this skill can do

该 Skill 可以辅助完成论文不同阶段的写作任务，包括：

- **Title**
  - 明确研究任务与核心区别
  - 避免把模块名称简单堆入标题
  - 检查任务设定是否准确

- **Abstract**
  - 压缩完整的问题—方法—证据链
  - 区分研究动机、核心认识与具体实现
  - 避免只写成 Introduction 的缩短版

- **Introduction**
  - 从任务背景逐步推进到具体研究问题
  - 分析现有方法的假设、机制和适用边界
  - 建立从问题诊断到方法设计的逻辑链
  - 组织贡献点

- **Related Work**
  - 按研究路线和机制分类文献
  - 定位与最相关工作的实质差异
  - 避免逐篇罗列论文

- **Method**
  - 建立清晰的问题定义
  - 组织方法 Overview
  - 解释模块之间的数据流和优化关系
  - 检查符号、公式、梯度路径和训练/推理流程

- **Experiments**
  - 将实验与论文中的具体 claim 对齐
  - 设计主实验、消融实验和机制验证
  - 检查 baseline 是否公平可比
  - 避免让实验结论超过已有证据

- **Conclusion**
  - 回收已经得到实验支持的研究认识
  - 避免重新展开背景或提出未经验证的新主张

---

## 🎯 Suitable research areas

该 Skill 尤其适合以下计算机视觉研究方向：

- Domain Adaptation
- Source-Free Domain Adaptation
- Test-Time Adaptation
- Black-Box Adaptation
- Vision-Language Models
- Knowledge Distillation
- Pseudo-Label Learning
- Teacher-Student Learning
- Representation Learning
- Medical / Cross-domain Vision Tasks

同时，其中的大部分论证方法也可以迁移到其他机器学习研究论文。

---

## 🧠 Core philosophy

这个 Skill 的重点不是让论文“听起来更高级”，而是让论文中的每一个重要表述都能够回答：

1. **What is the exact problem?**
2. **Why does the existing strategy fail under this setting?**
3. **What mechanism causes the failure?**
4. **What principle does the proposed method introduce?**
5. **How is that principle implemented?**
6. **What evidence supports each claim?**

一个典型的研究逻辑可以被压缩为：

> 在 **〈约束〉** 下，  
> **〈现有策略〉** 由于 **〈原因〉** 导致 **〈具体失败〉**；  
> **〈证据〉** 表明 **〈关键观察〉**；  
> 因此采用 **〈设计原则〉**，通过 **〈具体机制〉** 实现，  
> 并使用 **〈实验〉** 验证对应主张。

这不是论文中的固定句型，而是一种用于检查科研论证完整性的工作框架。

---

## 🧩 Writing routes

Skill 不会把所有论文强行套入同一种 narrative，而是根据研究问题选择不同的论证路径，例如：

| Route | Typical idea |
|---|---|
| Learning Signal | 分析现有监督信号的限制，并构造新的可用学习信号 |
| Structure / Knowledge | 利用被忽略的数据结构、先验知识或物理约束 |
| Decision Decomposition | 将预测过程拆成不同因素并分析缺失环节 |
| Reliability | 分析伪标签、外部知识或模型预测的不可靠性并进行纠偏 |
| Collaborative Optimization | 分析多个模型、教师或角色之间的更新与监督关系 |

核心原则是：

> **方法设计必须能够从问题机制中推出来，而不是在写作阶段为已有模块补一个故事。**

---

## 📂 Repository structure

```text
academic-writing-Mao/
├── SKILL.md
├── references/
│   ├── evidence.md
│   ├── publications.md
│   └── worked-example.md
└── LICENSE
```

### `SKILL.md`

Skill 的核心文件。

包含：

- 论文写作总体流程
- 研究问题与 claim 分析
- Title / Abstract / Introduction
- Related Work
- Method
- Experiments
- Conclusion
- 写作检查规则
- 证据约束与事实核验要求

### `references/evidence.md`

用于追踪 Skill 中写作规律和风格判断的依据。

当需要回答：

> “为什么建议这样写？”

或需要进一步检查某项写作模式是否确实能够从已有论文中观察到时，可以参考该文件。

### `references/publications.md`

用于整理相关论文、作者顺序、论文版本及检索覆盖情况。

适合在分析具体论文或追踪写作依据时使用。

### `references/worked-example.md`

提供一个完整的教学案例，用于展示同一个研究问题如何在：

- Abstract
- Introduction
- Method
- Experiments

等不同章节中以不同的信息密度展开。

该示例用于教学，不代表真实研究结果。

---

## 🚀 Usage

将本仓库作为一个 Skill 提供给支持 `SKILL.md` 工作流的 AI Agent，然后向 Agent 提供你的研究材料，例如：

- research idea
- existing manuscript
- method description
- equations
- experiment tables
- figures
- reviewer comments
- advisor comments
- related papers

之后可以直接提出具体任务。

例如：

```text
根据这个 skill 帮我检查 Introduction 的逻辑。
重点检查 problem → observation → method 之间是否连贯。
```

或者：

```text
这是我的方法和实验结果。
请先建立 claim–evidence mapping，然后帮我重新写 abstract。
不要编造任何不存在的实验结果。
```

也可以只修改局部内容：

```text
帮我润色这一段 Method。
保持技术含义和符号不变，只改善逻辑顺序和英文表达。
```

对于完整论文，推荐先让模型建立：

- Claim–Evidence Table
- Problem–Component–Validation Table
- Terminology Table

再开始逐章节写作。

---

## ⚠️ Evidence and hallucination control

这个 Skill 特别强调：

**不要为了让论文故事完整而编造研究事实。**

如果实验、数据或文献依据缺失，应明确保留缺口，例如：

```text
〔待提供：指标 / 数据集 / 比较对象〕
```

或：

```text
〔待核验引用：所需命题〕
```

以下内容不应由模型自行补全：

- 不存在的实验结果
- 未验证的性能提升
- 不确定的 baseline 设置
- 虚构引用
- 未证明的数学性质
- 未实际执行的训练或推理流程

论文中的 claim 强度应始终受到现有 evidence 的约束。

---


## 🤝 Contributions

欢迎通过 Issue 或 Pull Request：

- 补充论文样本
- 修正 evidence attribution
- 改进写作规则
- 增加 worked examples
- 补充不同类型计算机视觉论文的写作模式
- 报告 Skill 在实际论文写作中的问题

如果新增规则来自特定论文或批注，建议同时说明对应依据，以便区分：

- observed writing pattern
- teaching annotation
- general writing recommendation

---

## 📄 License

This project is licensed under the **Apache License 2.0**. See [`LICENSE`](./LICENSE) for details.

---

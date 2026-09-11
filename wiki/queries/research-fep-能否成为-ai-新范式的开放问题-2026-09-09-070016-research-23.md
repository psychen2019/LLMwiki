---
type: query
title: "Research: FEP 能否成为 AI 新范式的开放问题"
created: 2026-09-09
origin: deep-research
tags: [research]
---

# Research: FEP 能否成为 AI 新范式的开放问题

# 自由能原理（FEP）作为 AI 新范式的开放问题

## 概述

自由能原理（Free Energy Principle, FEP）由 [[卡尔·弗里斯顿]]（Karl Friston）提出，宣称"所有生物体的感知、学习与行动都可以被描述为最小化变分自由能——这是最小化感官输入的惊讶度（即低概率）的一种可处理的代理"[1]。该原理近年来被部分研究者和企业视为构建下一代 AI 系统——尤其是"主动推断"（Active Inference）架构——的潜在统一理论 [3]。然而，FEP 究竟能否上升为 AI 的**新范式**，仍然是一个未决的开放问题：既存在支持其范式地位的实验验证与商业押注 [2][3]，也缺乏大规模、跨任务的实证对比来证明其相对于当前主流深度学习范式（连接主义/Transformer 路线）的优越性。

---

## FEP 在 AI 中的核心转化路径

从 FEP 到 AI 的范式转化主要通过两条路径展开：

### 1. 主动推断（Active Inference）

主动推断将 FEP 从神经科学描述转化为**生成式行为策略**：智能体通过持续最小化期望自由能（Expected Free Energy）来同时完成感知（更新世界模型）与行动（选取符合偏好的观测）[3]。这一框架天然地将"预测"与"决策"统一在同一个目标函数之下，被研究者视为对当前"感知—决策—控制"分模块堆叠的 AI 架构的一种替代方案。

### 2. 预测编码（Predictive Coding）

FEP 的另一个工程化落点是层级预测编码网络——其核心是用自上而下的预测与自下而上的预测误差来替代传统的前馈-反向传播结构 [3]。这一思路与 [[预测机器]]、层级贝叶斯推断（Bayesian brain）有深厚的概念亲缘性。

---

## 关键参与者：VERSES AI 与 Genius

在将 FEP 推向工业级 AI 产品的尝试中，[[verses-ai]]（VERSES AI）是目前最具代表性的实体。该公司开发了名为 **Genius™** 的认知架构，明确以 FEP 与主动推断为核心，试图构建"由自然启发的智能体"（Smarter by Nature™）[1][4]。在 2025 年 8 月的"Kar's Corner"中，Friston 本人也将相关研究定位为"具有生物启发性（biomimetic）的自然智能生态系统视角"，并强调其与"主动推断和自由能原理"在认知科学、计算精神病学中的应用一致性 [5]。

VERSES 同时布局了 **Agentic Enterprise Intelligence™** 与 **Spatial Web** 等产品线，试图把 FEP 框架从认知模型拓展到多智能体协作与空间语义网络 [3][4]。

---

## 支持 FEP 成为新范式的证据

### 实验验证层面

2024 年前后出现的实验研究被部分报道解读为"Friston 的 AI 定律被证明"——即神经元层面的放电与学习机制可以被 FEP 所描述的变分推断过程所解释 [2]。如果该结论成立，意味着 FEP 不仅是高层认知的描述性理论，还下沉到了神经回路的微观计算层面。

### 概念统一性层面

研究综述指出，FEP/主动推断"可能重塑 AI 架构、可解释性与伦理框架"——它把感知、行动、学习、注意力分配全部纳入同一个自由能最小化的目标函数，避免了当前深度学习系统中"目标函数碎片化"的问题（感知用交叉熵、决策用 RL 奖励、控制用 MPC 损失等）[3]。

### 商业押注层面

VERSES AI 等公司已经将 FEP 路线产品化，提供了"理论—架构—产品"的完整链条 [1][4]。

---

## 反对或存疑的观点（缺口与矛盾）

尽管如此，将 FEP 视为"AI 新范式"仍面临若干悬而未决的挑战：

1. **缺乏规模化的基准对比**：截至当前可获得的公开资料中，未见 FEP/主动推断系统在 ImageNet、GLUE、Robot Learning 等主流基准上系统性击败 Transformer 路线或 RL 路线的报告 [1][3]。这与"新范式"的提法之间存在显著张力。

2. **可扩展性（Scalability）未证**：FEP 的数学推导依赖于变分推断，在高维空间中的近似质量是否足以支撑大规模模型的训练，目前仍是开放问题 [3]。

3. **生态成熟度差距**：当前 AI 生态（GPU、Triton、PyTorch、HuggingFace 等）围绕反向传播与稠密矩阵运算高度优化。FEP 路线的工具链、训练基础设施、开发者社区规模仍非常有限 [3]。

4. **"AI 定律"措辞的争议**：将 FEP 上升为"定律"的表述更多见于科普性报道 [2]，而非经过同行评议的共识论文。学界对"FEP 是否能解释一切智能"的**通用性主张**（universal claim）一直存在质疑（详见 [[自由能原理]] 词条中关于其本体论争议的讨论）。

5. **与 [[稳态生存逻辑]] 的潜在张力**：FEP 在生物层面的"最小化惊讶度"指向一种维持系统稳态的保守倾向；而当代 AI 训练范式（尤其是 [[重尾分布]] 中的极端值竞争）则倾向于通过[[复利]]式积累与[[正反馈]]放大特定能力。两者在"智能体应主动求稳还是主动求变"这一[[sdt精英化叙事-vs-稳态生存逻辑-2026-09-09-065725|叙事重心]]上存在深层分歧，这一矛盾尚未被公开文献正面讨论。

---

## 开放问题清单

基于现有材料，以下问题对于判断"FEP 是否能成为 AI 新范式"具有关键意义：

- **OQ-1**：在标准大模型基准（语言、视觉、推理、机器人）上，主动推断架构与 Transformer + RLHF 的性能差距如何随规模变化？
- **OQ-2**：FEP 路线能否在能效（per-FLOP 性能）与样本效率上提供压倒性优势，从而弥补生态劣势？
- **OQ-3**：VERSES AI 的 Genius 架构是否会有公开的、可复现的第三方评测？
- **OQ-4**：FEP 是否能够解释或整合当前大模型中出现的**突现能力**（emergent abilities）？如果不能，其"统一理论"地位将受到削弱。
- **OQ-5**：在多智能体场景中，FEP 是否能比现有的 MARL（多智能体强化学习）框架提供更稳健的协作机制？[5] 中 Friston 的相关表述指向这一方向，但缺乏量化证据。

---

## 建议进一步检索的资料

为推进该开放问题的研究，建议补充以下方向的资料：

1. **VERSES AI 的官方白皮书与技术博客**（尤其是 Genius 的架构说明与基准测试报告）。
2. **Friston 实验室与 UCL 主动推断研究组**近 2 年的同行评议论文，关注其在规模化与可扩展性上的进展。
3. **对比性综述**：寻找明确将主动推断与 Transformer、强化学习进行系统比较的论文（arXiv 关键词：`active inference vs transformer`、`active inference benchmark`）。
4. **批评性文献**：包括对 FEP"万能性主张"（everything-is-free-energy）的学界反驳，例如来自计算神经科学传统（Eliasmith、Dayan 等）的回应。
5. **AGI 路线图文档**：Sam Altman、Yann LeCun、Demis Hassabis 等近期关于"下一代 AI 范式"的公开演讲，与 FEP 立场进行对照。
6. **中文综述**：搜索国内"自由能原理 + 主动推断 + 人工智能"的综述文章，以平衡西方学界的视角。

---

## 相关词条链接

- 概念：[[自由能原理]]、[[主动推断]]、[[预测机器]]、[[知觉推断]]、[[马尔可夫毯]]、[[对齐]]、[[最优惊讶度]]
- 实体：[[卡尔·弗里斯顿]]、[[verses-ai]]、[[斯蒂芬沃尔夫勒姆]]
- 关联议题：[[sdt精英化叙事-vs-稳态生存逻辑-2026-09-09-065725]]、[[稳态生存逻辑]]、[[重尾分布]]、[[复利]]

---

## 引用

[1] "Will Karl Friston's FEP shape 2024?" — Verdict.co.uk  
[2] "Friston's AI Law is Proven: FEP Explains How Neurons Learn" — Spatial Web AI (deniseholt.us)  
[3] "From Neuroscience to Artificial Intelligence: Karl Friston's Free Energy Principle and the Rise of Active Inference" — ResearchGate (PDF)  
[4] "Videos | Free Energy Principle" — Verses.ai  
[5] "Karl's Corner | August 2025" — Verses.ai

## References

1. [Will Karl Friston's FEP shape 2024? - Verdict](https://www.verdict.co.uk/friston-free-energy-principle-fep-ai/) — verdict.co.uk
2. [Friston's AI Law is Proven: FEP Explains How Neurons Learn - Spatial Web AI](https://deniseholt.us/fristons-ai-law-is-proven-fep-explains-how-neurons-learn/) — deniseholt.us
3. [(PDF) From Neuroscience to Artificial Intelligence: Karl Friston's Free Energy Principle and the Rise of Active Inference](https://www.researchgate.net/publication/397380587_From_Neuroscience_to_Artificial_Intelligence_Karl_Friston's_Free_Energy_Principle_and_the_Rise_of_Active_Inference) — researchgate.net
4. [Videos | Free Energy Principle - Verses.ai](https://www.verses.ai/videos/tag/free-energy-principle) — verses.ai
5. [Karl's Corner | August 2025](https://www.verses.ai/videos/karls-corner-august-2025) — verses.ai

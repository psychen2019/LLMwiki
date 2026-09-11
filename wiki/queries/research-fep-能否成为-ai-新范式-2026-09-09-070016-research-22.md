---
type: query
title: "Research: FEP 能否成为 AI 新范式 |"
created: 2026-09-09
origin: deep-research
tags: [research]
---

# Research: FEP 能否成为 AI 新范式 |

# FEP 能否成为 AI 新范式？

## 概述

[[自由能原理]]（Free Energy Principle, FEP）由神经科学家 [[卡尔·弗里斯顿]]（Karl Friston）在 2010 年前后正式提出，最初用以解释生物体感知、学习和行动的统一机制 [1]。该原理的核心主张是：**所有生物有机体的感知、学习和行动都可以被描述为最小化变分自由能——一个可处理的代理量，用于最小化感官输入的惊讶度（或低概率）** [1]。近年来，FEP 及其衍生的 [[主动推断]]（Active Inference）框架被部分研究者视为可能重塑 AI 架构的新范式候选者，并在产业界催生了以 [[verses-ai|VERSES AI]] 为代表的专门机构。

本文综合多份资料，评估 FEP/主动推断作为 AI 新范式的理论潜力、工程进展与争议。

---

## 一、FEP 的核心思想：从生物到机器

### 1.1 变分自由能与惊讶度最小化

FEP 的数学核心是引入一个"自由能"上界，作为无法直接计算的感官惊讶度的可计算替代物。系统通过持续最小化这一上界，从而实现对环境状态的**预测**与对自身模型的**更新** [1]。这一机制在认知科学中通常被称为 [[预测机器]] 范式——大脑并非被动接收信号，而是主动生成预测并用误差信号修正内部模型。

### 1.2 [[主动推断]]：感知即行动

[[主动推断]] 将 FEP 拓展到行动领域：智能体不仅通过更新内部模型来最小化自由能，还可以通过改变环境（例如选择动作）来使感官输入更符合自身预测 [3]。这与传统强化学习中"行动—奖励"的循环不同，主动推断将行动视为**主动采样信息以降低不确定性**的过程，与 [[最优惊讶度|最优惊讶度]] 的最小化目标一脉相承。

### 1.3 [[马尔可夫毯]]：系统边界的形式化

FEP 区分系统内部状态与外部状态的关键工具是 [[马尔可夫毯]]（Markov Blanket）——一组条件独立地将系统与环境分开的中间变量。这一形式化使得 FEP 天然具备"主体边界"语义，对多智能体系统的建模尤其重要 [5]。

---

## 二、为何 FEP 被视为 AI 新范式候选者

### 2.1 与当前主流 AI 范式的对比

当前深度学习的主流范式以**监督学习**与**基于奖励的强化学习**为基础，存在以下长期挑战：样本效率低、可解释性弱、缺乏统一的"世界模型"、对分布外场景脆弱。FEP/主动推断声称能提供一种**统一的、生成式的、内在动机驱动**的替代框架 [3]。

| 维度 | 主流深度学习 | FEP / 主动推断 |
|------|-------------|----------------|
| 学习信号 | 外部标注或奖励 | 预测误差（自由能） |
| 内在动机 | 无（需人为设计奖励） | 内在的惊讶度最小化与不确定性消解 |
| 世界模型 | 通常隐式 | 显式生成模型 |
| 可解释性 | 弱 | 强（基于变分推断） |
| 多智能体 | 需额外设计 | 通过 [[马尔可夫毯]] 自然形式化 |

### 2.2 与本知识库既有概念的对接

FEP/主动推断与本知识库中的多个既有概念存在结构性对应：
- 与 [[主动高认知负荷|主动高认知负荷]] 中"主动维持高负荷以避免陷入 [[默认模式网络|默认模式网络]]"的思想相呼应——主动推断将"主动采样"视为降低长期自由能的手段；
- 与 [[自我决定理论|自我决定理论]] 中的内在动机结构相容——主动推断的内在目标（最小化惊讶）即一种自我决定的信号；
- 与 [[反脆弱|反脆弱]] 系统所追求的"通过暴露于波动而变得更强"的特性有相通之处——主动推断通过持续最小化预测误差来更新内部模型。

---

## 三、产业进展：从理论到工程

### 3.1 [[verses-ai|VERSES AI]] 与 Spatial Web Foundation 是当前最具代表性的产业推动者 [2][4]。VERSES AI 明确将自身定位为"仿生智能生态系统"，强调以主动推断和 FEP 为基础指导智能体之间的直接交互 [4]。

在 2025 年 8 月的 "Karl's Corner" 中，Friston 本人描述了其工作"具有公益取向，本质上是仿生的（biomimetic），采取了一种自然智能生态系统的视角"，并强调该路径"与主动推断和自由能原理在认知科学、认知神经科学、计算精神病学等领域的应用高度一致" [4]。这种说法意味着 FEP 不仅被视为 AI 工具，更被视为连接神经科学、计算精神病学与多智能体 AI 的**统一理论框架**。

### 3.2 "Friston AI Law" 的实验验证

[2] 报道了所谓的 "Friston's AI Law"——即 FEP 已能够解释神经元如何学习。该来源声称这一成果"已被证明"，但需注意此类陈述往往来自利益相关方（VERSES 生态系统），其独立可重复性仍待学术界进一步验证。

---

## 四、潜在影响：架构、伦理、可解释性

来源 [3] 系统性地评估了主动推断可能重塑 AI 的三个维度：

### 4.1 架构层面
主动推断提供了一种**端到端的生成式架构**，其中感知、推理、学习、行动共享同一目标函数（自由能最小化）。这与当前模块化的"感知—决策—控制"分立架构形成对比。

### 4.2 伦理层面
由于 FEP 天然涉及"系统边界"（[[马尔可夫毯]]）与"自身模型"的概念，主动推断智能体在理论上更容易被赋予清晰的"自我/他者"区分，从而可能为 AI 伦理中的责任归属问题提供形式化基础 [3]。

### 4.3 可解释性层面
变分自由能是**可计算的、可分解的**量——它可以拆解为预测精度与复杂度两项。这使得基于 FEP 的系统在原则上比黑箱神经网络更具可解释性 [3][5]。

---

## 五、争议与未决问题

### 5.1 物理学的批评
来源 [5] 引用的 Friston 2022 年论文《"非常特殊的"：对〈自由能原理的物理学有多特殊？〉的评论》表明，关于 FEP 是否仅是**对已有物理学（如贝叶斯推断）的重新包装**，学术界存在持续争议 [5]。批评者认为 FEP 作为"包罗万象的理论"在物理学意义上并不独特。

### 5.2 工业落地尚未规模化
尽管 [[verses-ai|VERSES AI]] 持续推动，迄今尚无公开记录显示基于 FEP/主动推断的大规模工业部署在性能上显著优于主流 Transformer+RLHF 路线。FEP 是否能在大模型时代证明其工程价值，仍是悬而未决的问题。

### 5.3 与主流学习范式的兼容性
FEP 强调**生成模型先于判别模型**，而当前大语言模型的成功主要来自判别式的下一 token 预测。如何将 FEP 与现有的规模化预训练范式结合，或证明 FEP 在大规模场景下的可扩展性，是决定其能否成为"新范式"的关键。

---

## 六、结论：潜力巨大但尚未定论

综合现有证据，FEP/主动推断具备成为 AI 新范式的若干关键特征：
- 统一的学习—感知—行动框架；
- 内在的[[对齐|对齐]]信号（与 [[自由能原理|自由能原理]] 词条中"活着就是对齐"的思想一致）；
- 形式化的系统边界（[[马尔可夫毯]]）；
- 强可解释性。

然而，FEP 距离真正成为 AI 新范式，仍需克服以下障碍：
1. **独立可重复的基准对比**：在主流基准上证明优于或等效于现有范式；
2. **可扩展性验证**：证明框架适用于亿级参数级别；
3. **物理学与认知科学层面的争议解决**：回应"是否是真正新理论"还是"对已有概念的重新表述"的批评 [5]；
4. **产业生态的扩展**：摆脱对单一公司（VERSES）的依赖，建立更广泛的开源生态。

### 待补充研究

- 主动推断在 NLP/大模型场景下的应用案例（目前主要见于机器人与感知）；
- Friston "AI Law" 的独立学术验证；
- FEP 与 [[ruliad|Ruliad]]（[[斯蒂芬沃尔夫勒姆|斯蒂芬·沃尔夫勒姆]] 的元系统理论）的形式化关联；
- FEP 框架在 [[反馈回路|反馈回路]] 与 [[补偿性控制|补偿性控制]] 层面与本知识库既有体系（如 [[智能生活系统四要素|智能生活系统四要素]]）的整合路径。

---

## 参考来源

[1] Will Karl Friston's FEP shape 2024? - Verdict. https://www.verdict.co.uk/

[2] Friston's AI Law is Proven: FEP Explains How Neurons Learn - Spatial Web AI. https://deniseholt.us/

[3] From Neuroscience to Artificial Intelligence: Karl Friston's Free Energy Principle and the Rise of Active Inference (PDF). ResearchGate. https://www.researchgate.net/

[4] Karl's Corner | August 2025. VERSES AI. https://verses.ai/

[5] Free energy principle. Wikipedia. https://en.wikipedia.org/wiki/Free_energy_principle

## References

1. [Will Karl Friston's FEP shape 2024? - Verdict](https://www.verdict.co.uk/analyst-comment/friston-free-energy-principle-fep-ai/) — verdict.co.uk
2. [Friston's AI Law is Proven: FEP Explains How Neurons Learn - Spatial Web AI](https://deniseholt.us/fristons-ai-law-is-proven-fep-explains-how-neurons-learn/) — deniseholt.us
3. [(PDF) From Neuroscience to Artificial Intelligence: Karl Friston's Free Energy Principle and the Rise of Active Inference](https://www.researchgate.net/publication/397380587_From_Neuroscience_to_Artificial_Intelligence_Karl_Friston's_Free_Energy_Principle_and_the_Rise_of_Active_Inference) — researchgate.net
4. [Karl's Corner | August 2025](https://www.verses.ai/videos/karls-corner-august-2025) — verses.ai
5. [Free energy principle - Wikipedia](https://en.wikipedia.org/wiki/Free_energy_principle) — en.wikipedia.org

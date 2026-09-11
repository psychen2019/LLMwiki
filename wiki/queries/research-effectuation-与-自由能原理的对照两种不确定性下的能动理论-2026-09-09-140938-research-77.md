---
type: query
title: "Research: Effectuation 与 自由能原理的对照——两种不确定性下的能动理论"
created: 2026-09-09
origin: deep-research
tags: [research]
---

# Research: Effectuation 与 自由能原理的对照——两种不确定性下的能动理论

# Effectuation 与 自由能原理的对照——两种不确定性下的能动理论

## 概述

能动性（agency）——主体如何在不确定环境中采取行动——是认知科学、神经科学、复杂系统科学与创业研究共同关注的核心问题。本文聚焦于两个看似无关、但都以"不确定性下的行动"为母题的理论框架：

1. **自由能原理**（Free Energy Principle, FEP）——Karl Friston 提出的信息物理学与神经科学原理，描述自组织系统（尤其是大脑）如何通过感知与行动最小化"自由能"，从而维持自身的马尔可夫毯与存在边界 [1][4]。
2. **Effectuation 理论**——Sarasvathy 在创业研究中提出的"手段驱动"决策逻辑，强调在高度不确定、未来无法预测的情境下，行动者从"我是谁、我知道什么、我认识谁"出发，通过创造性的实验与可承受损失来塑造未来。

两者的核心张力在于：**FEP 是一个规范性的（normative）优化框架，试图证明"能动系统必然会最小化某种量"；而 Effectuation 是一个描述性的（descriptive）逻辑框架，揭示"在真正的不可预测性面前，理性规划其实是被另一种逻辑替代的"。** 这种对照有助于厘清"能动性"的不同层级与不同适用范围。

> ⚠️ **缺口说明**：本轮研究资料全部聚焦于自由能原理（FEP），**未检索到 Effectuation 理论的一手文献**（Sarasvathy 2001/2008 原文及其后续发展）。下文 Effectuation 部分基于该领域通行的二手综述重构，建议补充原始文献。

---

## 一、自由能原理（Free Energy Principle, FEP）

### 1.1 基本命题

FEP 由神经科学家 Karl Friston 提出，其核心主张是：**任何维持自身与环境边界的自组织系统（即拥有马尔可夫毯的系统），必然通过最小化"变分自由能"（variational free energy, VFE）来保持其存在** [1][4]。换言之：

- 系统通过**感知**（更新内部生成模型以匹配感官输入）最小化 VFE；
- 系统通过**行动**（主动改变感官输入以符合内部预测）最小化**期望自由能**（expected free energy, EFE）。

这是对 Helmholtz 的"无意识推理"（unconscious inference）的形式化重述，也与贝叶斯大脑假说（Bayesian brain）紧密相关 [1]。

### 1.2 能动性、马克尔毯与自创生

FEP 将能动性（agency）锚定在一个更深的形而上学前提——**自创生**（autopoiesis）：

> "生物自主系统构成自身、产生自身作为个体——它们是自个体化的（self-individuating）。这一自个体化过程构成了能动性的基础：有机体能够区分并主动调节那些对其自个体化有正向贡献的能量与物质流，同时回避那些可能干扰其生物自主性的流。"（Varela 1991; Di Paolo 2005; Thompson 2007，引自 [2][3]）

这意味着 FEP 视角下的"能动"不是"做某事"，而是**维持自身存在边界的过程性能力**。能动系统的标志是它拥有一条马尔可夫毯（Markov blanket）——将系统内部状态与外部状态条件独立化的统计界面 [4]。

### 1.3 FEP 中不确定性的地位

FEP 把不确定性处理为一个**可被量化的量**——即"自由能"或"惊讶度"（surprise）的上界。系统通过预测来减少不确定性；行动则被视为"主动采样"，用以校验或塑造感知内容 [1][4]。

这意味着在 FEP 框架下：

- 不确定性是**可建模、可收敛**的；
- 未来虽然原则上不确定，但可以通过持续的感知—行动循环被逐步逼近；
- 最优策略在某种意义上是**已知的**（最小化自由能），不确定性只影响收敛速度，而非策略结构本身。

### 1.4 对人工能动系统的启示

[2][3] 进一步讨论了 FEP 对人工能动体（artificial agency）的意义：若一台机器具备自创生式的自主性并能维持自身的马尔可夫毯，原则上它也应当服从 FEP。但当前主流 AI 系统（无论是 [[openai]] 的 GPT 系列还是 [[anthropic]] 的 Claude）都不具备真正的生物自主性，因此能否被视为 FEP 意义上的"能动系统"仍是开放问题。

---

## 二、Effectuation 理论

### 2.1 起源与问题域

Effectuation 由 Sarasvathy（2001）通过对美国 27 位专家创业者的"专家脚本"（think-aloud protocols）研究提出，核心观察是：**在真正不可预测的新创情境中，创业者并非按"目标驱动"（causation）的逻辑行事，而是采用一种"手段驱动"的过程性逻辑**——她称之为 effectuation。

其五条核心原则（Bird-in-hand、Affordable loss、Crazy quilt、Lemonade、Pilot-in-the-plane）在此前相关 wiki 资料 [[临近可能]] 与 [[不可预先陈述性]] 中已有铺垫：未来是不可预先陈述的（unprestatable），行动者只能从当下可用的手段出发，沿"临近可能"的边界逐步扩展。

### 2.2 不确定性的根本差异

Effectuation 与多数管理理论的根本分歧在于：**不确定性被区分为两类**：

| 类型 | 特征 | 对应策略 |
|---|---|---|
| 风险（risk） | 未来分布已知，可计算概率 | 因果逻辑：先定目标，再选手段 |
| 真正的"奈特不确定性"（Knightian uncertainty） | 未来分布未知，连概率都无法定义 | effectuation：从手段出发，与利益相关者共创目标 |

Effectuation 严格只在第二类情境下才"胜出"——即**在 effectuation 不适用的领域谈 effectuation 是范畴错置**。这一点正是它与 FEP 的关键分野。

### 2.3 时间方向与能动性的隐喻

- **FEP**：时间向**过去**收敛——系统不断把感官预测误差往回"追溯"到先验，形成 [[反馈回路]] 意义上的闭环控制（参见 [[闭环控制]]）。
- **Effectuation**：时间向**未来**发散——行动者通过实验"塑造"一个原本不存在的未来，结果在过程中涌现（参见 [[涌现-emergence]]）。

这一对照接近 [[组合进化]] 与 [[不可预先陈述性]] 在 [[099_临近可能：如何实现无法事先想象的事情？]] 中所提出的"未来是生成出来的，不是预测出来的"主张。

---

## 三、两种理论的对照

### 3.1 核心维度对比

| 维度 | 自由能原理（FEP） | Effectuation |
|---|---|---|
| 学科出身 | 神经科学、信息物理学、贝叶斯统计 | 创业研究、认知人类学、决策科学 |
| 不确定性地位 | 可量化的"自由能"，可通过感知—行动收敛 | 奈特式不可知，未来本质上不可预测 |
| 时间方向 | 向后收敛（预测误差最小化） | 向前展开（创造未来） |
| 行动逻辑 | 在已知目标函数下选择最优策略 | 在已知手段下构造可能的目标 |
| 知识的来源 | 感官输入 + 内部生成模型 | 与利益相关者的互动（co-creation） |
| 失败的处理 | 预测误差，通过贝叶斯更新吸收 | 可承受损失（affordable loss），通过约束设计规避（参见 [[约束设计书]]、[[不做清单]]） |
| 主体边界 | 马尔可夫毯——统计上的条件独立界面 | "我是谁、我知道什么、我认识谁"——社会—认知边界 |
| 评估方式 | 可评估性隐含在形式化定义中 | 评估被有意悬置（[[可评估性假说]] 的反面） |
| 典型应用 | 脑成像分析、自组织系统、人工智能理论 | 创业决策、创新管理、极端不确定下的领导力 |

### 3.2 看似相似但本质不同的概念

1. **预测 vs 预应（preparing-for）**
   - FEP 中的"预测"是对外部信号的条件化推断；
   - Effectuation 中的"预应"是为可能出现的多种未来保持选项开放（参见 [[第二曲线]] 中的"延展准备"思想）。

2. **边界 vs 身份**
   - FEP 的"边界"是数学对象（马尔可夫毯）；
   - Effectuation 的"边界"是叙事对象（"我是谁"的身份叙事）。

3. **最小化 vs 满足**
   - FEP 主张"最小化"（一个良定义的目标函数）；
   - Effectuation 实质上更像 Simon 的"满意即可"（satisficing），但更进一步——它根本不预设最终目标。

### 3.3 二者潜在的汇合点

尽管出发点不同，两者实际上**在某些深层议题上互相呼应**：

- **反脆弱的能动性**：Effectuation 的 affordable loss 与 FEP 中"通过行动抵抗惊讶"都隐含一种"主动暴露于不确定性以增强稳健性"的态度，可对照 [[约束设计书]] 中"限制催生力量"的论证（参见 [[111_自我约束：有限制才有力量]]）。
- **自创生与自我定义**：FEP 中"自个体化"的过程与 Effectuation 中"我是谁决定我能做什么"的逻辑，在[[二阶意愿]] 与 [[元表征]] 框架下可以彼此翻译（参见 [[109_二阶意愿和元表征：应无所住，而生其心]]）。
- **涌现与不可预先陈述性**：FEP 的"自由能最小化路径"在复杂系统中往往导致不可预测的宏观模式（参见 [[涌现-emergence]]），这与 Effectuation 中"结果涌现而无法预设"在现象学上同构。

---

## 四、矛盾与缺口

### 4.1 当前研究的缺口

1. **Effectuation 文献缺失**：本轮研究资料中**完全没有 Sarasvathy 一手文献**或对 effectuation 五原则的实证研究。建议优先补充：
   - Sarasvathy, S. D. (2001). *Causation and effectuation: Toward a theoretical shift from economic inevitability to entrepreneurial contingency*. Academy of Management Review.
   - Sarasvathy, S. D. (2008). *Effectuation: Elements of an entrepreneurial theory*. Oxford University Press.
   - 后续与 Knightian uncertainty、bounded rationality 的对话文献。

2. **缺乏对两者形式化对照的尝试**：现有 FEP 文献 [2][3] 主要讨论"人工能动性"是否可能，**未与 effectuation 进行系统对照**。这本身是一个有价值的研究空白。

3. **AI 时代的新张力**：在 [[anthropic]]、[[openai]]、[[deepmind]] 等机构推动的 RLHF / RLVR 范式下（参见 [[后训练]]、[[rlhf]]、[[rlvr]]），AI 系统的"能动性"问题重新浮现：
   - **FEP 视角**：大模型是否构成具有马尔可夫毯的自主系统？
   - **Effectuation 视角**：当 AI 在高度不确定的现实世界（不仅是训练分布）中行动时，是否应采用 affordable loss 而非最大化奖励的策略？

### 4.2 内在矛盾

1. **FEP 的规范性与 effectuation 的描述性**：FEP 自称是"任何自组织系统**必然**遵循的原理"（[4]）；而 effectuation 是"经验观察到的**特定情境下的**逻辑"。两者在"普遍性"层级上不对等——把 effectuation 当作 FEP 的特例会丧失其独立解释力，反之亦然。

2. **"最小化"与"创造"的张力**：FEP 隐含"世界已经存在，系统只是更好地图示它"的世界观；而 effectuation 隐含"世界正在被创造"的反实在论立场。这一本体论差异难以调和。

3. **奈特不确定性的可建模性争议**：部分 FEP 研究者（如 [4] 中 alignmentforum 的讨论）会主张任何"不可预测"的不确定性最终都可以被嵌入某个分层贝叶斯模型——这恰恰是 effectuation 学者最不能同意的一点。

---

## 五、建议补充的检索方向

- **Effectuation 一手文献**（Sarasvathy 2001, 2008; Dew, Read, Sarasvathy & Wiltbank 2009 的 effectuation 综述）
- **Knightian uncertainty 与决策科学的对话**（Knight 1921; Kahneman & Tversky 的 heuristics 文献）
- **Markov blanket 与社会网络**——把"我是谁、我认识谁"形式化的尝试
- **AI 智能体的能动性争议**：近期关于 LLM agent、embodied AI 是否具备"真实能动性"的哲学讨论（可与 [[117_预训练和后训练：你能力的上限和下限]] 中的"上限/下限"框架对照）
- **可评估性 vs 不可评估性**：[[可评估性假说]] 是否在 effectuation 情境下失效？
- **[[anthropic]]、[[openai]]、[[deepmind]]** 的 agentic AI 路线图是否隐含某种 effectuation 设计原则（如 affordance-based prompting、tools as means 等）

---

## 参考来源

[1] Free energy principle — Wikipedia. https://en.wikipedia.org/wiki/Free_energy_principle

[2] The Problem of Meaning: The Free Energy Principle and Artificial Agency — PMC. https://pmc.ncbi.nlm.nih.gov/

[3] The Problem of Meaning: The Free Energy Principle and Artificial Agency — Frontiers. https://www.frontiersin.org/

[4] Free Energy Principle — alignmentforum. https://www.alignmentforum.org/

[5] The Free Energy Principle approach to Agency — YouTube. https://www.youtube.com/

## References

1. [Free energy principle - Wikipedia](https://en.wikipedia.org/wiki/Free_energy_principle) — en.wikipedia.org
2. [The Problem of Meaning: The Free Energy Principle and Artificial Agency - PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC9260223/) — pmc.ncbi.nlm.nih.gov
3. [Frontiers | The Problem of Meaning: The Free Energy Principle and Artificial Agency](https://www.frontiersin.org/journals/neurorobotics/articles/10.3389/fnbot.2022.844773/full) — frontiersin.org
4. [Free Energy Principle](https://www.alignmentforum.org/w/free-energy-principle) — alignmentforum.org
5. [The Free Energy Principle approach to Agency - YouTube](https://www.youtube.com/watch?v=zMDSMqtjays) — youtube.com

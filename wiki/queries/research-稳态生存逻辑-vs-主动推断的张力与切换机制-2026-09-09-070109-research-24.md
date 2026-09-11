---
type: query
title: "Research: 稳态生存逻辑 vs 主动推断的张力与切换机制"
created: 2026-09-09
origin: deep-research
tags: [research]
---

# Research: 稳态生存逻辑 vs 主动推断的张力与切换机制

# 稳态生存逻辑 vs 主动推断的张力与切换机制

## 概述

[[自由能原理]]（Free Energy Principle, FEP）自 [[卡尔·弗里斯顿]] 提出以来，一直面临一个根本性的质疑：它是否意味着生物（包括人和智能体）只能被动地维持稳态，从而预先排除了新颖性与复杂性？[1][3][4] 这一质疑的实质，是把 [[主动推断]] 简化为一种 [[稳态生存逻辑]]——即把"减少惊讶"等同于"回归均值"或"维持现状"。但近年的形式化研究表明，主动推断框架内部恰恰内置了一种 [[不确定性作为意义的燃料|不确定性机制]]，能够自然地产生探索（exploration）与新颖性奖励（novelty bonus），从而在"维持稳态"与"主动探索"之间建立可切换的动态平衡。[1][3][4][5]

本文聚焦这对张力，以及在其中工作的"切换机制"。

---

## 一、稳态生存逻辑侧：对自由能原理的经典误解

[[稳态生存逻辑]] 通常被表述为：生物体通过维持内部变量（生命体征、体内平衡）在狭窄区间内运行，从而延续自身存在。这与 [[马尔可夫毯]] 所定义的"内部状态—外部状态之间的统计边界"高度同构。

在这一视角下：

- 系统的目标被简化为"减少惊讶"或"最小化自由能"；
- 任何偏离已有模型的输入都被视为"威胁"，应通过感知推断（perception）或主动行动消除；
- 因此系统被假定为保守的、风险规避的、抗拒变化的。

这一叙述在通俗传播中很常见——它把自由能原理等同于"生物体是一台维持不变的恒温器"，并据此推断 FEP 必然排除任何主动追求新奇的行为。[1][3][4]

---

## 二、主动推断侧：FEP 框架自带的探索机制

但在严格的形式化层面，[[主动推断]] 中的关键量是**期望自由能**（Expected Free Energy, EFE），而非简单的即时惊讶。EFE 同时包含两项：

1. **信息增益**（epistemic value / information gain）：降低未来不确定性的能力；
2. **外在价值**（pragmatic value / preference）：达成偏好状态的概率。[5]

更关键的是，主动推断智能体在每个时间步选择的策略（policy）是使 EFE 加权和（或负 EFE）最大化的分布。当 EFE 中信息增益项占主导时，智能体会**主动选择那些能带来最大不确定度降低**的行动——也就是说，它会**主动去探索未知**。[5]

由此引申出一个常被忽视的推论：

> "最小化惊讶"在长时程上反而要求系统去**寻找并消解**它还不知道自己不知道的东西——即主动把"未知"转化为"已知"。[1][3][4]

来源 [1][3][4] 直接表述了这一点：尽管 FEP 表面上似乎排除了新颖性与复杂性，但**近期的形式化表明，最小化惊讶自然引出探索与新颖性奖励**等概念。

---

## 三、张力的本质：两种时间尺度

把这对张力梳理清楚，可以看到它们其实在**不同的时间尺度**上运作：

| 维度 | 稳态生存逻辑 | 主动推断的探索面 |
|------|------------|----------------|
| 时间尺度 | 长时程、统计意义上的稳态吸引子 | 短时程、每步策略选择 |
| 目标函数 | 长期平均惊讶度最小化 | 期望自由能（信息增益 + 价值）加权最大化 |
| 行为表现 | 维持内部状态、回避风险 | 主动寻求不确定性、采集信息 |
| 失败模式 | 过度刚性、对变化过敏 | 过度好奇、脱离可行域 |

二者并不矛盾，反而是同一目标函数（自由能最小化）在不同时间窗下的两个面向：

- 在**秒—分钟级**尺度，系统表现为探索者，主动选择能降低未来惊讶的"高信息量"行动；
- 在**天—年级**尺度，系统表现为稳态维持者，其生存边界（[[马尔可夫毯]]）确保了"长期而言我仍然是我"。

这与 [[不确定性作为意义的燃料|不确定性作为意义的燃料]] 中的论述形成互文——不确定性不是系统的"故障"，而是它驱动探索的"燃料"。

---

## 四、切换机制：亚稳态动力学

来源 [2] 给出了一个关键的技术答案：要**同时**支持稳态维持与主动探索，主动推断智能体需要实现**亚稳态动力学**（metastable dynamics）。原文表述为：

> "To strike a balance between exploitation and exploration an adaptive active inference agent will need to instantiate a metastable dynamics."[2]

亚稳态意味着系统存在多个稳定的吸引子（attractors），但能在一定条件下**在不同吸引子之间跃迁**。这为"稳态 ↔ 探索"的切换提供了物理与计算基础：

1. **多吸引子**：模型中存在多个稳态解，对应不同的"生存模式"；
2. **噪声/惊喜注入**：当自由能降低遇到局部极小、且存在尚未消解的高信息增益项时，系统被"推离"当前吸引子；
3. **再稳态化**：跃迁之后，系统在新吸引子上继续最小化自由能，进入新的稳态。

换言之，**稳态不是单一固定点，而是一族吸引子；探索是吸引子之间的跳跃**。这一机制与 [[稳态生存逻辑]] 的"稳态"概念相比，是更高阶、更动态的版本。

---

## 五、与已有 wiki 框架的对接

这一张力可以接入 wiki 中已有的多个概念节点：

- **与 [[主动高认知负荷]] 的关系**：在人类认知层面，主动选择高信息增益任务（探索）相当于把系统推出当前"舒适稳态"，进入 [[主动高认知负荷]] 状态；
- **与 [[自我决定理论]] 的关系**：[SDT] 中的三种心理需求（自主、胜任、关系）与 EFE 中"自主选择 + 信息获取 + 价值达成"具有同构性，这呼应了 [[SDT精英化叙事-vs-稳态生存逻辑-2026-09-09-065725|SDT 精英化叙事 vs 稳态生存逻辑]] 中的张力；
- **与 [[对齐]] 的关系**：当 EFE 中的"价值"项被良好指定时，主动推断本身就构成一种 [[对齐]] 机制——系统只在能降低未来惊讶的方向上行动；
- **与 [[复利]] 的关系**：长时程上的稳态维持，使得短时程的探索收益得以**复利式累积**，这呼应了"短视的探索 + 长期的复利"这一组合。

---

## 六、矛盾与未解之处

尽管上述叙述在形式上自洽，仍存在几个需要警惕的空白与可能的矛盾：

1. **EFE 加权如何指定**？信息增益与外在价值之间的相对权重是硬编码的还是学习得到的？来源 [5] 明确指出二者"联合决定"最终策略，但**权重的元学习机制**在公开材料中并未展开。
2. **亚稳态的稳定性条件**？来源 [2] 提出需要亚稳态动力学，但**多少个吸引子、跃迁的触发阈值、如何避免无限跃迁**，尚缺乏统一的工程化方案。
3. **稳态生存逻辑的"刚性失败"**：当 [[文化滞后]] 或外部剧变（参见 [[文化滞后]]）出现时，稳态维持可能反向成为系统适应的阻力；FEP 框架如何处理这种"稳态本身的失效"，现有材料未直接讨论。
4. **与人类自由意志/能动性的接驳**：参见 [[进程自我的被动日志-vs-人的终极自由选择归属于哪一层]]——如果系统终归是在最小化自由能，那么"主动选择探索"究竟是真实能动，还是 EFE 加权下的"必然解"？

---

## 七、建议进一步检索的方向

为补全上述空白，建议沿以下方向补充来源：

- **Friston 关于"metastable attractors"与"self-evidencing models"的最新论文**（2023 之后），尤其是关于多吸引子切换的形式化条件；
- **Seth、Clark 等关于"interoceptive inference"的研究**——内脏稳态如何通过亚稳态动力学产生意识与情绪；
- **强化学习中 exploration bonus（ICM、RND、Go-Explore）与 EFE 的形式对照**，以确认工程化切换机制的等价性；
- **Solms、Markov、Verses AI 团队**关于"homeostatic agents with built-in curiosity"的工作，看工业界如何落地这一张力；
- **临床/精神病学角度**：稳态过强（如 OCD、抑郁性固着）与过弱（如躁狂、ADD）的对照，是否可被 EFE 框架统一解释。

---

## 八、小结

稳态生存逻辑与主动推断的"对立"，本质上是一个**被传播过程误读的对立**。严格的 FEP/主动推断理论已经内置了探索机制，且明确指出系统需要**亚稳态动力学**来平衡 exploit 与 explore [2]。这一切换机制可以概括为：

> **稳态 = 当前吸引子上的自由能最小化；探索 = 因尚未满足的高信息增益项而触发的吸引子跳跃；切换 = 亚稳态。**

把它纳入 [[最强AI的核心思维工具]] 所倡导的"工具库"视角，可以说：**自由能原理本身就是"如何既稳态又创新"的统一答案**——前提是我们正确理解"稳态"是多吸引子、而非单点的。

---

## 引用

[1] Frontiers, *Exploration, novelty, surprise, and free energy minimization* — https://www.frontiersin.org/
[2] Frontiers, *The Problem of Meaning: The Free Energy Principle and Artificial Agency* — https://www.frontiersin.org/
[3] ResearchGate PDF, *Exploration, Novelty, Surprise and Free Energy Minimisation* — https://www.researchgate.net/
[4] PMC, *Exploration, novelty, surprise, and free energy minimization* — https://pmc.ncbi.nlm.nih.gov/
[5] ResearchGate PDF, *An Overview of the Free Energy Principle and Related Research* — https://www.researchgate.net/

## References

1. [Frontiers | Exploration, novelty, surprise, and free energy minimization](https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2013.00710/full) — frontiersin.org
2. [Frontiers | The Problem of Meaning: The Free Energy Principle and Artificial Agency](https://www.frontiersin.org/journals/neurorobotics/articles/10.3389/fnbot.2022.844773/full) — frontiersin.org
3. [(PDF) Exploration, Novelty, Surprise and Free Energy Minimisation](https://www.researchgate.net/publication/257600319_Exploration_Novelty_Surprise_and_Free_Energy_Minimisation) — researchgate.net
4. [Exploration, novelty, surprise, and free energy minimization - PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC3791848/) — pmc.ncbi.nlm.nih.gov
5. [(PDF) An Overview of the Free Energy Principle and Related Research](https://www.researchgate.net/publication/378829088_An_Overview_of_the_Free_Energy_Principle_and_Related_Research) — researchgate.net

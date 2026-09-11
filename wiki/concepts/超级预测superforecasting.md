---
type: concept
title: "超级预测（Superforecasting）"
tags: [方法论, 预测, 概率化, 工程化, 闭环]
related: [fermi-izing, brier-score, calibration-resolution, good-judgment-project, philip-tetlock, hedgehog-vs-fox-experts, decision-hygiene, red-teaming, pre-mortem, bayers-formula, subjective-probability, reference-class-forecasting]
sources: ["043_超级预测：给不确定性命名，给自己打分.md"]
created: 2026-09-09
updated: 2026-09-09
---
# 超级预测（Superforecasting）

## 定义

一套"概率化 + 可检验"的方法论闭环：把预测未来从跳大神的手艺升级为可操作、可记分、可学习的工程工作流。

> 预测不是观点的延长线，而是自我校准的工艺。你不是在求一个神谕，你是在训练自己的判断账本。

## 核心思想

**两条支柱**：

1. **概率化**：把所有预测写成概率数字，而非感想或定性判断
2. **可检验**：用 [[concepts/brier-score|布里尔分数]] 等规则为长期预测表现打分

源文强调：

> 概率和检验构成了一个完美闭环：没有概率就没有校准，没有记分就没有学习。

## 三步法

| 步骤 | 名称 | 含义 |
|------|------|------|
| 1 | [[concepts/fermi-izing\|费米化]] | 把云状问题拆解为可操作的小问题 |
| 2 | 参考类打底 + 内部视角微调 | 用 [[concepts/reference-class-forecasting\|外部视角]] 的历史基率作先验，再根据事件特殊性小幅修正 |
| 3 | [[concepts/bayers-formula\|贝叶斯更新]] | 随事件进展用贝叶斯公式微调概率 |

## 与传统预测的区别

| 传统预测 | 超级预测 |
|----------|----------|
| "美国很可能会对伊朗越来越强硬" | "到某年某月某日之前，美国对伊朗目标实施军事打击的概率是 X%" |
| 单道题押注 | 一揽子预测的长期表现 |
| 叙事性论断 | 可结算的数字 |
| 一次性表态 | 持续更新的工作流 |

## 关键纪律

- **不要和稀泥**：避免把所有事都定为 50%（区分度要求）
- **不要一厢情愿**：避免被立场、自尊、从众心理、安全感带偏
- **要写概率，不要写感想**：来源要求的每个问题都必须有数字
- **要记分**：哪怕是短期训练，只要计分就能显著提高预测水平

## 失败模式

源文承认的失败案例（俄乌战争预测）：

- **过度依赖参考类**：此类事件罕见，基率极低
- **低估决策者冒险意愿**：忽略个体特异性
- **低估情报准确度**：过度相信直觉判断而非专业信号

## 与 AI 结合的最新进展（2025）

| 比较项 | 结果 |
|--------|------|
| 单独大语言模型 vs 人类超级预测者 | 大模型**不如**人类 |
| 人类 + 大模型协作 vs 人类单独 | 准确率提高 24%–28% |

解读：

- AI 善于搜索信息
- 人擅长界定问题边界、挑选参考类、决定该忽略哪个变量
- AI 能进一步帮人把自尊从判断里剥离出去

## 一句话总结

> 不确定性一旦被拆解和命名、被写成概率，它就从一种令人恐慌的情绪，变成了可求解的工程问题。

## 相关概念

- 上游：[[concepts/reference-class-forecasting|参考类预测]]（讲 042，第二步直接调用）
- 上游：[[concepts/bayers-formula|贝叶斯公式]]（讲 030，第三步直接调用）
- 上游：[[concepts/subjective-probability|主观概率]]（超级预测是主观概率的工程化实践）
- 平行方法：[[concepts/decision-hygiene|决策卫生]]、[[concepts/red-teaming|红队]]、[[concepts/pre-mortem|事前验尸]]
- 评价工具：[[concepts/brier-score|布里尔分数]]、[[concepts/calibration-resolution|校准度与区分度]]
- 分类视角：[[concepts/hedgehog-vs-fox-experts|刺猬与狐狸型专家]]
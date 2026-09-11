---
type: query
title: 后训练能否推高能力上限？RLVR 长期训练的涌现效应
tags: [后训练, RLVR, 涌现, 开放问题]
related: [后训练, 表面对齐假说, rlvr, 涌现, 开悟, pass@k与pass@1]
sources: ["117_预训练和后训练：你能力的上限和下限.md"]
created: 2026-09-09
updated: 2026-09-09
---

# 后训练能否推高能力上限？RLVR 长期训练的涌现效应

## 提问

[[表面对齐假说]] 主张后训练不添加新能力，只塑造表现。但课程末尾承认：

> "后训练里的 RLVR——也就是不问人喜不喜欢，只按答案客观上对不对来奖励模型——**如果训练得足够久，又能保持探索，也可能推高能力上限**。"

这意味着后训练在某些条件下**确实**能推高 [[pass@k与pass@1]] 中的上限（k 路）。这一现象是否系统？条件是什么？与 [[涌现]] / [[开悟]] 是什么关系？

## 候选证据

| 候选 | 含义 |
|------|------|
| OpenAI o1 类推理模型的"思维链开悟" | 长期 RLVR 训练让模型自发出现长链推理 |
| DeepMind AlphaGo 的 RL 推高 | AlphaGo Zero 通过自对弈超越了人类经验上限 |
| 课程黄高团队 2025 研究 | 仅在 k 数百时追平，k 较小时仍 RL 胜出 |
| [[rlvr]] 与 [[rlhf]] 对比 | RLVR 的硬反馈可能更易推高上限 |

## 进一步研究建议

- 检索"RLVR capability ceiling"
- 检索"reasoning models emergence post-training"
- 检索"long-horizon RL scaling law"
- 检索"chain-of-thought grokking"

## 相关

- [[后训练]]
- [[表面对齐假说]]
- [[rlvr]]
- [[涌现]]
- [[开悟]]
- [[pass@k与pass@1]]
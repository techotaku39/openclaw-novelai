# OpenClaw NovelAI Opus Free

这是一个专门面向 Opus 订阅、同时保留实测免费图片编辑能力的“零 NovelAI 图片 Anlas”OpenClaw Skill 变体。

它保留小说写作、剧情规划、Prompt 设计、账户查询、费用估算、标签建议和本地记录。在 Opus、正常分辨率、单张、28 steps 以内且估算明确为 `0 Anlas` 时，允许文生图、图生图、局部重绘、已有 Vibe 生图、标注，以及部分 Director 工具。

它会禁止：

- 新的 Vibe 编码；
- Director 去背景；
- Precise Reference；
- Enhance；
- 专用放大；
- 批量、高分辨率、超过 28 steps、多样本和并行生图；
- 任何扣 Anlas 的降级或重试。

## 重要区别

“零 Anlas”不等于“没有任何使用额度或费用”：

- Opus 的 V5 免费图片会消耗独立的 V5 Usage Limit；
- 如果 OpenClaw 把文字请求交给第三方模型，第三方模型可能单独收费；
- 网络、主机和其他模型的费用不属于本 Skill 的控制范围。

## 使用边界

如果不是 Opus、费用估算工具缺失、返回空值、返回未知、V5 Usage Limit 已耗尽，或者余额审计发现扣点，Skill 会拒绝或停止后续图片操作。它不会因为用户说“我接受收费”就放行。

想使用新的 Vibe 编码、去背景、Precise Reference、Enhance、专用放大、批量或高分辨率，请改用父项目中的高级版 `openclaw-novelai`。

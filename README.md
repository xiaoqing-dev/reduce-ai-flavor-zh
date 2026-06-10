# reduce-ai-flavor-zh · 中文写作降 AI 味

一个 Claude skill，用于润色中文文章、去掉典型的「AI 味」：

- 大词空话（颠覆 / 赋能 / 底层逻辑）
- 被动句过多、主语模糊
- 逗号制造的「诗化停顿」
- 公式化的平行排比结构
- 替读者下心理判断（"你一定想过……"）
- 一句话一段的散文腔
- 没有证据支撑的宏大结论
- 对着虚空观众广播的语气
- 矫枉过正的「专栏腔」——句句铿锵短促、挤掉所有松弛虚词

核心元原则是**改写，而非删除**——去掉味道，不去掉内容。每一处 AI 味都改写成具体行动、真实主语、人话表达，而不是直接删掉留下逻辑空洞。

## 适用场景

- 基于视频转写 / 会议纪要 / 访谈素材写文章（AI 味最高风险的来源）
- 改写 AI 生成的初稿
- 口播脚本转可读文章
- 润色营销 / 产品 / 技术博客、公众号、Newsletter

## 安装

### Claude Code

把 `skills/reduce-ai-flavor-zh/` 复制到你的 skills 目录：

```bash
# 个人级（所有项目可用）
mkdir -p ~/.claude/skills
cp -r skills/reduce-ai-flavor-zh ~/.claude/skills/

# 或项目级（只在当前项目可用）
mkdir -p .claude/skills
cp -r skills/reduce-ai-flavor-zh .claude/skills/
```

### Claude.ai / Claude 桌面版

在 Settings → Capabilities → Skills 中上传 `skills/reduce-ai-flavor-zh/` 文件夹（或将其打包为 zip 上传）。

## 使用

安装后无需显式调用。当你说「润色」「改一下」「让这篇文章更自然」「去 AI 味」「写得更口语化」「减少翻译腔」时，Claude 会自动应用这个 skill。

## License

MIT

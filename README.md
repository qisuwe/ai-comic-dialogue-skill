# AI Comic Dialogue Skill

AI漫剧人物对话质量提升 Skill。

让角色对话更自然、有性格区分、有潜台词、适合短视频漫剧生成（简洁台词 + 视觉动作协同）。

## 使用方式

将本仓库作为 skill 放到支持 SKILL.md 的 Agent（Claude Code、OpenClaw、Cursor 等）的 skills 目录，或在对话开头说：

> 请读取并遵循 `SKILL.md` 的规则来写/改对白。

触发词示例：
- 帮我提高这段AI漫剧的人物对话质量
- 写一段更自然的角色对话，适合短视频漫剧
- 优化剧本里的对白，让角色更有性格
- 按霸总模板写一段对话

## 文件结构

```
SKILL.md                              ← 主入口（流程 + 原则）
references/examples.md                 ← 基础前后对比示例
references/genre-examples.md           ← 更多题材示例（甜宠/重生/系统流/虐恋/女强）
references/character-voice-templates.md ← 角色声音卡片
references/ai-dialogue-blacklist.md    ← AI 味对白黑名单
evals/                                ← 触发测试
CHANGELOG.md
```

详细规则见 `SKILL.md`。

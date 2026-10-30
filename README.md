# victorable-shuorenhua（说人话）

> 中文实战派去 AI 味改写 Skill。专克伪导师鸡汤、生造隐喻、二元假对比与大词包装；只降调、不加戏。

## 背景

许多经过"二次润色"的文本虽然去掉了"赋能、闭环"等旧大词，却衍生出新型 AI 通病：强凑对仗金句（"不是……而是……"）、生造惊悚动词（"业务被杂事生吞"）、假装热血的网文腔。

本 Skill 面向真实业务场景，强调**事实白描**、**只降调不加戏**，让职场汇报、复盘与方案呈现出业务骨干真实、洗练的手感。

## 安装

支持 Agent Skills 的工具（Claude Code / Codex / Cursor / OpenCode 等）：

```bash
npx skills add https://github.com/victorpaulee/victorable-shuorenhua
```

或手动克隆到 skills 目录：

```bash
git clone https://github.com/victorpaulee/victorable-shuorenhua ~/.claude/skills/victorable-shuorenhua
```

Codex 中使用：

```bash
codex exec -C . "读取 ./SKILL.md，按其中规则改写以下文本：..."
```

## 使用

```
帮我去 AI 味：[粘贴简体中文]
```

或指定场景：

```
用 victorable-shuorenhua 改写下面这段业务复盘，保留数据与判断：[原文]
```

## 规则概要

| 模式 | 典型症状 | 处理 |
| --- | --- | --- |
| 二元假对比 | "不是……而是……"对称金句 | 拆散骨架，直接陈述 |
| 戏剧化隐喻 | "生吞""血洗"等重动词 | 换中性动词 |
| 咨询黑话 | "协作者拓扑""责任真空" | 换成一线人话 |
| 强凑排比 | 三句式机械并列 | 打散重组 |
| 假导师共情 | "想说一句实话"式铺垫 | 直接删除 |

## 边界

- 保留事实、数字、条件、责任归属与作者判断；只降调，不加强。
- 不编造数据、经历或观点；技术文档与公文不强行改成聊天口吻。

## License

MIT

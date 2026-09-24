# humanizer-zh

中文去 AI 味 / 保真润色 Skill。去掉模板腔和宣传腔，但不改事实、不编故事。

## 安装（Work Buddy）

1. 下载或克隆本仓库
2. 把 `humanizer-zh` 文件夹放到技能目录：

```bash
cp -r humanizer-zh ~/.workbuddy/skills/
```

3. 重启 Work Buddy，或新开一个会话

其他工具同理：放进该工具的 skills 目录即可（如 `~/.claude/skills/`、`~/.agents/skills/`）。

## 怎么用

> 去 AI 味：（粘贴正文）

> 润色一下这封邮件

> 改自然点 / 说人话：（粘贴正文）

要更大幅度改写时明确说：

> 启用创作模式，深度重写：（粘贴正文）

- 默认**保真模式**：只修明显 AI 腔，不改事实、不补细节
- 原文已经自然时**原样返回**，不会为了显得工作过而乱改
- 密码 / API key / 私钥会直接拒收

## 不适用

从零写文章 / 写爆文 / 起标题 / 优化 prompt / 改代码 / 翻译

## 许可

MIT。衍生自 [blader/humanizer](https://github.com/blader/humanizer) → [op7418/Humanizer-zh](https://github.com/op7418/Humanizer-zh)。

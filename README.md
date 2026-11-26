# social-product-video

面向抖音、小红书、视频号等平台的**产品宣传 / 口播种草 / 调性美学片**内容策划与脚本撰写 Agent Skill。

按标准 SOP 执行：理解需求 → 沟通明确 → 创建项目 → 明确目标 → 分解任务 → 分步执行 → 产出 → 复核验收 → 交付。支持缺资料主动催要、消费者语言翻译、Hook 与旁白×镜头分工，以及调性美学片（人文 / 生活方式 / 空镜 / 人物模特）。

**开发者：** 刘淮安

---

## 片型

| 片型 | 说明 |
|------|------|
| 广告宣传片 | 品牌调性、卖点与 CTA，允许广告感 |
| 口播种草 / 讲解 | 真实体验分享；禁参数堆叠；旁白有信息量 |
| 调性美学片 | 主张 / 美学 / 生活方式主导；大量空镜；人物兼模特 |

## 目录

```
social-product-video/
├── SKILL.md                 # 主流程（必读）
├── sop-checklist.md         # 九段 SOP 速查
├── consumer-language.md     # 卖点 → 消费者语言
├── tonal-aesthetic.md       # 调性美学片规范
├── hooks-and-retention.md   # Hook、旁白×镜头、完播
├── platforms.md             # 抖音 / 小红书 / 视频号
├── examples.md              # 示例与反例
└── README.md                # 本说明
```

## 安装

### WorkBuddy

对话里发送：

```
请安装这个 Skill：
https://github.com/liuhuaian01/social-product-video
安装到用户级 skills 目录后告诉我是否成功。
```

或在技能管理中选择「通过 URL 导入」，粘贴本仓库地址。

### 通用 CLI（Cursor / Claude Code / Codex 等）

```bash
npx skills add liuhuaian01/social-product-video -g -y
```

指定 Agent 示例：

```bash
npx skills add liuhuaian01/social-product-video --skill social-product-video -a claude-code -g -y
```

### 手动复制

将本仓库克隆或下载后，把整个文件夹放到对应目录：

| 平台 | 路径 |
|------|------|
| WorkBuddy | `~/.workbuddy/skills/social-product-video/` |
| CodeBuddy | `~/.codebuddy/skills/social-product-video/` |
| Claude Code | `~/.claude/skills/social-product-video/` |
| Cursor | `.cursor/skills/` 或 Agent Store / `.agents/skills/` |

Windows 用户级示例：`C:\Users\<你>\.workbuddy\skills\social-product-video\`

## 使用

装好后可直接说，例如：

- 「用 social-product-video 写一条小红书种草口播」
- 「按调性美学片写羊绒床品，主张是卧室修复感」
- 「/social-product-video」+ 产品资料

## 许可与归属

- **开发者：** 刘淮安
- 本 Skill 为方法论文档与工作流模板；使用时请遵守各内容平台与广告合规要求。

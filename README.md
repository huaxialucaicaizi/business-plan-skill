# Business Plan Skill / 商业计划书 Skill

[![CI](https://github.com/huaxialucaicaizi/business-plan-skill/actions/workflows/ci.yml/badge.svg)](https://github.com/huaxialucaicaizi/business-plan-skill/actions/workflows/ci.yml)

**为初创项目和创业团队提供结构化、可复用的商业计划书、路演材料和孵化器申请文案工作流。**

A structured, reusable workflow for creating business plans, pitch decks, and incubator applications for startups and entrepreneurial teams.

---

## 一句话价值 / Value Proposition

这个 Codex skill 帮助你沉淀项目定位、市场分析、团队介绍、财务预测和申请文案的一致口径，让 AI 在后续写材料时保持结构清晰、逻辑连贯、避免虚构数据。

This Codex skill helps you maintain consistent positioning, market analysis, team profiles, financial projections, and application copy, ensuring structured, logical, and fact-based materials.

---

## 快速开始 / Quick Start

### 安装 / Installation

**方法 1：克隆到用户技能目录（推荐）**

```bash
# 克隆到 Codex 用户技能目录
mkdir -p ~/.agents/skills
cd ~/.agents/skills
git clone https://github.com/huaxialucaicaizi/business-plan-skill.git
```

**方法 2：克隆到项目技能目录**

```bash
# 克隆到项目的 .agents/skills 目录
mkdir -p .agents/skills
cd .agents/skills
git clone https://github.com/huaxialucaicaizi/business-plan-skill.git
```

**方法 3：使用 Codex 内置安装器**

在 Codex 中使用 `$skill-installer` 命令：

```bash
$skill-installer huaxialucaicaizi/business-plan-skill
```

Codex 会自动检测新安装的 skill。如果未显示，请重启 Codex。

Codex automatically detects newly installed skills. If one doesn't appear, restart Codex.

**注：** 其他支持 Agent Skills 的工具（如 Cursor）也可以通过各自的方式安装此 skill。

**Note:** Other tools that support Agent Skills (such as Cursor) can also install this skill through their respective methods.

---

### 验证安装 / Verify Installation

安装完成后，Codex 会自动检测新 skill。可以通过以下方式验证是否正常加载：

After installation, Codex automatically detects new skills. Verify it is loaded:

**简单测试 / Quick Test:**

在 Codex 中向 AI 助手发送以下消息：

Send this message to the AI assistant in Codex:

```
请使用 business-plan-skill 帮我列出一份商业计划书应该包含的核心章节。
```

如果 AI 回复中提到了"项目定位"、"目标客户"、"痛点分析"、"解决方案"等结构化章节，说明 skill 已正常工作。

If the AI responds with structured sections like "项目定位", "目标客户", "痛点分析", "解决方案", the skill is working correctly.

**检查 skill 加载状态 / Check Skill Loading Status:**

你也可以直接询问 AI：

You can also ask the AI directly:

```
请确认 business-plan-skill 是否已加载。
```

**注：** 如果在其他支持 Agent Skills 的工具中使用，验证方法类似。

**Note:** If using in other Agent Skills-compatible tools, the verification method is similar.

---

### 使用示例 / Example Prompts

**中文示例：**

```text
调用 business-plan-skill，帮我把项目介绍压缩到 300 字以内，适合孵化器申请表。
```

```text
用商业计划书 skill 的口径，帮我生成一页竞品分析 PPT 内容。
```

```text
根据这个 skill，帮我更新团队能力和竞争优势部分，目标读者是园区评委。
```

```text
调用商业计划书 skill 整理路演逻辑，再调用 codex-ppt 生成一份高颜值 16:9 商业计划书 PPT。
```

**English examples:**

```text
Use the business-plan-skill to draft a 300-character project summary for an incubator application.
```

```text
Based on this skill, generate a competitor analysis slide for my pitch deck.
```

```text
Use the business-plan-skill to organize the pitch deck narrative, then call codex-ppt to generate a polished 16:9 visual deck.
```

---

## 示例输出 / Examples

查看 [`examples/`](./examples/) 目录了解虚构项目示例输出：

See the [`examples/`](./examples/) directory for fictional project sample outputs:

- **商业计划书大纲** / Business plan outline: [`bp-outline.md`](./examples/bp-outline.md)
- **孵化器申请摘要（约 300 字）** / Incubator application summary (~300 characters): [`incubator-application-summary.md`](./examples/incubator-application-summary.md)
- **路演 PPT 页面大纲** / Pitch deck slide outline: [`pitch-deck-outline.md`](./examples/pitch-deck-outline.md)

**注意：所有示例内容均为虚构，仅用于演示 skill 使用方法。**

**Note: All example content is fictional and for demonstration purposes only.**

---

## 工作原理 / How It Works

### 文件结构 / File Structure

```text
business-plan-skill/
├── SKILL.md                          # Skill 入口文件，定义触发条件和工作流
├── README.md                         # 使用说明
├── LICENSE                           # MIT License
├── CHANGELOG.md                      # 版本更新日志
├── agents/
│   └── openai.yaml                   # Codex skill 元数据
├── references/                       # 可复用的参考文档
│   ├── business-plan-core.md         # 商业计划书核心结构（定位、市场、财务）
│   ├── founder-and-advantage.md      # 创始人背景和竞争优势模板
│   └── application-copy.md           # 孵化器申请和官方表格文案模板
└── examples/                         # 虚构项目示例输出
    ├── README.md
    ├── bp-outline.md
    ├── incubator-application-summary.md
    └── pitch-deck-outline.md
```

### 核心原则 / Core Principles

1. **结构化工作流：** 提供商业计划书、路演材料、申请文案的标准结构和占位符模板
2. **避免虚构数据：** 遵循隐私规则，不虚构姓名、数据、客户、融资等事实
3. **可复用口径：** 在 `references/` 中沉淀项目信息，让 AI 在后续任务中保持一致
4. **灵活适配：** 支持商业计划书、路演 PPT、孵化器申请、项目简介等多种场景

---

## 与 codex-ppt 配合 / Working with codex-ppt

当你需要生成高颜值视觉版 PPT 时，建议先用本 skill 整理内容逻辑，再调用 `codex-ppt` 做视觉化。

When you need a polished visual deck, use this skill first to organize the narrative, then call `codex-ppt` for visualization.

### 推荐流程 / Recommended Workflow

1. 用本 skill 明确项目定位、市场背景、产品方案、商业模式、团队能力、竞争优势、财务预测
2. 将每页 PPT 压缩成一个核心观点、2-4 个支撑要点和一个视觉表达建议
3. 调用 `codex-ppt` 生成统一风格的 16:9 视觉版商业计划书
4. 自查是否覆盖团队能力、商业模式、竞争优势、市场空间、财务数据

### 如何获取 codex-ppt / Where to Get codex-ppt

`codex-ppt` 是由 [@ningzimu](https://github.com/ningzimu) 开发的第三方 Codex skill，用于将文章、报告、大纲等内容转换为整页图片式的演示文稿。

`codex-ppt` is a third-party Codex skill developed by [@ningzimu](https://github.com/ningzimu) that converts articles, reports, and outlines into image-based presentation slides.

**GitHub 仓库 / Repository:** https://github.com/ningzimu/codex-ppt-skill

**快速安装 / Quick Installation:**

最简单的方式是直接让 Agent 帮你安装：

The easiest way is to ask your Agent to install it:

```text
请帮我安装这个 codex-ppt skill，链接是：https://github.com/ningzimu/codex-ppt-skill
```

**手动安装到 Codex / Manual Installation for Codex:**

```bash
npx -y skills@latest add ningzimu/codex-ppt-skill \
  --skill codex-ppt \
  --agent codex \
  --global
```

安装完成后重启 Codex 生效。更多安装方式和使用说明请查看 [codex-ppt-skill 官方文档](https://github.com/ningzimu/codex-ppt-skill#readme)。

After installation, restart Codex. For more installation options and usage instructions, see the [official codex-ppt-skill documentation](https://github.com/ningzimu/codex-ppt-skill#readme).

---

## 如何定制 / How to Customize

如果你想将此 skill 改造为自己项目的专属模板：

If you want to customize this skill for your own project:

1. **修改 `SKILL.md`：** 更新 `name` 和 `description`，添加项目特有的触发词
2. **在 `references/business-plan-core.md` 中替换：** 项目定位、客户、市场、产品和财务信息
3. **在 `references/founder-and-advantage.md` 中替换：** 创始人、团队和竞争优势信息
4. **在 `references/application-copy.md` 中替换：** 常用申请文案和表格默认值
5. **重启 Codex：** 让新的 skill 元数据进入自动触发列表

**隐私提示：** 如果你希望公开分享自己的定制版 skill，请将具体项目数据替换为占位符，避免泄露敏感信息。

**Privacy Note:** If you want to share your customized skill publicly, replace specific project data with placeholders to avoid exposing sensitive information.

---

## 隐私与数据安全 / Privacy and Data Safety

- **不虚构数据：** 本 skill 遵循"不虚构姓名、身份证号、公司注册号、融资数据、客户名称"等隐私规则
- **占位符优先：** 当信息未知时，使用 `待补充` 或询问用户，而非编造事实
- **公开输出清理：** 对于 GitHub 等公开材料，自动移除私密事实，替换为占位符

---

## 贡献 / Contributing

欢迎提交 Issue 或 Pull Request，帮助改进本 skill：

Contributions are welcome! Please submit an Issue or Pull Request to help improve this skill:

- 报告问题或提出改进建议 / Report issues or suggest improvements
- 分享更好的模板结构或文案示例 / Share better template structures or copy examples
- 添加更多适用场景（如创业大赛、政府项目申请） / Add more use cases (e.g., startup competitions, government project applications)

---

## 许可证 / License

本项目采用 [MIT License](./LICENSE) 开源。

This project is licensed under the [MIT License](./LICENSE).

**Copyright (c) 2026 Rui Huang (huaxialucaicaizi)**

---

## 致谢 / Acknowledgments

本 skill 基于 OpenAI Codex 的 [agent skills 规范](https://learn.chatgpt.com/docs/build-skills)构建。

This skill is built based on OpenAI Codex's [agent skills specification](https://learn.chatgpt.com/docs/build-skills).

感谢所有使用、反馈和贡献的朋友。

Thanks to everyone who uses, provides feedback, and contributes to this project.

---

## 联系方式 / Contact

- **作者 / Author:** Rui Huang (华夏路菜菜子)
- **GitHub:** [huaxialucaicaizi/business-plan-skill](https://github.com/huaxialucaicaizi/business-plan-skill)
- **问题反馈 / Issues:** [GitHub Issues](https://github.com/huaxialucaicaizi/business-plan-skill/issues)

---

## 版本历史 / Version History

查看 [CHANGELOG.md](./CHANGELOG.md) 了解版本更新历史。

See [CHANGELOG.md](./CHANGELOG.md) for version history.

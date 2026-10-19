# 贡献指南 / Contributing Guide

感谢你对 business-plan-skill 的关注！我们欢迎各种形式的贡献。

Thank you for your interest in business-plan-skill! We welcome all forms of contributions.

---

## 如何贡献 / How to Contribute

### 1. 提出新增申请场景 / Propose New Application Scenarios

如果你发现 skill 适用于某个未被覆盖的场景（如创业大赛、政府项目申请、企业内部路演等），欢迎提交 Issue：

If you find the skill could be useful for a scenario not yet covered (e.g., startup competitions, government project applications, internal corporate presentations), please submit an issue:

1. 点击 [Issues](https://github.com/huaxialucaicaizi/business-plan-skill/issues) → **New issue**
2. 选择模板「新增申请场景 / New Application Scenario」
3. 描述场景、目标读者、所需材料类型和关键差异点
4. 如果可能，提供示例要求或模板参考

**Click** [Issues](https://github.com/huaxialucaicaizi/business-plan-skill/issues) → **New issue** → Select "新增申请场景 / New Application Scenario" template

### 2. 反馈输出问题 / Report Output Problems

如果在使用 skill 时遇到问题（如格式不符合预期、信息缺失、逻辑不清晰等），请提交 Issue：

If you encounter issues while using the skill (e.g., unexpected format, missing information, unclear logic), please submit an issue:

1. 点击 [Issues](https://github.com/huaxialucaicaizi/business-plan-skill/issues) → **New issue**
2. 选择模板「反馈输出问题 / Report Output Problem」
3. 描述问题、预期行为、实际输出，以及重现步骤
4. 请移除任何敏感或私密信息

**Click** [Issues](https://github.com/huaxialucaicaizi/business-plan-skill/issues) → **New issue** → Select "反馈输出问题 / Report Output Problem" template

### 3. 提交 Pull Request / Submit a Pull Request

欢迎直接提交改进！在提交 PR 前：

We welcome direct improvements! Before submitting a PR:

**准备工作 / Preparation:**

1. Fork 本仓库到你的 GitHub 账号
2. Clone 你的 fork 到本地
3. 创建新分支：`git checkout -b feature/your-feature-name`

**开发与测试 / Development and Testing:**

1. 进行修改（SKILL.md、references、examples 等）
2. 如果添加或修改示例，确保标注为虚构且不包含真实数据
3. 更新 CHANGELOG.md 的 `[Unreleased]` 部分
4. 测试修改（至少手动验证 YAML 和 frontmatter 可正常解析）

**提交 PR / Submit PR:**

1. Commit 并 push 到你的 fork：`git push origin feature/your-feature-name`
2. 在 GitHub 上创建 Pull Request 到 `main` 分支
3. 描述修改内容、动机和测试方法
4. 等待 CI 检查通过和 Review

**代码规范 / Code Standards:**

- SKILL.md frontmatter 必须包含 `name` 和 `description`
- agents/openai.yaml 必须包含 `interface` 字段及其子字段
- 所有示例必须标注为虚构（中英文）
- 不虚构任何真实数据（姓名、公司、融资、客户等）
- 保持中英文双语一致性

---

## 改进建议 / Improvement Suggestions

以下是一些欢迎贡献的方向：

Here are some areas where contributions are welcome:

- **新增申请场景参考模板** / New application scenario templates
- **改进示例输出质量** / Improve example output quality
- **补充更多行业或领域示例** / Add more industry or domain examples
- **优化提示词和工作流** / Optimize prompts and workflows
- **改进文档可读性** / Improve documentation readability
- **修复错别字或格式问题** / Fix typos or formatting issues

---

## 行为准则 / Code of Conduct

本项目遵循 [Contributor Covenant 2.1](CODE_OF_CONDUCT.md)。参与本项目即表示你同意遵守该行为准则。

This project follows the [Contributor Covenant 2.1](CODE_OF_CONDUCT.md). By participating, you agree to abide by its terms.

---

## 问题与讨论 / Questions and Discussions

- **Bug 报告和功能请求：** 使用 [GitHub Issues](https://github.com/huaxialucaicaizi/business-plan-skill/issues)
- **一般讨论：** 使用 [GitHub Discussions](https://github.com/huaxialucaicaizi/business-plan-skill/discussions)（如果启用）
- **安全问题：** 查看 [SECURITY.md](SECURITY.md)

---

## 许可证 / License

通过贡献代码，你同意你的贡献将在 [MIT License](LICENSE) 下发布。

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).

---

感谢你的贡献！🎉

Thank you for your contributions! 🎉

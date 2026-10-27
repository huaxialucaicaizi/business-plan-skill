# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- CONTRIBUTING.md with guidelines for proposing scenarios, reporting issues, and submitting PRs
- GitHub issue templates: new scenario and output problem reports
- Pull request template with comprehensive checklist
- SECURITY.md with private vulnerability reporting instructions
- CODE_OF_CONDUCT.md (Contributor Covenant 2.1)
- GitHub Actions CI workflow validating SKILL.md frontmatter, agents/openai.yaml, and markdown links
- CI status badge in README
- `references/business-plan-core.md` 财务部分新增：关键假设表（含数据来源类型：实际 / 估算 / 假设 / 待补充）、收入推导公式、盈亏平衡算法说明、财务自检清单（全部为占位符模板）
- `references/business-plan-core.md` Financial Plan: added a Key Assumptions table (with source type: Actual / Estimate / Assumption / 待补充), revenue derivation formulas, break-even calculation, and a Financial Self-Check list (placeholder-only templates)
- `references/business-plan-core.md` 新增"想法验证"章节（面向 AI 产品）：验证内容（痛点、付费意愿、AI 输出质量）、用户访谈方法、小额 Meta 广告测试、结果呈现模板（`[填写]` 占位符，不含基准数字）与验证自检清单，并链接 [ai-mvp-validation](https://github.com/huaxialucaicaizi/ai-mvp-validation)
- `references/business-plan-core.md`: added a "Validation Evidence" section for AI products: what to validate (pain point, willingness to pay, AI output quality), user interviews, small Meta ad tests, placeholder-only results tables (no benchmark numbers), and a validation self-check, linking to [ai-mvp-validation](https://github.com/huaxialucaicaizi/ai-mvp-validation)
- 新增虚构示例 `examples/financial-assumptions-and-validation.md`：以「智汇学伴」演示填好的关键假设表、逐月收入推导、盈亏平衡、资金用途、财务自检清单，以及 MVP 阶段的想法验证证据（所有数字均标注为示例假设或虚构示例结果）；`examples/README.md`、`examples/bp-outline.md` 和 README 增加指向该文件的链接
- Added fictional example `examples/financial-assumptions-and-validation.md` demonstrating a filled-in Key Assumptions table, month-by-month revenue derivation, break-even, use of funds, Financial Self-Check, and MVP-stage Validation Evidence for StudyPal AI (all numbers labeled as example assumptions or fictional results); linked from `examples/README.md`, `examples/bp-outline.md`, and README
- `SKILL.md` 新增"交付前总自检"清单：汇总数字标注、不编造事实、列出 `待补充` 字段、受众与字数、财务自检、AI 产品想法验证、公开版去除隐私等规则，并指向对应参考章节
- `SKILL.md`: added a "Final Delivery Check" checklist consolidating existing rules (number labeling, no invented facts, listing `待补充` fields, audience and character limits, Financial Self-Check, Validation Evidence for AI products, removing private facts from public outputs), pointing to the relevant reference sections
- `SKILL.md` 新增"上下游衔接"说明：本 skill 是一人公司工具包第 2 步，链接第 1 步 ai-mvp-validation、第 3 步 opc-policy-navigator、第 4 步 ai-pitch-coach 及合集 ai-startup-skills（均为可选配套 skill，非依赖）
- `SKILL.md`: added a "Related Toolkit Steps" note: this skill is step 2 of the One-Person Company Toolkit, linking step 1 ai-mvp-validation, step 3 opc-policy-navigator, step 4 ai-pitch-coach, and the ai-startup-skills bundle (optional companion skills, not dependencies)

### Changed
- 修正安装说明：恢复 Codex 官方的 `$skill-installer` 命令（根据官方文档核实）
- 更新 OpenAI Codex 规范链接：从失效的 `/codex/skills` 更新为新地址 `https://learn.chatgpt.com/docs/build-skills`
- 添加"验证安装"部分，提供针对 Codex 的测试方法
- 补充说明：其他支持 Agent Skills 的工具也可使用此 skill
- Fixed installation instructions: restored official Codex `$skill-installer` command (verified from official documentation)
- Updated OpenAI Codex specification link: from deprecated `/codex/skills` to new URL `https://learn.chatgpt.com/docs/build-skills`
- Added "Verify Installation" section with Codex-specific test methods
- Added note: other Agent Skills-compatible tools can also use this skill
- Added codex-ppt installation instructions and attribution to [@ningzimu](https://github.com/ningzimu)
- Replaced codex-ppt TODO sections in README.md with actual source and installation guide
- Added codex-ppt attribution note in SKILL.md
- `SKILL.md` 的 What To Read 新增提示：做财务预测、融资计划时先使用关键假设表和财务自检清单
- `SKILL.md` What To Read: added a pointer to use the Key Assumptions table and Financial Self-Check for financial projections and funding plans
- 合并 CHANGELOG [Unreleased] 中重复的 "Changed" 小节
- Merged duplicate "Changed" sections under [Unreleased] in CHANGELOG
- `SKILL.md` Default Workflow 新增一句：AI 产品需加入想法验证章节，缺少证据时如实说明
- `SKILL.md` Default Workflow: added a pointer to include the Validation Evidence section for AI products, stating honestly when evidence is missing
- `references/business-plan-core.md` 后续章节编号顺延（竞品分析 → 7，商业模式 → 8，路线图 → 9，财务计划 → 10）
- `references/business-plan-core.md`: renumbered later sections (Competitor Analysis → 7, Business Model → 8, Roadmap → 9, Financial Plan → 10)

## [1.0.0] - 2026-10-19

### Added
- Initial public release of business-plan-skill
- MIT License for open source distribution
- Comprehensive SKILL.md with business plan workflow instructions
- Three reference files for reusable content:
  - `business-plan-core.md`: positioning, market analysis, financial planning
  - `founder-and-advantage.md`: team profiles and competitive advantages
  - `application-copy.md`: incubator and official form templates
- Bilingual support (English and Chinese) for descriptions and trigger words
- Integration guidance for codex-ppt visual deck generation
- Privacy-first rules: no fabricated data, placeholder-based workflow
- OpenAI Codex skill metadata (agents/openai.yaml)
- Example outputs for fictional project demonstrations

### Documentation
- README with quick start, installation, and usage examples
- Clear separation between instruction-based workflow and placeholder data
- Contributing guidelines and customization instructions

[1.0.0]: https://github.com/huaxialucaicaizi/business-plan-skill/releases/tag/v1.0.0

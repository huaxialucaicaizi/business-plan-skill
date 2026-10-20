# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed
- 修复安装说明：移除不正确的 `$skill-installer` 命令格式，改为通过 Cursor Agent 安装的说明
- 添加"验证安装"部分，提供简单的测试方法帮助用户确认 skill 是否正常加载
- 移除失效的 OpenAI Codex 规范链接（该链接返回 308 重定向），改为描述性说明
- 明确说明需要重启 Cursor IDE 才能使新 skill 生效
- Added installation verification section with quick test method
- Fixed installation instructions: removed incorrect `$skill-installer` command format, replaced with Cursor Agent installation guide
- Removed broken OpenAI Codex specification link (returns 308 redirect), replaced with descriptive text
- Clarified that Cursor IDE restart is required for new skills to take effect

### Added
- CONTRIBUTING.md with guidelines for proposing scenarios, reporting issues, and submitting PRs
- GitHub issue templates: new scenario and output problem reports
- Pull request template with comprehensive checklist
- SECURITY.md with private vulnerability reporting instructions
- CODE_OF_CONDUCT.md (Contributor Covenant 2.1)
- GitHub Actions CI workflow validating SKILL.md frontmatter, agents/openai.yaml, and markdown links
- CI status badge in README

### Changed
- Added codex-ppt installation instructions and attribution to [@ningzimu](https://github.com/ningzimu)
- Replaced codex-ppt TODO sections in README.md with actual source and installation guide
- Added codex-ppt attribution note in SKILL.md

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

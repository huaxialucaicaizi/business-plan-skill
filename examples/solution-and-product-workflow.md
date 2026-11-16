# 解决方案与产品流程填写示例 - 智汇学伴（虚构示例） / Solution And Product Workflow — StudyPal AI (Fictional Example)

**虚构说明：本文档全部内容均为虚构，仅用于演示如何填写 [`references/business-plan-core.md`](../references/business-plan-core.md) 第 4 节「Solution And Product Workflow」模板。不含任何真实项目、真实个人、真实雇主、真实统计、真实报告或来源网址；也不含第三方产品促销。**

**Fiction notice: Everything in this document is entirely fictional and for demonstration only. It shows how to fill section 4 of [`references/business-plan-core.md`](../references/business-plan-core.md). It contains no real project, real person, real employer, real statistics, real reports or source URLs, and no third-party product promotion.**

本示例只复用仓库已有示例中的事实与数字：项目背景与痛点见 [`README.md`](./README.md) 与 [`target-customers-and-pain-point.md`](./target-customers-and-pain-point.md)；核心功能与工作流措辞与 [`bp-outline.md`](./bp-outline.md) 第 4 节、[`pitch-deck-outline.md`](./pitch-deck-outline.md) 第 4–5 页对齐；MVP / 验证结果见 [`financial-assumptions-and-validation.md`](./financial-assumptions-and-validation.md)；付费点见 [`business-model.md`](./business-model.md)；阶段时点见 [`roadmap.md`](./roadmap.md)；「已完成引导式对话与知识图谱诊断的 MVP 原型」等口径见 [`team-and-competitive-advantage.md`](./team-and-competitive-advantage.md) / [`competitor-analysis.md`](./competitor-analysis.md)。凡现有示例尚未给出的准确率、留存、规模化效果等，一律写 `待补充` / `待验证`，不另编。

This example reuses only facts and figures already present in the repo examples above. Accuracy rates, retention, and scale effects not already derived stay `待补充` / `待验证`.

**标注约定 / Labels：**

- 「示例假设」 / example assumption：对应来源类型 `Assumption` / 假设（规划口径，不是已发生事实）。
- 「虚构示例结果」 / fictional result：来自验证示例中编造的访谈 / 试用结果，仅供演示。
- `待补充`：现有示例也未给出的数字或来源。
- `待验证`：方向合理，但当前阶段尚无足够证据。
- `MVP 已有`：当前阶段已完成的原型能力（与「MVP 原型已完成、小范围测试中」一致）。
- `计划中`：路线图后续事项，不得写成当前成绩。

---

## 1. 痛点 → 方案对应表 / Pain → Solution Mapping

| 第 3 节痛点 / 工作流断裂点（复用已有示例） | 对应方案 / 模块 | 状态 |
|---|---|---|
| 课后卡题无人可问；缺少即时、耐心、可引导思考的辅导 | 对话式辅导：学生输入问题后，AI 通过提问引导学生思考，不直接给答案 | `MVP 已有`（小范围试用；见验证示例） |
| 题库主要给答案 / 步骤，较少引导学生自己想下一步 | 引导式对话工作流（「教思考而非给答案」） | `MVP 已有`；广告变体 A 同一定位（虚构示例结果） |
| 概念理解停留在表面、难以举一反三；缺少薄弱环节诊断 | 知识图谱分析：诊断薄弱知识点，建议优先学习的前置知识 | `MVP 已有`（原型已含知识图谱诊断；准确率对比 `待验证`） |
| 零散答疑难形成知识体系；需要可重复的学习陪伴 | 学习路径推荐 + 练习推荐；记录掌握情况并调整后续推荐 | 模块写入产品定义与工作流（`MVP 已有` 设计）；规模化后推荐是否更准 `待验证` |
| 一对一时段 / 成本约束；家长辅导不稳定 | 免费入口（每天 3 次免费提问）+ 计划中的个人月度会员（¥99/月）提供可随时使用的辅导入口 | 免费入口为获客 / 教育（非收入）；付费自 M4 起为 `计划中`（示例假设） |

---

## 2. 用户使用流程 / User Workflow（分步）

对应参考模板的推荐流程，写成「用户一步步怎么用」，而不是功能堆砌。 / Matching the recommended reference flow as a walkthrough, not a feature dump.

| 步骤 / Step | 用户侧输入或动作 / Input | 系统处理 / Processing | 输出 / 结果 / Output | 状态 |
|---|---|---|---|---|
| 1. Input / 输入 | 学生输入问题，或选择知识点；免费档每天最多 3 次提问（示例假设） | 接收题目 / 知识点上下文 | 进入辅导会话 | `MVP 已有` |
| 2. Analysis / 分析 | （承接上一步） | AI 分析涉及的知识点与前置依赖（知识图谱） | 薄弱点 / 前置知识提示 | `MVP 已有`；诊断准确率对比 `待验证` |
| 3. Generation / 生成引导 | 学生在对话中作答或继续追问 | 生成引导式提问与讲解路径，不直接给最终答案 | 一步步思考提示 | `MVP 已有`；22 / 30 次被评为「能看懂」（虚构示例结果） |
| 4. Execution / 练习与路径 | 学生按提示继续；需要巩固时进入练习 / 路径 | 诊断理解程度，推荐相关练习与学习路径 | 练习题 / 个性化路径建议 | 工作流已写明（`MVP 已有` 设计）；效果 `待验证` |
| 5. Tracking / 记录 | 学生完成练习或结束会话 | 记录掌握情况 | 掌握情况记录，供后续调整 | 产品设计会记录（见团队示例）；规模化数据效果 `待验证` |
| 6. Iteration / 迭代 | （下一题或下一阶段学习） | 根据掌握情况调整后续推荐；教研顾问抽查 AI 输出 | 调整后的推荐；错误项进入修复清单 | 抽查已发现 2 次知识点错误待修复（虚构示例结果）；复测为 `计划中` |

**与付费点 / 路线图对齐 / Alignment with sections 8–9：**

- **免费入口：** 每天 3 次免费提问 = 获客 / 用户教育，不是收入（与商业模式示例一致）。
- **付费解锁：** 个人月度会员 ¥99/月为当前可推导的核心付费点；M1–M3 不收费，M4 起计划收费（与财务 / 路线图示例一致）。年度会员、学校 / 团体、B 端定价均为 `待补充`，不写入当前方案的「已上线付费能力」。
- **质量修复：** 验证阶段记录的 2 次知识点错误，在路线图 6–12 个月「计划修复验证阶段发现的输出问题」中处理，不写成已修复完毕。

---

## 3. 产品模块表 / Product Module Table

| Module / 模块 | User Problem / 用户问题 | Core Function / 核心功能 | Output / 输出 | 状态 |
|---|---|---|---|---|
| 对话式辅导 | 课后卡题无人可问；题库只给答案 | 提问引导学生自主思考，不直接给答案 | 引导式对话结果；「能看懂」评价可核验 | `MVP 已有` |
| 知识图谱分析 | 不知薄弱环节与前置知识 | 诊断知识点薄弱处，建议优先补的前置知识 | 薄弱点 / 前置依赖提示 | `MVP 已有`；准确率对比 `待验证` |
| 学习路径推荐 | 缺少个性化计划、难形成体系 | 按当前水平与目标给出学习路径建议 | 学习路径建议 | `MVP 已有`（产品定义）；规模化效果 `待验证` |
| 练习推荐 | 理解后缺少匹配练习巩固 | 推荐匹配能力水平的练习题 | 练习题推荐 | `MVP 已有`（产品定义）；规模化效果 `待验证` |
| 付费会员（个人月度） | 免费次数用尽后需持续辅导 | ¥99/月个人订阅（示例假设） | 付费使用权 | `计划中`（M4 起；Y1 唯一计入收入） |
| 学校 / 团体 / B 端能力 | 机构侧规模化辅导 | `待补充` | `待补充` | `计划中`；定价与假设 `待补充` |

---

## 4. 未核实表述改写对照 / Before/After: Softening Unsupported Claims

左列为反面教材，右列才是本示例采用的口径。 / Left column is what not to write; right column is the wording used here.

| 问题类型 / Problem | 改写前（不要这样写） / Before (do not use) | 改写后（本示例口径） / After (used here) | 依据 / Why |
|---|---|---|---|
| 功能堆砌、不对应痛点 | 我们有十大数据看板、社区、商城和直播课 | 只写对应课后卡题 / 不教思考 / 薄弱诊断的引导式对话、知识图谱、路径与练习 | 方案须逐条对应第 3 节痛点 |
| 把计划写成已有 | 已上线学校团体版与 B 端交付 | 学校 / 团体与 B 端为 `计划中`，定价 `待补充`；当前 MVP 为家庭课后辅导原型 | 与商业模式 / 路线图一致 |
| 未核实技术口号 | 行业领先的大模型，准确率 99% | 已完成引导式对话与知识图谱诊断的 MVP 原型；22 / 30 次「能看懂」（虚构示例结果）；准确率对比与规模化效果 `待验证` | 只写可演示 / 可核验结果 |
| 编造用户量 / 留存 | 已有百万用户，月留存 80% | 不写用户量或留存；当前为小范围测试，付费转化 `待验证` | 禁止新编数据 |
| 忽略已知缺陷 | AI 从不讲错知识点 | 教研抽查发现 2 次知识点错误，已记录待修复；复测为 `计划中` | 可核验的负面结果也要写 |
| 付费点错位 | 免费无限用，同时宣称订阅已全面变现 | 每天 3 次免费提问为非收入入口；个人月度会员自 M4 起为 `计划中` | 与第 8–9 节一致 |

---

## 5. Solution And Product Workflow Self-Check / 解决方案与产品流程自检清单（本虚构示例已勾选）

真实项目必须根据自身证据重新运行清单，不可直接沿用本示例的勾选结果。 / Real projects must re-run this checklist using their own evidence.

- [x] Every solution point maps to a named pain / workflow break in section 3. / 对话、知识图谱、路径 / 练习、免费入口均对应「无人可问 / 只给答案 / 薄弱诊断 / 难成体系 / 时段成本」等已有痛点。
- [x] The product is described as a user workflow (input → processing → output / result), not only a feature list. / 第 2 节按输入 → 分析 → 引导 → 练习 / 路径 → 记录 → 迭代书写。
- [x] MVP / already-built items are clearly separated from planned items. / 对话与知识图谱等标 `MVP 已有`；付费会员、错误复测、学校 / B 端标 `计划中`。
- [x] AI / technical claims are demoable or checkable, or marked `待验证` / `待补充`; no unverified 「行业领先」 / 「准确率 99%」-style claims. / 仅复用 22 / 30「能看懂」与 2 次错误待修复；准确率 / 规模化效果标 `待验证`。
- [x] Solution capabilities and unlock timing match Business Model pay points (section 8) and Roadmap (section 9). / 免费 3 次 / ¥99 月费 / M4 收费起点 / 未定价学校与 B 端口径与商业模式、路线图示例一致。

---

**再次说明：本文档全部内容均为虚构演示。数字与试用结果仅复用仓库已有示例假设 / 虚构结果，或保留为 `待补充` / `待验证`。不代表任何真实项目或个人。**

**Again: this document is entirely fictional. Numbers and trial results only reuse existing example assumptions / fictional results in this repo, or stay `待补充` / `待验证`. It represents no real project or person.**

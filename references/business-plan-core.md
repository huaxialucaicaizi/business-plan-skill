# Business Plan Core Reference

This reference provides reusable business-plan structures and placeholders. Replace bracketed text with the user's real project information.

## 1. Positioning

One-sentence formula:

> `[Project Name]` is a `[product/service category]` for `[target customer]`, helping them solve `[specific pain point]` through `[core technology/workflow]` and achieve `[business outcome]`.

Chinese formula:

> `[项目名称]` 是面向 `[目标客户]` 的 `[产品/服务类型]`，通过 `[核心技术/工作流]` 解决 `[具体痛点]`，帮助客户实现 `[业务结果]`。

Positioning should answer:
- Who is the customer?
- What painful problem do they have?
- Why is the current solution insufficient?
- What does the product do differently?
- What measurable outcome does it produce?

## 2. Target Customers

Segment target customers by value and urgency:

| Segment | Description | Pain | Budget / Willingness To Pay | Priority |
|---|---|---|---|---|
| Primary customer | `[high-value customer segment]` | `[urgent pain]` | `[budget level]` | High |
| Early adopter | `[easier-to-reach segment]` | `[validation pain]` | `[budget level]` | Medium |
| Strategic partner | `[platform / channel / ecosystem]` | `[ecosystem need]` | `[project or partnership model]` | Medium |

Avoid describing everyone as the customer. Pick one primary wedge.

## 3. Pain Point

A strong pain-point section should include:
- Current workflow
- Where the workflow breaks
- Cost of the problem
- Why existing tools/services do not solve it
- Why now

Pain statement template:

> `[Target customer]` already has `[existing resources/tools]`, but still struggles with `[specific workflow problem]`. The result is `[cost: time, money, conversion, risk, missed growth]`. Existing solutions such as `[alternatives]` mainly solve `[partial problem]`, but do not address `[missing workflow/result]`.

## 4. Solution And Product Workflow

Recommended flow:

1. Input: `[customer goal / data / business context]`
2. Analysis: `[market / user / competitor / operation insight]`
3. Generation: `[strategy / content / workflow / leads / plan]`
4. Execution: `[automation / team task / agent action / service delivery]`
5. Tracking: `[metrics / dashboard / feedback]`
6. Iteration: `[optimization / next action / report]`

Product module table:

| Module | User Problem | Core Function | Output |
|---|---|---|---|
| `[Module 1]` | `[problem]` | `[function]` | `[artifact/result]` |
| `[Module 2]` | `[problem]` | `[function]` | `[artifact/result]` |
| `[Module 3]` | `[problem]` | `[function]` | `[artifact/result]` |

## 5. Market Analysis

Market section structure:

1. Macro trend: `[industry/technology/policy/customer behavior shift]`
2. Target market: `[specific segment, geography, customer type]`
3. Market size: `[TAM/SAM/SOM or proxy indicators]`
4. Urgency: `[why customers need this now]`
5. Entry market: `[why this geography/segment first]`

Use source-backed data for market size when possible. If using assumptions, label them clearly.

## 6. Validation Evidence / 想法验证

本节用于在商业计划书中展示"想法已被验证"的证据，适用于 AI 产品。方法：用户访谈 + 小额 Meta（Facebook / Instagram）广告测试。完整方法见一人公司工具包第 1 步 [ai-mvp-validation](https://github.com/huaxialucaicaizi/ai-mvp-validation)。

### What To Validate / 验证什么

| 验证项 | 要回答的问题 | 主要证据来源 |
|---|---|---|
| 痛点 | `[目标客户]` 是否真的有这个问题、频率多高、现在怎么解决 | 用户访谈 |
| 付费意愿 | 是否愿意为解决方案付费、愿意付多少、谁来付 | 访谈 + 广告落地页的定价 / 预约行为 |
| AI 输出质量 | AI 生成的结果是否"够用"：用户能否直接使用，还是需要大量修改 | 让受访者试用原型或样例输出后反馈 |

### User Interviews / 用户访谈

- **找谁：** 符合主要客户画像、最近真实遇到过该问题的人；优先从广告报名者中邀约，避免只访谈亲友。
- **访谈多少：** 经验法则（非统计标准）：每个客户细分先访谈约 5–10 人，若新访谈已不再出现新信息再停止；结论不一致时继续增加。
- **关键问题：**
  - "上一次遇到 `[问题]` 是什么时候？当时具体怎么处理的？"
  - "这个问题让你花了多少时间 / 钱？"
  - "你试过哪些工具或办法？哪里不满意？"
  - "看完这份 AI 生成的 `[样例输出]`，哪些能直接用，哪些需要改？"
  - "如果有工具能解决，你现在为类似工具付多少钱？谁批准这笔支出？"
- **避免诱导性提问：** 问过去的真实行为，不问假设性意愿。不要问"你会用这个产品吗？""你觉得这个功能好不好？"；也不要在访谈开头先推销方案。

### Small Meta Ad Test / 小额 Meta 广告测试

1. **落地页 / 等候名单：** 做一个单页，写清楚一句话价值主张、目标用户、（可选）参考价格，以及"加入等候名单 / 预约访谈"按钮。
2. **几组广告变体：** 准备 2–4 组广告，每组测试一个不同的价值主张（如"省时间" vs "提升质量" vs "降低成本"），其余变量（受众、预算、素材风格）尽量保持一致。
3. **测试前先定标准：** 在投放前由创始人自行设定预算上限、测试周期和每个指标的通过 / 不通过阈值并记录下来。本模板不提供行业基准数字。
4. **衡量指标：**
   - 点击率（CTR）= 链接点击数 ÷ 展示次数
   - 单个注册成本 = 广告花费 ÷ 等候名单注册数
   - 注册到访谈转化率 = 完成访谈人数 ÷ 注册人数
5. 遵守 Meta 广告政策，落地页如收集个人信息需说明用途。

### Presenting Results In The Plan / 在商业计划书中呈现

验证摘要表：

| 验证项 | 方法 | 样本量 | 结果 | 测试前设定的阈值 | 结论（通过 / 不通过 / 待定） |
|---|---|---|---|---|---|
| 痛点 | 用户访谈 | `[填写]` 人 | `[填写]` 人确认高频痛点 | `[填写]` | `[填写]` |
| 付费意愿 | 访谈 + 落地页 | `[填写]` | `[填写]` | `[填写]` | `[填写]` |
| AI 输出质量 | 原型 / 样例试用 | `[填写]` 人 | `[填写]` | `[填写]` | `[填写]` |

广告测试结果表：

| 广告变体（价值主张） | 花费 | 展示 | 点击 | CTR | 注册数 | 单个注册成本 | 完成访谈 | 注册到访谈转化率 |
|---|---|---|---|---|---|---|---|---|
| `[变体 A]` | `[填写]` | `[填写]` | `[填写]` | `[填写]` | `[填写]` | `[填写]` | `[填写]` | `[填写]` |
| `[变体 B]` | `[填写]` | `[填写]` | `[填写]` | `[填写]` | `[填写]` | `[填写]` | `[填写]` | `[填写]` |

在表格之后用 2–3 句话写出：哪个价值主张表现最好、用户原话中的关键证据、验证后对产品或定位做了哪些调整。如需引用外部基准数字，必须注明可核实的来源；否则只与创始人自设的阈值比较。

### Validation Self-Check / 验证自检清单

- [ ] Every result comes from a real interview or ad test, with sample size stated. / 每个结果都来自真实的访谈或广告测试，并注明样本量。
- [ ] Pass/fail thresholds were set before the test, not after. / 通过 / 不通过阈值是测试前设定的，而不是事后调整的。
- [ ] Interview questions asked about past behavior, not leading or hypothetical. / 访谈问的是过去的真实行为，没有诱导性或假设性问题。
- [ ] AI output quality was judged by target users, not only by the team. / AI 输出质量由目标用户评价，而不只是团队自评。
- [ ] No external benchmark is quoted without a verifiable source. / 未注明可核实来源的外部基准数字一律不引用。
- [ ] Validation results are consistent with the Key Assumptions table (e.g. CAC, price). / 验证结果与关键假设表（如获客成本、价格）一致。

**If evidence is missing / 缺少证据时：** 如实写明"尚未完成验证"，列出 `待补充` 项和计划的验证步骤与时间节点，不要编造访谈数量、注册数、付费用户或其他 traction。

## 7. Competitor Analysis

Competitor framing:

| Type | Representative Products | Strength | Gap | Opportunity |
|---|---|---|---|---|
| Incumbent tools | `[example]` | `[strength]` | `[gap]` | `[project opportunity]` |
| Point solution | `[example]` | `[strength]` | `[gap]` | `[project opportunity]` |
| Services / consulting | `[example]` | `[strength]` | `[gap]` | `[project opportunity]` |
| Internal workaround | `[spreadsheet/manual process/etc.]` | `[strength]` | `[gap]` | `[project opportunity]` |

Differentiation claim:

> Unlike `[alternative]`, `[Project Name]` focuses on `[unique workflow/result]`, combining `[capability 1]`, `[capability 2]`, and `[capability 3]` to deliver `[measurable result]`.

## 8. Business Model

Common models:
- SaaS subscription
- Usage-based pricing
- Course/training revenue
- Consulting or implementation service
- Enterprise package
- Marketplace commission
- Data/report subscription
- Channel or ecosystem partnership

Business model table:

| Revenue Type | Product Form | Pricing Assumption | Strategic Role |
|---|---|---|---|
| Entry product | `[course/free trial/basic plan]` | `[price]` | User education / lead generation |
| Core product | `[SaaS/subscription]` | `[price]` | Scalable recurring revenue |
| Premium service | `[consulting/implementation]` | `[price]` | High-ticket validation |
| Enterprise plan | `[custom package]` | `[price]` | Higher ACV and case studies |

## 9. Roadmap

18-month roadmap template:

| Stage | Key Actions | Milestones |
|---|---|---|
| 0-3 months | MVP / prototype / first users | `[prototype, user interviews, early pilots]` |
| 3-6 months | Commercial validation | `[paid customers, case studies, first revenue]` |
| 6-12 months | Productization and scale | `[SaaS launch, repeatable delivery, retention]` |
| 12-18 months | Regional or vertical expansion | `[new market, financing readiness, partnerships]` |

## 10. Financial Plan

Financial section should include:
- Revenue streams
- Key assumptions
- Three-year revenue projection
- Cost structure
- Gross margin assumption
- Break-even point
- Funding amount and use of funds

Build the financial plan in this order: key assumptions → revenue derivation → three-year projection → break-even → use of funds → self-check. Every number in the projection should trace back to a row in the Key Assumptions table.

财务部分建议按此顺序完成：关键假设 → 收入推导 → 三年预测 → 盈亏平衡 → 资金用途 → 自检。预测中的每个数字都应能追溯到关键假设表中的某一行。

### Key Assumptions / 关键假设表

Source type / 数据来源类型:
- `Actual` / 实际: verified data the user provided, such as signed contracts, invoices, or current users.
- `Estimate` / 估算: derived from real data or cited sources, with the method stated.
- `Assumption` / 假设: a planning hypothesis with no direct evidence yet; state the reasoning.
- `待补充`: unknown; ask the user instead of inventing a value.

| Assumption / 假设项 | Value / 数值 | Source Type / 来源类型 | Basis / 依据说明 |
|---|---|---|---|
| Paying customers / 付费客户数 | `[number per period]` | `[Actual / Estimate / Assumption / 待补充]` | `[pipeline, pilots, signed LOIs, channel plan]` |
| New customers per period / 新增客户数 | `[number per month/quarter]` | `[Actual / Estimate / Assumption / 待补充]` | `[sales capacity, channel conversion]` |
| Price or ARPU / 客单价或 ARPU | `[amount per customer per period]` | `[Actual / Estimate / Assumption / 待补充]` | `[pricing page, quotes, comparable products]` |
| Billing period / 计费周期 | `[monthly / annual / one-off]` | `[Actual / Estimate / Assumption / 待补充]` | `[contract terms]` |
| Retention or renewal rate / 续费或留存率 | `[x]% per [month/year]` | `[Actual / Estimate / Assumption / 待补充]` | `[pilot data, industry reference with source]` |
| Customer acquisition cost (CAC) / 获客成本 | `[amount per customer]` | `[Actual / Estimate / Assumption / 待补充]` | `[ad spend, sales cost, channel fees]` |
| Gross margin / 毛利率 | `[x]%` | `[Actual / Estimate / Assumption / 待补充]` | `[delivery cost, infrastructure, third-party fees]` |
| Variable cost per customer / 单客户变动成本 | `[amount per customer per period]` | `[Actual / Estimate / Assumption / 待补充]` | `[compute, service hours, materials]` |
| Monthly fixed costs / 月度固定成本 | `[amount per month]` | `[Actual / Estimate / Assumption / 待补充]` | `[team, office, tools, compliance]` |
| Tax and currency basis / 税务与币种口径 | `[tax-inclusive / tax-exclusive, currency]` | `[Actual / 待补充]` | `[invoicing practice]` |

Add or remove rows to match the business model. If a value is unknown, keep `待补充` and list it in the output as a question for the user.

### Revenue Derivation / 收入推导

Basic formula (per revenue stream):

```text
Revenue = Paying customers × Price (ARPU) × Number of billing periods
收入 = 付费客户数 × 客单价 × 计费周期数
```

Subscription revenue, calculated month by month:

```text
Customers(month n) = Customers(month n-1) × Monthly retention rate + New customers(month n)
MRR(month n)       = Customers(month n) × Monthly ARPU
Annual revenue     = Sum of MRR for the 12 months of that year
```

If there are several revenue types (see the Business Model table), derive each one separately and add them up. Use one-off pricing for courses, consulting, or implementation, and the subscription formula for recurring revenue.

### Break-Even / 盈亏平衡

```text
Contribution margin per customer = ARPU − Variable cost per customer
Break-even customers             = Monthly fixed costs ÷ Monthly contribution margin per customer
Break-even revenue               = Monthly fixed costs ÷ Gross margin %
Break-even month                 = First month where monthly gross profit ≥ monthly fixed costs
```

State which assumptions the break-even point depends on most, and how it moves if those assumptions are weaker than planned.

### Three-Year Projection / 三年收入预测

Template:

| Year | Revenue Target | Main Revenue Source | Operating Goal |
|---|---|---|---|
| Y1 | `[amount]` | `[source]` | `[goal]` |
| Y2 | `[amount]` | `[source]` | `[goal]` |
| Y3 | `[amount]` | `[source]` | `[goal]` |

### Use Of Funds / 资金用途

Funding-use template:

| Use Of Funds | Percentage | Purpose |
|---|---:|---|
| Product R&D | `[x]%` | `[purpose]` |
| Market Growth | `[x]%` | `[purpose]` |
| Operations / Delivery | `[x]%` | `[purpose]` |
| Pilots / Partnerships | `[x]%` | `[purpose]` |
| Reserve / Compliance | `[x]%` | `[purpose]` |

### Financial Self-Check / 财务自检清单

Run this checklist before delivering any financial projection or funding request:

- [ ] Use-of-funds percentages add up to 100%. / 资金用途百分比合计为 100%。
- [ ] Funding amount × each percentage matches the amount described for that use. / 融资金额 × 各项百分比与对应用途描述的金额一致。
- [ ] Y1 revenue and customer numbers are consistent with the 0-12 month Roadmap milestones. / Y1 收入与客户数与 Roadmap 中 0-12 个月里程碑一致。
- [ ] Every Y1-Y3 revenue figure can be recomputed from the Key Assumptions table. / Y1-Y3 每个收入数字都能用关键假设表重新算出。
- [ ] Every number is labeled `Actual`, `Estimate`, `Assumption`, or `待补充`. / 每个数字都标注了来源类型。
- [ ] Unknown numbers are written as `待补充`, not invented. / 未知数字写 `待补充`，没有编造。
- [ ] Revenue and costs use the same basis: tax-inclusive or tax-exclusive, monthly or annual, same currency. / 收入与成本口径一致（含税/不含税、月/年、币种）。
- [ ] Gross margin and break-even use the same cost figures as the cost structure. / 毛利率与盈亏平衡使用的成本与成本结构一致。
- [ ] The same numbers appear identically in the executive summary, pitch deck, and application forms. / 执行摘要、路演 PPT、申请表中的同一数字保持一致。
- [ ] Market-size or industry figures cite a source, or are labeled as assumptions. / 市场规模和行业数据注明来源，否则标注为假设。


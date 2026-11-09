# 市场规模测算填写示例 - 智汇学伴（虚构示例） / Market Sizing — StudyPal AI (Fictional Example)

**虚构说明：本文档所有内容均为虚构示例，仅用于演示如何填写 `references/business-plan-core.md` 第 5 节「Market Sizing / 市场规模测算」模板。所有项目信息与数字均为假设，不代表任何真实项目、真实市场或真实人口。文中不引用任何真实市场规模统计、真实人口数字、真实报告、真实机构或来源网址。**

**Fiction notice: Everything in this document is FICTIONAL and for demonstration only — it shows how to fill the `Market Sizing / 市场规模测算` subsection in `references/business-plan-core.md` section 5. It does not represent any real project, market, or population. There are no real market statistics, real population figures, real reports, real institutions, or source URLs.**

本示例按 [`references/business-plan-core.md`](../references/business-plan-core.md) 中「Market Sizing / 市场规模测算」的结构与措辞填写，不增加该小节没有的章节。项目背景见 [`README.md`](./README.md)；付费客户、客单价与 Y1 收入口径见 [`financial-assumptions-and-validation.md`](./financial-assumptions-and-validation.md)，SOM 与该文件对齐，不另编一套财务数字。

This example fills in the Market Sizing subsection of [`references/business-plan-core.md`](../references/business-plan-core.md) using that subsection’s structure and wording only. Project background: [`README.md`](./README.md). Paying-customer, price/ARPU, and Y1 revenue figures are reused from [`financial-assumptions-and-validation.md`](./financial-assumptions-and-validation.md); SOM is aligned to that file.

**数字标注约定 / Number labels：**

- 「示例假设」 / example assumption：为演示表格算法而设定的圆整规划假设，对应来源类型 `Assumption` / 假设。不是真实市场统计，也不是已发生事实。
- `待补充`：真实创始人必须用可核对来源替换的格子；本示例也不编造真实人口、行业总额或具名报告。需要查阅时，只写应查找的公开资料类型，不写报告名、机构名或网址。

---

## Market Sizing / 市场规模测算

Explain TAM / SAM / SOM in plain words before filling numbers:

- **TAM** (Total Addressable Market / 总可触达市场): if every customer who could theoretically use this category bought it, how large is that demand? / 该品类理论上全部潜在客户都购买时的需求规模。
  - 本示例口径 / This example’s filter: 面向初高中学生家庭的 AI 学习陪伴 / 课后辅导订阅，不限城市层级。/ Household subscriptions for an AI study-companion / after-school tutoring category, any city tier.
- **SAM** (Serviceable Addressable Market / 可服务市场): the part of TAM you can serve with the current product, customer segment, and geography. / TAM 中当前产品、客户细分与地理范围内实际能服务的部分。
  - 本示例口径 / This example’s filter: 当前产品为中文、初高中课后场景；地理上优先一二线城市、由家长付费的家庭订阅。学校团体订阅尚未定价，不计入 SAM。/ Chinese-language, middle- and high-school after-school use; first- and second-tier city households paying for a family plan. School group subscriptions have no price yet, so they are out of SAM.
- **SOM** (Serviceable Obtainable Market / 可获得市场): the share of SAM you can realistically win in 1–3 years. / 未来 1–3 年在 SAM 中可现实拿到的份额。
  - 本示例口径 / This example’s filter: 先填 **Y1 可现实拿到的份额**，与三年收入预测的 Y1 一致。Y2、Y3 在财务示例中为 `待补充`，因此 1–3 年 SOM 不能完整填写，缺口按模板保留为 `待补充` 并说明原因。/ Fill **Y1 obtainable** so it matches Y1 in the Three-Year Projection. Y2 and Y3 are `待补充` in the financial example, so a 1–3 year SOM cannot be completed; the gap is left as `待补充` with an explanation, as the template requires.

**Bottom-up (preferred) / 自下而上（优先）:** start from reachable customers, then narrow TAM → SAM → SOM. Replace `[填写]` / `[number]` / `待补充` only; do not invent market numbers or sources.

对应模板公式 / Matching the reference formula:

```text
TAM ≈ [目标客户总数] × [客单价或 ARPU] × [年购买频次]
SAM ≈ TAM after [细分 / 地理 / 可服务范围] filters
SOM ≈ SAM × [1–3 年内可现实拿到的份额]
```

代入本示例（全部为示例假设；客单价与频次复用财务示例，不另设价格）/ Filled in for this example (all example assumptions; price and frequency reused from the financial example):

```text
TAM ≈ 1,000,000 × ¥99 × 12 = ¥1,188,000,000（示例假设 / example assumption）
SAM ≈ 200,000 × ¥99 × 12 = ¥237,600,000（示例假设 / example assumption）
     （在 TAM 上叠加「一二线城市 + 当前中文/初高中课后可服务范围」后的示例假设）
SOM ≈ Y1 收入 ¥2,271,456
     （与三年预测 Y1 及关键假设表一致，不是另拍的市场份额；
       隐含份额 = 2,271,456 ÷ 237,600,000 = 0.00956 = 0.956%；
       Y2–Y3 待补充，故不写 1–3 年合计 SOM）
```

计算核对 / Arithmetic check:

- 年化 ARPU = ¥99 × 12 = **¥1,188 / 客户 / 年**（示例假设）
- TAM = 1,000,000 × ¥1,188 = **¥1,188,000,000**（示例假设）
- SAM = 200,000 × ¥1,188 = **¥237,600,000**（示例假设）
- SAM 客户数 ÷ TAM 客户数 = 200,000 ÷ 1,000,000 = **20%**（由上面两个示例假设推出，不是外部渗透率）
- SOM 客户数（Y1 平均在册）= 22,944 客户·月 ÷ 12 = **1,912**（示例假设，来自财务推导）
- SOM 规模 = 1,912 × ¥99 × 12 = 22,944 × ¥99 = **¥2,271,456**（与财务示例 Y1 收入一致）
- SOM ÷ SAM = 2,271,456 ÷ 237,600,000 = **0.00956 = 0.956%**（由 SOM 与 SAM 推出，不是事先设定的整数份额）

| Layer | Filter / 口径 | Customers / 客户数 | Price or ARPU / 客单价 | Frequency / 频次 | Size / 规模 | Source Type / 来源类型 | Source / 来源或链接 |
|---|---|---|---|---|---|---|---|
| TAM | 全品类 / 全地理：面向初高中学生家庭的 AI 学习陪伴 / 课后辅导订阅，不限城市层级 / Category-wide household subscriptions, any city tier | 1,000,000（示例假设 / example assumption；演示用圆整整数，不是任何国家或地区的真实在校生或家庭户统计） | ¥99 / 客户 / 月（示例假设 / example assumption） | 12 次/年（按月订阅；示例假设 / example assumption） | ¥1,188,000,000（示例假设 / example assumption） | Assumption / 假设 | `待补充`：真实项目应查阅所在国家或地区**公开发布的教育统计或人口/住户统计**中可核对的初高中在校生人数或家庭户数，再替换本行客户数。本示例不点名任何机构或报告，也不填写网址。查到前不要把本行的 1,000,000 当成真实人口。 |
| SAM | 细分 / 地理 / 可服务范围：中文、初高中课后场景；一二线城市、家长付费的家庭订阅。学校团体订阅未定价，不计入。 / Chinese-language middle- and high-school after-school use; first- and second-tier city family plans. School group plans excluded (no price yet). | 200,000（示例假设 / example assumption；= TAM 客户数 × 20% 的演示用圆整，不是真实城市或学科渗透率） | ¥99 / 客户 / 月（示例假设 / example assumption） | 12 次/年（示例假设 / example assumption） | ¥237,600,000（示例假设 / example assumption） | Assumption / 假设 | `待补充`：真实项目应在 TAM 客户数有公开来源之后，再用**可核对的地理/学段/付费能力过滤口径**收窄，而不是沿用本行的 20%。本示例不引用任何城市名单、入学率或付费比例报告。 |
| SOM | 1 年可现实份额（与 Y1 对齐）；Y2–Y3 `待补充` / Y1 obtainable share (aligned to Y1); Y2–Y3 待补充 | 1,912（示例假设 / example assumption；Y1 平均在册付费客户 = 22,944 客户·月 ÷ 12。M12 月末时点人数是 5,118 人，见下方对齐说明） | ¥99 / 客户 / 月（示例假设 / example assumption） | 12 次/年（示例假设 / example assumption） | ¥2,271,456（示例假设 / example assumption；= Y1 收入） | Assumption / 假设 | 由 [`financial-assumptions-and-validation.md`](./financial-assumptions-and-validation.md) 的关键假设表与 Y1 收入推导得出，不是外部市场报告。无来源网址。 |

Source type uses the same labels as `Key Assumptions / 关键假设表`: `Actual` / 实际, `Estimate` / 估算, `Assumption` / 假设, `待补充`.

本表没有 `Actual` 或 `Estimate`：项目尚未收费，也没有任何可核对的公开市场来源。TAM / SAM 客户数为演示用示例假设，来源栏为 `待补充`；价格、频次与 SOM 复用财务示例中的 `Assumption`（示例假设）。年度会员占比在财务示例中为 `待补充`，因此频次仍按 12 次月付计算，不混入 ¥899/年。

This table has no `Actual` or `Estimate`: the project is not charging yet, and there is no citable public market source. TAM / SAM customer counts are demonstration example assumptions with source `待补充`. Price, frequency, and SOM reuse `Assumption` (example assumption) rows from the financial example. Annual-plan share is `待补充` there, so frequency stays 12 monthly payments and does not mix in ¥899/year.

**Align with the financial plan / 与财务计划对齐:** SOM (Y1–Y3) should be consistent with Y1–Y3 revenue in `Three-Year Projection / 三年收入预测` and with paying-customer / price / ARPU rows in `Key Assumptions / 关键假设表`. If they diverge, revise SOM or the forecast and explain why.

与 [`financial-assumptions-and-validation.md`](./financial-assumptions-and-validation.md) 的对照 / Cross-check against the financial example:

| 财务口径 / Financial figure | 数值（均为示例假设） / Value (all example assumptions) | 本表示 SOM 如何使用 / How this SOM table uses it |
|---|---|---|
| Price or ARPU / 客单价或 ARPU | ¥99 / 客户 / 月 | 三行客单价相同 |
| Billing period / 计费周期 | 按月 | 频次 = 12 次/年 |
| Paying customers / 付费客户数 | M12 月末 5,118 人 | **时点人数**，不等于全年都在付费的客户数 |
| Y1 客户·月 | 22,944 | SOM 客户数 = 22,944 ÷ 12 = 1,912（年平均在册） |
| Y1 revenue / Y1 收入 | ¥2,271,456（约 ¥227 万） | **SOM 规模 = 该数字**，使「客户数 × 客单价 × 频次」与三年预测 Y1 一致 |
| Y2 revenue / Y2 收入 | `待补充` | 1–3 年 SOM 不能完整填写 |
| Y3 revenue / Y3 收入 | `待补充` | 同上；需先补学校团体订阅定价、签约周期和 Y2 获客预算 |

**已对齐 / Aligned:** Y1 SOM 规模 ¥2,271,456、客单价 ¥99/月、按月计费，与三年预测 Y1 及关键假设表一致。

**缺口（按模板说明，不另编数字）/ Gaps (explained per the template; no invented replacement figures):**

1. **Y2、Y3 为 `待补充`。** 模板要求 SOM 覆盖 1–3 年并与 Y1–Y3 收入一致。财务示例因缺少学校合作与 B 端假设，Y2 / Y3 收入保留 `待补充`。本示例因此只填 Y1 SOM；1–3 年合计 SOM 写 `待补充`，待财务假设补齐后再推导。路线图详细示例 [`roadmap.md`](./roadmap.md) 同样不为 12–18 个月编造客户或收入数字。
2. **M12 时点人数 ≠ Y1 确认收入。** 若用 5,118 × ¥99 × 12，会得到年化 run-rate **¥6,080,184**（5,118 × ¥1,188；示例假设下的反事实口径）。这与 Y1 收入 ¥2,271,456 不一致，因为 M1–M3 不收费、付费客户是从 M4 起爬坡的。模板要求与三年预测的 **Y1 收入** 对齐，所以表中 SOM 使用年平均 1,912 人 / ¥2,271,456，而不是年末人数 × 12。
3. **与大纲 / 路演已对齐。** [`bp-outline.md`](./bp-outline.md) 第 5、9 节和 [`pitch-deck-outline.md`](./pitch-deck-outline.md) 第 6、11 页已回写为本示例与财务示例的派生口径：Y1 / SOM = ¥2,271,456（示例假设）；Y2 / Y3 为 `待补充`。不再使用「5,000 人 × ¥1,000 = ¥500 万」的未推导全年满员口径。

**Top-down cross-check (optional) / 自上而下交叉核对（可选）:** if a cited industry total exists, compare it with bottom-up TAM. Do not invent a source. If they differ, state the gap and which figure you use.

本示例**没有**可引用的行业总额，因此**不做**自上而下交叉核对。行业总额 = `待补充`。真实项目若之后有带出处的公开行业规模，再与上表自下而上 TAM ¥1,188,000,000（示例假设）比较；在没有来源时，不编造行业规模，也不编造机构名、报告名或网址。

This example has **no** citable industry total, so it **does not** do a top-down cross-check. Industry total = `待补充`. If a later public figure has a real source, compare it with the bottom-up TAM ¥1,188,000,000 (example assumption). Until then, do not invent an industry total, institution, report title, or URL.

**When no reliable data exists / 没有可靠数据时:** use proxy indicators (e.g. countable target customers, public listings, interview frequency) and label the figure `Assumption` / 假设. If even a proxy is unavailable, write `待补充` rather than inventing a number or source.

本示例的处理 / How this example handles missing data:

- **TAM / SAM 客户数：** 没有可核对的公开人口或在校生统计（本示例也故意不使用任何真实人口数字）。表中 1,000,000 与 200,000 只是为演示「客户数 × 客单价 × 频次」而设的圆整**代理指标**，来源类型 `Assumption` / 假设，来源栏 `待补充`。真实创始人在查到公开发布的教育统计或人口/住户统计之前，应把这两格客户数改回 `待补充`，而不是复制这两个整数。
- **价格与频次：** 复用财务示例已有的规划假设（¥99/月、按月计费），仍标注为示例假设；不是市场统计。
- **SOM：** 用财务示例里可推导的 Y1 收入做代理，而不是另拍一个「占 SAM 的 10%」。Y2 / Y3 连代理假设都没有，写 `待补充`。
- **自上而下行业总额：** 连代理也没有，写 `待补充`，不做交叉核对。

**Market-Sizing Self-Check / 市场规模自检清单**

- [x] TAM, SAM, and SOM are defined, with the TAM → SAM → SOM filters stated. / 已给出 TAM / SAM / SOM，并写明从 TAM 收窄到 SAM、再到 SOM 的过滤条件。
  - TAM：品类内、不限城市的家庭订阅。SAM：中文 / 初高中课后 / 一二线城市家庭付费；排除未定价的学校团体订阅。SOM：Y1 可现实份额；Y2–Y3 `待补充`。
- [x] Every market figure has Source Type `Actual` / `Estimate` / `Assumption` / `待补充`, plus a source/link or an explicit assumption note. / 每个市场规模数字都标注了来源类型，并有来源链接或假设说明。
  - 每个数字都标明「示例假设」或 `待补充`。来源类型只有 `Assumption` / 假设 或 `待补充`。来源栏：TAM / SAM 为 `待补充` 加应查阅的公开资料类型；SOM 指向财务示例的推导，无外部网址。
- [x] No market number or source was invented; unknown values are `待补充`. / 没有编造市场规模数字或来源；未知值写 `待补充`。
  - 未引用真实人口、真实行业规模、真实报告、真实机构或网址。TAM / SAM 客户数是标了「示例假设」的演示用圆整代理，来源为 `待补充`，不能当作真实统计。Y2 / Y3 SOM、年度会员占比、自上而下行业总额均为 `待补充`。
- [ ] SOM is consistent with Y1–Y3 revenue and the Key Assumptions table. / SOM 与三年收入预测及关键假设表一致。
  - **Y1 通过：** SOM 规模 ¥2,271,456、客单价 ¥99/月、按月频次 12，与关键假设表和 Y1 收入一致；用年平均 1,912 人而不是 M12 的 5,118 × 12，避免与 Y1 确认收入分叉。
  - **未完全通过：** Y2、Y3 收入为 `待补充`，1–3 年 SOM 无法填完整。需先补学校团体订阅定价、签约周期和 Y2 获客预算，再更新 SOM。
- [x] If no reliable source exists, a proxy is used and labeled as an assumption, or the field is `待补充`. / 无可靠来源时使用代理指标并标注为假设，或写 `待补充`。
  - TAM / SAM 客户数：圆整代理 + `Assumption`（示例假设）+ 来源 `待补充`。SOM：财务 Y1 推导代理。行业总额与 Y2 / Y3：`待补充`。

**自检结论（示例）/ Self-check conclusion (example):** TAM → SAM → SOM 过滤条件、数字标注和「无来源则 `待补充`」通过；Y1 SOM 与财务示例对齐。1–3 年 SOM 因 Y2 / Y3 缺少假设而未完全通过。真实项目不要复制本表的 1,000,000 / 200,000 客户数，应在有公开统计之前把 TAM / SAM 客户数改回 `待补充`。

---

**再次说明：本文档所有内容均为虚构示例。每一个数字都是示例假设，或保留为 `待补充`。不包含真实市场统计、真实人口数字、真实报告或来源网址。**

**Again: this document is entirely fictional. Every number is an example assumption, or is left as `待补充`. It contains no real market statistics, real population figures, real reports, or source URLs.**

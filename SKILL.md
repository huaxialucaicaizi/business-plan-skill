---
name: business-plan-template
description: Use when creating, adapting, or filling business-plan materials, pitch deck content, incubator applications, project introductions, founder/team sections, market and competitor analysis, business models, financial projections, fundraising plans, or official application forms for a startup or new venture. This skill provides a reusable structure and placeholder-based workflow rather than project-specific facts.
---

# Business Plan Template

Use this skill when the user asks to create, update, polish, adapt, or fill materials for a startup, business project, incubator application, or pitch process.

## Scope

This skill supports:
- 商业计划书、执行摘要、可行性报告
- 路演 PPT 内容、页面标题、项目亮点
- 调用 `codex-ppt` 将商业计划书转化为高颜值视觉版路演材料
- 园区、孵化器、创业社区、政府项目申请材料
- 企业（团队）介绍、核心成员简介、项目内容摘要
- 市场背景、目标客户、竞品分析、产品定位、商业模式、竞争优势
- 财务预测、融资计划、里程碑、资源需求
- Word / Excel / PPT 申请模板的内容填充

## Privacy And Accuracy Rules

- Do not invent names, IDs, phone numbers, emails, addresses, company registration numbers, legal entities, awards, patents, revenue, funding, or customer names.
- If a field requires unknown personal, legal, financial, or registration information, write `待补充` or ask the user for it.
- For public or GitHub-ready outputs, remove private facts and replace them with placeholders.
- For official forms, preserve template structure and fill only relevant fields.
- For project summaries in official materials, prefer objective third-person wording and avoid `我` / `我们` unless the field asks for a personal statement.
- When using numbers, clearly distinguish actual data, estimates, assumptions, and placeholders.

## What To Read

Load only the reference needed for the task:

- Overall business-plan structure, positioning, customer pain, market, product, roadmap, and finance assumptions: read `references/business-plan-core.md`.
- Founder/team profile and competitive-advantage patterns: read `references/founder-and-advantage.md`.
- Short application copy, official-form fields, and materials checklist wording: read `references/application-copy.md`.

## Default Workflow

1. Identify the target audience: investor, incubator reviewer, government park, partner, customer, or internal team.
2. Clarify the venture type, target customers, key pain point, product/service, business model, and any known metrics.
3. If facts are missing, use placeholders rather than inventing.
4. Structure content around:
   - pain point
   - target customer
   - solution
   - product workflow
   - market opportunity
   - competition and differentiation
   - team capability
   - business model
   - roadmap
   - financial plan
   - funding/resource request
5. Adapt tone and length to the artifact:
   - application form: concise, objective, policy-friendly
   - pitch deck: sharp claims, visual page logic, investor-friendly
   - business plan: structured, detailed, evidence-oriented
   - short text box: copy-ready and within requested character limits

## Pitch Deck Visual Workflow

When the user asks for a good-looking PPT, visual pitch deck, investor deck, roadshow deck, or presentation based on the business plan, use `codex-ppt` when available.

Recommended sequence:

1. First use this business-plan skill to lock the deck narrative:
   - cover and one-line positioning
   - market background and pain point
   - target customer and use case
   - product workflow / demo logic
   - business model
   - market size
   - competition and differentiation
   - founder/team capability
   - financial forecast
   - roadmap and funding/resource request
2. Compress each slide into one main claim, 2-4 support points, and a suggested visual form.
3. Call `codex-ppt` to generate a polished 16:9 visual deck from the approved outline.
4. After generation, review whether the deck covers:
   - team capability
   - business model
   - competitive advantage
   - market opportunity
   - financial data
5. If the target is an incubator or government park, make the visuals credible, concise, and application-friendly rather than overly marketing-like.

Suggested user-facing prompt:

> 调用商业计划书 skill 先整理路演逻辑，再调用 `codex-ppt` 输出一份高颜值 16:9 商业计划书 PPT，目标读者是 `[投资人/园区评委/合作伙伴]`，重点说服他们相信 `[项目名称]` 的市场机会、团队能力、商业模式和落地路径。

## Generic Positioning Template

Use this as a starting point, then replace placeholders:

> `[Project Name]` is a `[product/service category]` for `[target customer]`, helping them solve `[specific high-pain problem]` through `[core technology/workflow]`, so they can achieve `[measurable business outcome]`.

Chinese version:

> `[项目名称]` 是面向 `[目标客户]` 的 `[产品/服务类型]`，通过 `[核心技术/工作流]` 解决 `[具体高痛点问题]`，帮助客户实现 `[可衡量业务结果]`。

## Deliverable Behavior

- If creating/editing DOCX, XLSX, or PPTX, use relevant document, spreadsheet, presentation, or deck-generation skills when available.
- If the user asks for a visually polished deck, explicitly use `codex-ppt` when available instead of only writing slide text.
- For official application files, list which fields remain `待补充`.
- For public templates, remove project-specific facts before finalizing.
- For short requested copy, provide copy-ready text rather than a long explanation.

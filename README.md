# Business Plan Skill Template

这是一个用于沉淀商业计划书、路演材料、孵化器申请材料和项目介绍口径的 Codex skill 模板。你可以把自己的项目定位、创始人故事、市场分析、竞品分析、商业模式、融资计划和常用申请文案放入 `references/`，让 Codex 在后续写材料时保持一致口径。

## 适用场景

当你需要反复处理同一个创业项目或业务项目的材料时，可以使用这类 skill：

- 商业计划书、执行摘要、项目简介
- 路演 PPT 内容、页面标题、项目亮点
- 园区、孵化器、创业社区申请材料
- 企业（团队）介绍、核心成员简介、项目内容摘要
- 市场背景、竞品分析、产品定位、商业模式、竞争优势
- 财务预测、融资计划、里程碑和资源需求

## 推荐文件结构

```text
business-plan-skill/
├── SKILL.md
├── README.md
├── agents/
│   └── openai.yaml
└── references/
    ├── application-copy.md
    ├── business-plan-core.md
    └── founder-and-advantage.md
```

## 文件说明

### `SKILL.md`

skill 的入口文件，用于告诉 Codex：

- 什么时候触发这个 skill
- 需要遵守哪些核心规则
- 哪些 reference 文件应该在什么任务下读取
- 输出文档、PPT、表格或申请材料时的默认工作流

### `references/business-plan-core.md`

用于存放项目的核心商业计划信息，例如：

- 产品定位
- 目标客户
- 用户痛点
- 产品模块
- 市场逻辑
- 竞品分析
- 商业模式
- 发展路线图
- 财务预测和融资计划

### `references/founder-and-advantage.md`

用于存放团队和竞争优势信息，例如：

- 创始人背景
- 核心成员简介
- 团队能力结构
- 外部资源网络
- 竞争壁垒
- 可复用的团队介绍文案

### `references/application-copy.md`

用于存放常用申请材料文案，例如：

- 企业（团队）介绍
- 核心成员及简介
- 项目内容摘要
- 项目基本情况表短摘要
- 官方表格默认字段
- 材料清单填写口径

## 使用方式

示例请求：

```text
调用这个商业计划书 skill，帮我把项目介绍压缩到 300 字以内。
```

```text
用这个 skill 的口径，更新孵化器入驻申请表。
```

```text
根据这个 skill，帮我生成一页竞品分析 PPT。
```

```text
用这个 skill，把团队能力和竞争优势改得更适合园区评委。
```

## 如何改成自己的项目

1. 修改 `SKILL.md` 的 `name` 和 `description`。
2. 在 `business-plan-core.md` 中替换项目定位、客户、市场、产品和财务信息。
3. 在 `founder-and-advantage.md` 中替换创始人、团队和竞争优势信息。
4. 在 `application-copy.md` 中替换常用申请文案和表格默认值。
5. 重启 Codex，让新的 skill 元数据进入自动触发列表。



公开版可以保留结构和方法论，把具体项目数据替换为示例占位符。


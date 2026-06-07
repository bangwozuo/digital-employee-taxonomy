# Digital Employee Taxonomy

> 一句话说明：数字员工（Digital Employee）开源生态的分类体系仓库，定义行业、岗位、技能、连接器和通用标签的标准化分类，确保所有资产在市场中可被一致地发现、筛选和组织。

[![License: CC-BY-4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Taxonomy Version](https://img.shields.io/badge/Taxonomy%20Version-2.1-green)]()

---

## 你可以直接用什么

| 资源 | 说明 | 路径 |
|------|------|------|
| **行业分类** | 20 个标准化行业分类 | [`industries/`](./industries/) |
| **岗位定义** | 常见数字员工岗位 | [`roles/`](./roles/) |
| **技能分类** | 业务技能标签体系 | [`skills/`](./skills/) |
| **连接器分类** | 第三方平台分类 | [`connectors/`](./connectors/) |
| **通用标签** | 跨领域通用标签 | [`tags/`](./tags/) |

---

## 快速开始

### 引用行业分类

```yaml
# 在你的 DigitalEmployeePackage 中引用
categories:
  - ecommerce-retail      # 电商零售
  - customer-service      # 客户服务
```

### 引用岗位定义

```yaml
# 在你的 DigitalEmployee 中引用
role:
  title: customer-service-specialist
  department: customer-service
```

### 引用技能标签

```yaml
# 在你的 BusinessSkill 中引用
tags:
  - product-recommendation
  - sentiment-analysis
```

---

## 目录结构

```
digital-employee-taxonomy/
├── README.md                          # 本文件
├── LICENSE                            # CC-BY-4.0
├── NOTICE                             # 归属与致谢
├── CONTRIBUTING.md                      # 贡献指南
├── CODE_OF_CONDUCT.md                 # 行为准则
├── SECURITY.md                        # 安全政策
├── SUPPORT.md                         # 获取帮助
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md
│   │   └── feature_request.md
│   └── PULL_REQUEST_TEMPLATE.md
├── industries/                        # 行业分类
│   └── *.yaml
├── roles/                             # 岗位定义
│   └── *.yaml
├── skills/                            # 技能分类
│   └── *.yaml
├── connectors/                        # 连接器平台分类
│   └── *.yaml
└── tags/                              # 通用标签
    └── *.yaml
```

---

## 分类体系概览

### 行业分类（20个）

| ID | 名称 | 说明 |
|----|------|------|
| `one-person-company` | 一人公司 | 个体创业者、自由职业者 |
| `startup-decision` | 创业决策 | 早期创业、战略决策 |
| `internet-product-dev` | 互联网产品研发 | 产品设计、开发、测试 |
| `tech-outsourcing` | 技术外包 | 外包项目管理、交付 |
| `ai-app-generation` | AI应用生成 | AI应用开发、Prompt工程 |
| `content-marketing` | 内容营销 | 内容创作、分发、运营 |
| `private-domain-ops` | 私域运营 | 社群运营、用户运营 |
| `ecommerce-retail` | 电商零售 | 电商运营、店铺管理 |
| `local-life` | 本地生活 | 餐饮、美业、本地服务 |
| `sales-growth` | 销售增长 | 销售管理、线索培育 |
| `customer-service` | 客户服务 | 售前售后、客户成功 |
| `finance-tax` | 财税 | 记账、报税、财务分析 |
| `admin-hr` | 行政人事 | 考勤、招聘、员工关系 |
| `legal-contract` | 法务合同 | 合同审核、合规管理 |
| `recruitment` | 招聘 | 简历筛选、面试安排 |
| `data-analysis` | 数据分析 | 数据报表、商业分析 |
| `knowledge-base` | 知识库 | 文档管理、知识沉淀 |
| `automation-office` | 自动化办公 | 流程自动化、效率工具 |
| `design-creative` | 设计创意 | 平面设计、UI/UX、创意 |
| `platform-ops` | 平台运营 | 平台治理、社区运营 |

### 岗位定义

参见 [`roles/`](./roles/) 目录下的岗位定义文件。

### 技能分类

参见 [`skills/`](./skills/) 目录下的技能分类文件。

### 连接器平台分类

参见 [`connectors/`](./connectors/) 目录下的连接器分类文件。

### 通用标签

参见 [`tags/`](./tags/) 目录下的通用标签文件。

---

## 平台入口

- **总入口**: [awesome-digital-employees-zh](https://github.com/hermes-agent/awesome-digital-employees-zh)
- **总规范**: [digital-employee-spec](https://github.com/hermes-agent/digital-employee-spec)
- **技能市场**: [digital-employee-skills-zh](https://github.com/hermes-agent/digital-employee-skills-zh)
- **连接器市场**: [digital-employee-connectors-zh](https://github.com/hermes-agent/digital-employee-connectors-zh)

---

## 贡献方式

分类体系的变更需要经过社区讨论。详见 [CONTRIBUTING.md](./CONTRIBUTING.md)。

---

## License

本仓库采用 [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/) 授权。

- 你可以自由分享、改编本仓库内容
- 必须注明出处：Hermes Agent / 数字员工平台

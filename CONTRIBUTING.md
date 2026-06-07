# Contributing to Digital Employee Taxonomy

感谢你对数字员工分类体系的贡献！分类体系的变更需要谨慎处理以确保一致性。

## 贡献类型

| 类型 | 说明 | 影响级别 |
|------|------|---------|
| 新增分类 | 添加新的行业、岗位、技能或标签 | 中 — 需社区讨论 |
| 分类修订 | 修改现有分类的定义或属性 | 高 — 可能影响现有资产 |
| 标签补充 | 添加新的标签值 | 低 — 直接 PR |
| 文档改进 | 修正拼写、格式、链接 | 低 — 直接 PR |

## 提交规范

### 新增行业分类

1. 提交 Issue 讨论必要性
2. 提供行业定义、适用场景、相关资产示例
3. 获得 1 名维护者批准后提交 PR

### 新增岗位定义

1. 确保岗位与现有行业分类关联
2. 提供岗位职责、所需技能、典型工作流
3. 提交 PR

### 新增技能标签

1. 确保技能标签与现有分类体系一致
2. 提供技能定义、输入输出示例
3. 提交 PR

### Commit Message 规范

```
taxonomy: <type> - <description>

type: industry, role, skill, connector, tag
description: 变更摘要
```

## 审核标准

- [ ] 分类定义清晰、无歧义
- [ ] 与现有分类无重复
- [ ] 命名符合 [digital-employee-spec](https://github.com/bangwozuo/digital-employee-spec) 命名规范
- [ ] YAML 语法正确
- [ ] 文档链接有效

## 行为准则

所有贡献者必须遵守 [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md)。

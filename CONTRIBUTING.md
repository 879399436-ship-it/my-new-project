# 贡献指南

感谢你愿意为 `my-new-project` 做出贡献。请在提交代码前阅读以下协作规范。

## 分支管理

- `main`：稳定发布分支，仅通过 Pull Request 合并。
- `feature/*`：新功能开发分支。
- `fix/*`：缺陷修复分支。
- `chore/*`：工具链、文档与配置类变更。
- `docs/*`：仅文档相关变更。

### 推荐流程

1. 从 `main` 拉取最新代码：`git checkout main && git pull origin main`
2. 创建功能分支：`git checkout -b feature/your-feature-name`
3. 完成开发后推送并创建 Pull Request。

## 提交规范

采用 [Conventional Commits](https://www.conventionalcommits.org/) 风格：

```
<type>(<scope>): <subject>
```

常用 `type`：

| type | 说明 |
|------|------|
| `feat` | 新功能 |
| `fix` | 缺陷修复 |
| `docs` | 文档变更 |
| `style` | 代码格式（不影响逻辑） |
| `refactor` | 重构 |
| `test` | 测试相关 |
| `chore` | 构建/工具/配置 |

示例：

```
docs: 更新 README 快速开始章节
chore: 添加 Python 与 Node.js 的 gitignore 规则
fix(api): 修复空指针异常
```

## Pull Request 流程

1. **创建 PR**：目标分支为 `main`，标题清晰描述变更意图。
2. **填写说明**：包含变更摘要、动机、测试方式及关联 Issue（如有）。
3. **自检清单**：
   - [ ] 通过本地测试/构建
   - [ ] 文档已同步更新
   - [ ] 无多余调试代码或敏感信息
4. **代码评审**：至少一名维护者 Approve 后方可合并。
5. **合并策略**：优先使用 **Squash merge**，保持 `main` 历史简洁。

## 行为准则

请保持尊重、包容的沟通方式。如有争议，请在 Issue 或 PR 中公开讨论。

## 问题反馈

- Bug 报告：https://github.com/879399436-ship-it/my-new-project/issues/new
- 功能建议：https://github.com/879399436-ship-it/my-new-project/issues/new

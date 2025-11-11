# GitHub 入门指南

_在不到一小时的时间内开始使用 GitHub。_

## 欢迎

人们使用 GitHub 构建世界上一些最先进的技术。无论你是在可视化数据还是构建新游戏，GitHub 上都有整个社区和工具集可以帮助你做得更好。GitHub Skills 的"GitHub 入门"课程将在不到一小时的时间内引导你完成开始贡献所需的一切。

- **适合人群**：新开发者、GitHub 新用户和学生。
- **你将学到什么**：我们将介绍仓库、分支、提交和拉取请求。
- **你将构建什么**：我们将制作一个简短的 Markdown 文件，你可以将其用作你的[个人资料 README](https://docs.github.com/zh/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)。
- **前置要求**：无。这门课程非常适合你在 GitHub 上的第一天。
- **所需时间**：完成本课程需要不到一小时。

## GitHub Copilot Agent 模式功能介绍

### 什么是 Agent 模式？

**Agent 模式**是 GitHub Copilot 的高级功能，它不仅能回答问题，还能自主执行完整的开发任务。与传统的聊天模式不同，Agent 模式可以直接操作代码仓库，帮助你完成从问题分析到代码实现的整个流程。

### Agent 模式的主要功能

Agent 模式具备以下强大能力：

1. **自主执行任务** - 自动浏览代码、创建文件、修改代码、运行测试
2. **使用开发工具** - 访问 Git、文件系统、构建工具、测试框架等
3. **多步骤规划** - 制定详细计划并逐步执行复杂任务
4. **代码审查** - 自动进行代码审查和安全检查
5. **问题修复** - 完整地修复 issues、bugs 和实现新功能

### Agent 模式 vs Chat 模式

了解两种模式的区别，有助于你选择合适的工具：

| 特性 | Chat 模式 | Agent 模式 |
|------|----------|-----------|
| **交互方式** | 问答对话 | 任务执行 |
| **代码修改** | 提供建议和代码片段 | 直接修改文件并提交 |
| **工具使用** | 无法使用外部工具 | 可使用 Git、bash、文件系统等 |
| **任务范围** | 单次问答 | 完整的多步骤任务 |
| **输出结果** | 文本和代码建议 | 实际的 commits 和 PRs |
| **适用场景** | 快速咨询、学习概念 | 实现功能、修复 bug |

### 如何高效使用 Agent 模式

掌握以下技巧，让 Agent 模式为你更好地工作：

#### 1. 编写清晰的任务描述

在创建 issue 时：
- ✅ **明确目标**：清楚说明你想要实现什么
- ✅ **提供上下文**：说明相关的文件、功能或背景信息
- ✅ **列出约束**：如果有特定要求或限制，请明确指出

示例：
```
好的描述：在 README.md 中添加一个新的"安装说明"章节，
包含 npm install 和配置步骤

不够好的描述：更新文档
```

#### 2. 单一职责原则

- 每个 issue 聚焦一个明确的任务
- 避免在一个 issue 中混合多个不相关的需求
- 复杂任务可以拆分为多个小任务

#### 3. 及时提供反馈

- 通过 PR 评论与 Agent 互动
- 如果结果不符合预期，说明具体问题
- Agent 会根据你的反馈进行调整和改进

#### 4. 利用迭代优化

- Agent 第一次的实现可能不完美
- 通过评论提出改进建议
- 让 Agent 逐步优化代码质量

### GitHub Education 与 Agent 模式

如果你使用 GitHub Education 账户：

- ✅ **免费访问** - GitHub Copilot（包括 Agent 模式）对学生免费
- 📊 **使用配额** - 具体限制取决于你的订阅计划
- 💡 **查看配额** - 访问 Settings → Copilot 查看当前使用情况
- 🎓 **学习资源** - 充分利用这个强大工具来学习和实践

### 最佳实践示例

**场景 1：添加新功能**
```markdown
Issue: 为用户登录页面添加"记住我"功能
- 在登录表单中添加复选框
- 使用 localStorage 保存用户偏好
- 添加相应的单元测试
```

**场景 2：修复 Bug**
```markdown
Issue: 修复用户头像显示问题
- 问题：头像在移动设备上显示模糊
- 位置：components/UserProfile.jsx
- 期望：使用高分辨率图片并正确缩放
```

**场景 3：改进文档**
```markdown
Issue: 完善 API 文档
- 为所有公共方法添加 JSDoc 注释
- 包含参数说明和返回值类型
- 添加使用示例
```

---

## 如何使用这个课程

在本课程中，你将：

1. 创建一个分支
2. 提交一个文件
3. 打开一个拉取请求
4. 合并你的拉取请求

### 开始课程的步骤

#### 1. Fork 这个仓库

滚动到页面顶部，点击 Fork 按钮旁边的下拉箭头。然后点击"Create a new fork"（创建新的 fork）来 fork 这个仓库。

#### 2. 开始课程

右键点击 **Start course**（开始课程）按钮并在新标签页中打开链接。

[![start-course](https://user-images.githubusercontent.com/1221423/235727646-4a590299-ffe5-480d-8cd5-8194ea184546.svg)](https://github.com/new?template_owner=skills&template_name=introduction-to-github&owner=%40me&name=skills-introduction-to-github&description=My+clone+repository&visibility=public)

#### 3. 创建你的仓库

在新标签页中，大多数提示将自动为你填写。
- 对于所有者（owner），选择你的个人账户或组织来托管仓库。
- 我们建议创建公共仓库，因为私有仓库将[使用 Actions 分钟数](https://docs.github.com/zh/billing/managing-billing-for-github-actions/about-billing-for-github-actions)。
- 向下滚动并点击表单底部的 **Create repository**（创建仓库）按钮。

#### 4. 跟随说明

创建新仓库后，等待大约 20 秒，然后刷新页面。按照新仓库 README 中的分步说明进行操作。

## 课程内容

### 第 1 步：创建分支
你将学习如何创建一个新分支来进行更改，而不影响主分支。

### 第 2 步：提交文件
你将学习如何创建新文件并将更改提交到你的分支。

### 第 3 步：打开拉取请求
你将学习如何创建拉取请求以提议将你的更改合并到主分支。

### 第 4 步：合并拉取请求
你将学习如何审查和合并拉取请求。

## 常见问题

**问：我完成课程后会发生什么？**

答：完成后，你将拥有一个个人资料 README，并了解 GitHub 的基本工作流程！

**问：如果我遇到问题怎么办？**

答：你可以在[讨论区](https://github.com/orgs/skills/discussions/categories/introduction-to-github)发帖寻求帮助。

**问：这门课程是免费的吗？**

答：是的！所有 GitHub Skills 课程都是完全免费的。

## 获取帮助

- [在我们的讨论区发帖](https://github.com/orgs/skills/discussions/categories/introduction-to-github)
- [查看 GitHub 状态页面](https://www.githubstatus.com/)

---

&copy; 2024 GitHub &bull; [行为准则](https://www.contributor-covenant.org/zh-cn/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT 许可证](https://gh.io/mit)

---

[English](README.md) | 简体中文

#  Issue 操作指南

## 1. 🔍 查找 Issue

### 1.1 🌐 全局搜索

**适用场景**：需要跨所有项目搜索相关 Issue。

**操作步骤**：
1. 访问 [HPCKit 社区 Issues 板块](https://atomgit.com/kunpengcompute/hpckit-community/issues)
2. 在搜索框中输入关键字（支持标题及内容搜索）
3. 按 Enter 键或点击搜索按钮进行搜索

### 1.2 📁 项目内搜索

**适用场景**：只在特定项目内搜索 Issue。

**操作步骤**：
1. 访问 [HPCKit 社区项目列表](https://atomgit.com/kunpengcompute/hpckit-community/blob/main/README.md)
2. 选择目标项目，进入项目主页
3. 点击 **Issues** 标签页
4. 在搜索框中输入关键字进行搜索

## 2. ✨ 创建 Issue

如果您需要上报 Bug、提交需求或提供建议，请按以下流程操作：

### 2.1 🎯 选择项目

1. 访问 [HPCKit 社区项目列表](https://atomgit.com/kunpengcompute/hpckit-community/blob/main/README.md)
2. 选择与问题相关的目标项目
   > **💡不确定归属时**：可提交至 **[community](https://atomgit.com/kunpengcompute/hpckit-community)** 仓库，社区将协助分发至合适的 SIG 或仓库。

### 2.2 ➕ 新建 Issue

1. 进入目标项目主页的 **Issues** 标签页
2. 点击 **新建 Issue** 按钮
   ![](images/issue-banner.png)

### 2.3 📋 填写 Issue 详情

进入 Issue 详细填写页面：
   ![](images/issue-details.png)

**填写要求**：

| 字段 | 说明 | 填写建议 |
|------|------|----------|
| **标题** | Issue 的简要描述 | 清晰概括问题核心，便于搜索和识别 |
| **内容** | 详细的问题描述 | 按照模板提示完整填写，包括：<br>• 问题现象<br>• 复现步骤<br>• 期望结果<br>• 实际结果<br>• 环境信息（如适用） |

### 2.4 🚀 提交 Issue

填写完成后，点击 **新建 Issue** 完成创建。

> **📌 最佳实践**：
> - 若 Issue 用于自我跟踪，建议提交后立即指派给自己
> - 若跟踪他人工作，指派给具体负责人
> - 无需主动指派时，SIG maintainer 会定期审视并分配 Issue

## 3. 💬 评论 Issue

每个 Issue 下方都设有评论区，支持：
- 📝 补充问题细节
- 💡 提供解决方案建议
- 🤝 讨论技术实现
- ✅ 确认问题状态

> **注意**：请保持评论内容与Issue相关，遵守[社区行为准则](code-of-conduct.md)。

## ⚠️ 重要说明

1. **Issue清理机制**：长时间未处理的Issue将由SIG maintainer定期清理或重新分配
2. **社区协作**：鼓励通过评论区进行公开讨论，避免私下解决Issue

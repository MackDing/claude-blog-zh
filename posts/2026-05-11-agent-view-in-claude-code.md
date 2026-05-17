# Claude Code 中的 Agent 视图

> 

原文：https://claude.com/blog/agent-view-in-claude-code  
发布日期：May 11, 2026  
译者：@HiClaws

---

今天我们在 Claude Code 中推出 agent 视图：一个统一管理所有 Claude Code 会话的地方。

在此之前并行运行 agent 时，你可能不得不管理多个终端标签页、一个 tmux 网格，以及一个超负荷的任务清单来记录接下来需要处理的事项。

有了 Claude Code 中的 agent 视图，你可以启动新的 agent、将它们置于后台运行，并且只在 Claude 需要你时介入。一目了然地查看哪些 agent 在等待你的响应、哪些仍在工作、哪些已经完成，从而轻松地同时管理多个 agent。

## 工作原理

Agent 视图改进了在 CLI 中可视化和交互 Claude Code 会话的方式。

### 一览全局

在任何会话中按左箭头键，或在终端运行 claude agents 即可打开 agent 视图。每一行显示会话信息、是否需要你的输入、最后一次响应的内容，以及你最后一次交互的时间。

![](https://cdn.prod.website-files.com/68a44d4040f98a4adf2207b6/6a02147d18cd3a9a9fe18c4f_aef149a9.png)

### 无需离开即可预览和回复

选择一个会话可以预览最后一轮对话。如果会话正在等待决策，直接在线回复即可让会话继续进行。按回车键可以直接进入会话，查看完整的对话记录。

![](https://cdn.prod.website-files.com/68a44d4040f98a4adf2207b6/6a02147d18cd3a9a9fe18c52_57c35e02.png)

### 后台运行任何会话

此外，用户可以使用 /bg 将任何现有会话添加到 agent 视图，或者使用 claude --bg [任务] 完全跳过前台直接启动一个新的后台会话。

## 开发者如何使用 agent 视图

我们从早期用户那里观察到的一些使用模式：

- 扩展并发会话数量：一次性派发多个想法，每个想法可选择搭配一个 skill，然后回到准备好审查的 pull request 列表。
- 管理长时间运行的 agent：PR 监控器、仪表板更新器和其他循环任务会在列表中直接显示下次运行时间。
- 在独立会话间切换：当你在一个会话中时，按左箭头键启动一个相关任务或快速的代码库问题，然后按右箭头键返回正在做的事情。预览功能会在答案到来时显示。
- 查看已完成的工作：每行的状态指示器加上预览中的标题，让你可以轻松扫描哪些会话生成了 PR。

## 开始使用

Agent 视图今天作为研究预览版在 Pro、Max、Team、Enterprise 和 Claude API 计划中提供。运行 claude agents 即可开启。适用常规速率限制。更多信息请参阅文档。


---

仅供学习交流，版权归 Anthropic 所有。
# Code w/ Claude 旧金山 2026 回顾：在 AI 指数增长上构建

> 

原文：https://claude.com/blog/code-w-claude-sf-2026-sf  
发布日期：May 12, 2026  
译者：@HiClaws

---

本周在旧金山，我们举办了 Code w/ Claude，这是我们的年度开发者大会。这场活动汇聚了开发者、工程师和创始人，进行了为期两天的主题演讲、分组会议，以及与构建 Claude 的团队一起开展的工作坊。

从提示词和模型选择到构建 skill 架构和扩展 AI 原生工程团队，每一场会议都围绕着同一个转变：从想法到生产软件的距离正在缩小，而获得最大杠杆效应的团队正在为 AI 指数级增长而设计——而不是被动应对。

我们通过现场编码演示、客户深度剖析和实操教程展示了这在今天是什么样子。

![联合创始人兼总裁 Daniela Amodei 和联合创始人兼 CEO Dario Amodei 参与由首席产品官 Ami Vora 主持的炉边谈话。](https://cdn.prod.website-files.com/68a44d4040f98a4adf2207b6/6a02b62b0fd6f5b85ee0bea3_CwC.jpeg)

*联合创始人兼总裁 Daniela Amodei 和联合创始人兼 CEO Dario Amodei 参与由首席产品官 Ami Vora 主持的炉边谈话。*

## 我们发布的内容

在大会上发布，我们将 Claude Code 的速率限制提高了一倍，并提升了 Claude Opus 的 API 限制，以便开发者、初创公司和企业能够更可靠地大规模构建。这两项变更现已生效。

我们还在 Claude Platform 上为 Claude Managed Agents 引入了新功能，旨在帮助团队大规模构建和部署云托管 agent。四项新功能现已向所有开发者开放：

- Dreaming。一个定期流程，回顾过去的 agent 会话，发现模式并整理记忆，使 agent 在运行之间不断改进。重复出现的错误、共享的工作流程和团队偏好会被提取到更有用的记忆存储中。
- 多 agent 编排。主 agent 可以委派给专业子 agent，它们在共享文件系统上并行工作，每个都有自己的模型、提示词和工具。整个流程可在 Claude Console 中追溯。
- Outcomes。开发者定义一个标准来说明好的输出应该是什么样子。一个独立的评分器在其自己的上下文窗口中评估每个结果，并将 agent 送回修订直到满足标准。在我们的内部基准测试中，outcomes 在最难的问题上将任务成功率提高了多达 10 个百分点。
- Webhooks：一旦定义了 outcome，您就可以让 agent 运行，并在完成时通过 webhook 获得通知。

## 如果您错过了

![Claude Code 创建者 Boris Cherny 在旧金山举行的 Code w/ Claude 2026 大会上发表演讲。](https://cdn.prod.website-files.com/68a44d4040f98a4adf2207b6/6a02b5708e141ac8abcd4968_Exec%20Boris%20Cherny.jpg)

*Claude Code 创建者 Boris Cherny 在旧金山举行的 Code w/ Claude 2026 大会上发表演讲。*

如果您错过了直播，可以在这里查看我们的主题演讲和分组会议录像。

我们的演讲深入介绍了与 Anthropic 团队一起构建 Claude 的幕后故事，并分享了 Asana、Cursor、GitHub、Replit 和 Vercel 等客户如何设计生产就绪的 agent 并突破 agent 开发的边界。

我们将把 Code w/ Claude 带到伦敦（5月20-21日）和东京（6月5-6日）。所有第一天的主题演讲和分组会议都将进行直播。

敬请期待受我们演讲启发的技术教程、指南和客户故事。

‍


---

仅供学习交流，版权归 Anthropic 所有。
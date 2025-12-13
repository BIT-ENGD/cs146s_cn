# CS146S：现代软件开发者

斯坦福大学 • 2025年秋季

概览 教学大纲 常见问题

## 课程表

### 第一周：编码 LLM 与 AI 开发导论

**主题**

- 课程事务
- LLM (大语言模型) 到底是什么
- 如何高效进行提示词工程 (Prompting)

**阅读材料**

- [LLM 深度解析](https://www.youtube.com/watch?v=7xTGNNLPyMI)
- [提示词工程概览](https://cloud.google.com/discover/what-is-prompt-engineering)
- [提示词工程指南](https://www.promptingguide.ai/techniques)
- [AI 提示词工程：深度解析](https://www.youtube.com/watch?v=T9aRN5JkmL8)
- [OpenAI 如何使用 Codex](https://cdn.openai.com/pdf/6a2631dc-783e-479b-b1a4-af0cfbd38630/how-openai-uses-codex.pdf)

**作业**

- [LLM 提示词操练场](https://github.com/mihail911/modern-software-dev-assignments/tree/master/week1)

**9/22 (周一):** 介绍与 LLM 是如何制造的 - [幻灯片](https://docs.google.com/presentation/d/1zT2Ofy88cajLTLkd7TcuSM4BCELvF9qQdHmlz33i4t0/edit?usp=sharing)

**9/26 (周五):** LLM 高级提示技巧 - [幻灯片](https://docs.google.com/presentation/d/1MIhw8p6TLGdbQ9TcxhXSs5BaPf5d_h77QY70RHNfeGs/edit?usp=drive_link)

### 第二周：编码智能体 (Coding Agents) 剖析

**主题**

- 智能体架构与组件
- 工具使用与函数调用
- MCP (模型上下文协议)

**阅读材料**

- [MCP 介绍](https://stytch.com/blog/model-context-protocol-introduction/)
- [MCP 服务器实现示例](https://github.com/modelcontextprotocol/servers)
- [MCP 服务器认证](https://developers.cloudflare.com/agents/guides/remote-mcp-server/#add-authentication)
- [MCP 服务器 SDK](https://github.com/modelcontextprotocol/typescript-sdk/tree/main?tab=readme-ov-file#server)
- [MCP 注册表](https://blog.modelcontextprotocol.io/posts/2025-09-08-mcp-registry-preview/)
- [关于 MCP 的思考](https://www.reillywood.com/blog/apis-dont-make-good-mcp-tools/)

**作业**

- [AI IDE 的第一步](https://github.com/mihail911/modern-software-dev-assignments/tree/master/week2)

**9/29 (周一):** 从零构建编码智能体 - [幻灯片](https://docs.google.com/presentation/d/11CP26VhsjnZOmi9YFgLlonzdib9BLyAlgc4cEvC5Fps/edit?usp=sharing), [完成的练习](https://drive.google.com/file/d/1YtpKFVG13DHyQ2i3HOtwyVJOV90nWeL2/view?usp=drive_link)

**10/3 (周五):** 构建自定义 MCP 服务器 - [幻灯片](https://docs.google.com/presentation/d/1zSC2ra77XOUrJeyS85houg1DU7z9hq5Y4ebagTch-5o/edit?usp=drive_link), [完成的练习](https://drive.google.com/file/d/1J6lgZWcxPzpCpjujJSnW1aAkCYF6Yxv3/view?usp=drive_link)

### 第三周：AI 集成开发环境 (IDE)

**主题**

- 上下文管理与代码理解
- 智能体的 PRD (产品需求文档)
- IDE 集成与扩展

**阅读材料**

- [规格说明书 (Specs) 是新的源代码](https://blog.ravi-mehta.com/p/specs-are-the-new-source-code)
- [长上下文是如何失败的](https://www.dbreunig.com/2025/06/22/how-contexts-fail-and-how-to-fix-them.html)
- [Devin: 编码智能体入门](https://devin.ai/agents101#introduction)
- [让 AI 在复杂代码库中工作](https://github.com/humanlayer/advanced-context-engineering-for-coding-agents/blob/main/ace-fca.md)
- [FAANG (大厂) 如何进行 Vibe Coding](https://x.com/rohanpaul_ai/status/1959414096589422619)
- [为智能体编写高效工具](https://www.anthropic.com/engineering/writing-tools-for-agents)

**作业**

- [构建自定义 MCP 服务器](https://github.com/mihail911/modern-software-dev-assignments/blob/master/week3/assignment.md)

**10/6 (周一):** 从第一个提示词到最佳 IDE 设置 - [幻灯片](https://docs.google.com/presentation/d/11pQNCde_mmRnImBat0Zymnp8TCS_cT_1up7zbcj6Sjg/edit?usp=sharing), [设计文档模板](https://drive.google.com/file/d/1MZ0Qx68Vzw4x5x_XcV8XiPLp7fFDe1LJ/view?usp=drive_link)

**10/10 (周五):** [Silas Alberti](https://www.linkedin.com/in/silasalberti/)，研究主管 [Cognition](https://cognition.ai/) - [幻灯片](https://docs.google.com/presentation/d/1i0pRttHf72lgz8C-n7DSegcLBgncYZe_ppU7dB9zhUA/edit?usp=sharing)

### 第四周：编码智能体模式

**主题**

- 管理智能体自主等级
- 人机协作模式

**阅读材料**

- [Anthropic 如何使用 Claude Code](https://www-cdn.anthropic.com/58284b19e702b49db9302d5b6f135ad8871e7658.pdf)
- [Claude 最佳实践](https://www.anthropic.com/engineering/claude-code-best-practices)
- [Awesome Claude Agents (Claude 智能体大全)](https://github.com/vijaythecoder/awesome-claude-agents)
- [Super Claude](https://github.com/SuperClaude-Org/SuperClaude_Framework)
- [好上下文带来好代码](https://blog.stockapp.com/good-context-good-code/)
- [一探 Claude Code 幕后机制](https://medium.com/@outsightai/peeking-under-the-hood-of-claude-code-70f5a94a9a62)

**作业**

- [使用 Claude Code 编程](https://github.com/mihail911/modern-software-dev-assignments/blob/master/week4/assignment.md)

**10/13 (周一):** 如何成为智能体管理者 - [幻灯片](https://docs.google.com/presentation/d/19mgkwAnJDc7JuJy0zhhoY0ZC15DiNpxL8kchPDnRkRQ/edit?usp=sharing)

**10/17 (周五):** [Boris Cherney](https://www.linkedin.com/in/bcherny/)，[Claude Code](https://www.anthropic.com/claude-code) 创作者 - [幻灯片](https://docs.google.com/presentation/d/1bv7Zozn6z45CAh-IyX99dMPMyXCHC7zj95UfwErBYQ8/edit?usp=sharing)

### 第五周：现代终端

**主题**

- AI 增强的命令行界面
- 终端自动化与脚本编写

**阅读材料**

- [Warp 大学](https://www.warp.dev/university?slug=university)
- [Warp 对比 Claude Code](https://www.warp.dev/university/getting-started/warp-vs-claude-code)
- [Warp 如何使用 Warp 构建 Warp](https://notion.warp.dev/How-Warp-uses-Warp-to-build-Warp-21643263616d81a6b9e3e63fd8a7380c)

**作业**

- [使用 Warp 进行代理式开发](https://github.com/mihail911/modern-software-dev-assignments/tree/master/week5)

**10/20 (周一):** 如何打造突破性的 AI 开发者产品 - [幻灯片](https://docs.google.com/presentation/d/1Djd4eBLBbRkma8rFnJAWMT0ptct_UGB8hipmoqFVkxQ/edit?usp=sharing)

**10/24 (周五):** [Zach Lloyd](https://www.linkedin.com/in/zachlloyd/)，CEO [Warp](https://www.warp.dev/) - [幻灯片](https://www.figma.com/slides/kwbcmtqTFQMfUhiMH8BiEx/Warp---Stanford--Copy-?node-id=9-116&t=oBWBCk8mjg2l2NR5-1)

### 第六周：AI 测试与安全

**主题**

- 安全的 Vibe Coding (直觉式编码)
- 漏洞检测简史
- AI 生成的测试套件

**阅读材料**

- [SAST 与 DAST 对比](https://www.splunk.com/en_us/blog/learn/sast-vs-dast.html)
- [通过提示词注入实现 Copilot 远程代码执行](https://embracethered.com/blog/posts/2025/github-copilot-remote-code-execution-via-prompt-injection/)
- [使用 Claude Code 和 OpenAI Codex 发现现代 Web 应用中的漏洞](https://semgrep.dev/blog/2025/finding-vulnerabilities-in-modern-web-apps-using-claude-code-and-openai-codex/)
- [代理式 AI 威胁：身份欺诈与冒充风险](https://unit42.paloaltonetworks.com/agentic-ai-threats/#:~:text=Identity spoofing and impersonation: Attackers,accurate information exchange are critical.)
- [OWASP Top Ten: 主要 Web 应用安全风险](https://owasp.org/www-project-top-ten/)
- [上下文腐烂：理解 AI 上下文窗口的退化](https://research.trychroma.com/context-rot)
- [使用 O3 进行漏洞提示词分析](https://github.com/SeanHeelan/o3_finds_cve-2025-37899/blob/master/system_prompt_uafs.prompt)

**作业**

- [编写安全的 AI 代码](https://github.com/mihail911/modern-software-dev-assignments/blob/master/week6/assignment.md)

**10/27 (周一):** AI 质量保证 (QA)、SAST、DAST 及更多 - [幻灯片](https://docs.google.com/presentation/d/1C05bCLasMDigBbkwdWbiz4WrXibzi6ua4hQQbTod_8c/edit?usp=sharing)

**10/31 (周五):** [Isaac Evans](https://www.linkedin.com/in/isaacevans/)，CEO [Semgrep](https://semgrep.dev/)

### 第七周：现代软件支持

**主题**

- 我们可以信任哪些 AI 代码系统
- 调试与诊断
- 智能文档生成

**阅读材料**

- [代码审查：尽管去做 (Just Do It)](https://blog.codinghorror.com/code-reviews-just-do-it/)
- [如何有效地审查代码](https://github.blog/developer-skills/github/how-to-review-code-effectively-a-github-staff-engineers-philosophy/)
- [现代代码审查中 AI 辅助的编码实践评估](https://arxiv.org/pdf/2405.13565)
- [AI 代码审查实施最佳实践](https://graphite.dev/guides/ai-code-review-implementation-best-practices)
- [软件团队的代码审查要素](https://blakesmith.me/2015/02/09/code-review-essentials-for-software-teams.html)
- [百万次 AI 代码审查的经验教训](https://www.youtube.com/watch?v=TswQeKftnaw)

**作业**

- [代码审查练习 (Reps)](https://github.com/mihail911/modern-software-dev-assignments/tree/master/week7)

**11/3 (周一):** AI 代码审查 - [幻灯片](https://docs.google.com/presentation/d/1NkPzpuSQt6Esbnr2-EnxM9007TL6ebSPFwITyVY-QxU/edit?usp=sharing)

**11/7 (周五):** [Tomas Reimers](https://www.linkedin.com/in/tomasreimers/)，CPO [Graphite](https://graphite.dev/) - [幻灯片](https://drive.google.com/file/d/1hwF-RIkOJ_OFy17BKhzFyCtxSS7Pcf7p/view?usp=drive_link)

### 第八周：自动化 UI 与应用构建

**主题**

- 面向所有人的设计与前端
- 快速 UI/UX 原型设计与迭代

**作业**

- [多技术栈 Web 应用构建](https://github.com/mihail911/modern-software-dev-assignments/tree/master/week8)

**11/10 (周一):** 单个提示词生成端到端应用 - [幻灯片](https://docs.google.com/presentation/d/1GrVLsfMFIXMiGjIW9D7EJIyLYh_-3ReHHNd_vRfZUoo/edit?usp=sharing)

**11/14 (周五):** [Gaspar Garcia](https://www.linkedin.com/in/gaspargarcia/)，AI 研究主管 [Vercel](https://vercel.com/) - [幻灯片](https://docs.google.com/presentation/d/1Jf2aN5zIChd5tT86rZWWqY-iDWbxgR-uynKJxBR7E9E/edit?usp=sharing)

### 第九周：部署后的智能体

**主题**

- AI 系统的监控与可观测性
- 自动化事件响应
- 故障分类与调试

**阅读材料**

- [站点可靠性工程 (SRE) 简介](https://sre.google/sre-book/introduction/)
- [你需要了解的可观测性基础](https://last9.io/blog/traces-spans-observability-basics/)
- [使用 AI 进行 Kubernetes 故障排除](https://resolve.ai/blog/kubernetes-troubleshooting-in-resolve-ai)
- [你的新自主队友](https://resolve.ai/blog/product-deep-dive)
- [多智能体系统在打造 AI 原生软件工程师中的作用](https://resolve.ai/blog/role-of-multi-agent-systems-AI-native-engineering)
- [代理式 AI 在待命工程 (On-call) 中的益处](https://resolve.ai/blog/Top-5-Benefits)

**11/17 (周一):** 事件响应与 DevOps - [幻灯片](https://docs.google.com/presentation/d/1Mfe-auWAsg9URCujneKnHr0AbO8O-_U4QXBVOlO4qp0/edit?usp=sharing)

**11/21 (周五):** [Mayank Agarwal](https://www.linkedin.com/in/mayank-ag/)，CTO [Resolve](https://resolve.ai/)，以及 [Milind Ganjoo](https://www.linkedin.com/in/mganjoo/)，技术专员 [Resolve](https://resolve.ai/)- [幻灯片](https://drive.google.com/file/d/11WnEbMGc9kny_WBpMN10I8oP8XsiQOnM/view?usp=sharing)

### 第十周：AI 软件工程的未来

**主题**

- 软件开发角色的未来
- 新兴 AI 编码范式
- 行业趋势与预测

**12/1 (周一):** 10 年后的软件开发

**12/5 (周五):** [Martin Casado](https://a16z.com/author/martin-casado/)，普通合伙人 [a16z](https://a16z.com/)

## 评分标准

期末项目 80%

每周作业 15%

课堂参与 5%

CS146S: 现代软件开发者

# 相关项目资源



| 名称                         | 简要                                                         | 链接                                                         |
| ---------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Awesome Vibe Coding          |精选的Vibe Coding编程资源 | [link](https://github.com/filipecalegario/awesome-vibe-coding) |
|  CCSwitch                    | Claude Code 配置切换工具 | [link](https://github.com/farion1231/cc-switch  ) |
| Vibe Coding Workflow         |一些Vibe coding 模板资源 | [link](https://github.com/KhazP/vibe-coding-prompt-template) |
| Vibe Coding Skills官方仓库         |一些Vibe coding 模板资源 | [link](https://github.com/anthropics/skills)) |





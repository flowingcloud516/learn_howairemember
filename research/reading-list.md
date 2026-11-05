# 第一批待读论文

按下面顺序阅读，并为每篇建立一份论文卡片。

1. **MemGPT: Towards LLMs as Operating Systems**（2023）——分层上下文与记忆管理的基本直觉。
2. **Evaluating Very Long-Term Conversational Memory of LLM Agents / LoCoMo**（ACL 2024）——超长、多会话对话记忆的早期基准。
3. **LongMemEval: Benchmarking Chat Assistants on Long-Term Interactive Memory**（ICLR 2025）——索引、检索、阅读三阶段；时间、更新和拒答。
4. **Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory**（2025）——生产型长期记忆系统的工程路径。
5. **Memory for Autonomous LLM Agents: Mechanisms, Evaluation, and Emerging Frontiers**（2026 survey）——用于建立全局技术图谱。

## 必问问题

- 这项工作解决的到底是模型上下文、检索，还是长期记忆生命周期问题？
- 写路径与读路径各包含哪些算子和数据访问？
- 实验控制了哪些变量？模型和评测器是否会掩盖系统差异？
- 系统如何处理时间、冲突、删除、权限与来源证据？
- 哪一个假设值得用 trace 或原型进一步证伪？

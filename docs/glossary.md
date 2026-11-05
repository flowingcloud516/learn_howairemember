# 术语表

| 术语 | 简明定义 |
| --- | --- |
| LLM | 基于大规模文本训练、逐 token 生成内容的语言模型。 |
| Context window | 单次模型调用中可以输入/处理的上下文容量。 |
| KV Cache | Transformer 推理时缓存历史 token 的 attention key/value，用于避免重复计算；它不是 Agent 长期记忆。 |
| Embedding | 把文本或其他对象编码为向量，以便按语义相似度检索。 |
| RAG | 在生成前从外部资料中检索相关证据，再将其放入模型上下文。 |
| Agent | 能围绕目标进行多步推理、调用工具、保存状态并采取行动的 LLM 应用。 |
| Semantic memory | 相对稳定的事实和知识，例如用户偏好或知识三元组。 |
| Episodic memory | 带有时间和情境的过往事件/交互经历。 |
| Procedural memory | 指导系统行为的规则、策略和成功案例。 |
| Re-ranking | 对初步召回的候选项进行更精细的相关性排序。 |
| Write amplification | 写入一条信息导致索引、摘要或多副本更新的额外工作量。 |

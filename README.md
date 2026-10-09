# Hi, I'm XUAN 👋

欢迎来到我的主页喵～ฅ(•̀ω•́)ฅ<br>
这里记录着我在 LLM、Agent 和 AI 系统上的探索与实践，希望能带来一些有价值的思路～

<p align="center">
  <img src="https://github.com/user-attachments/assets/b918af02-525e-4a84-ae3a-d02cc271d439" alt="XUAN 的主页插画" width="400"/>
</p>

喜欢研究模型怎么学习、Agent 怎么做事，也喜欢把一个个小想法慢慢变成能运行的项目。<br>
下面挑了几只比较有代表性的“小作品”，欢迎点进去逛逛吖～🐾

---

## 🌷 先来看看这些小作品吧

### Plan-and-Execute-Agent

想让本地模型学会把任务拆开、调用工具，再根据结果调整下一步，于是就有了这个项目喵～

基于 **LangChain + Ollama + MCP**，实现任务规划、工具调用、失败恢复与重规划；还加入了工具名称与参数修正、Watchdog 和执行指标记录。一起看看小模型是怎么一步步完成任务的吧 ฅ(•̀ω•́)ฅ

🔗 [Plan-and-Execute-Agent](https://github.com/SAYURIqvq/Plan-and-Execute-Agent)

---

### Hierarchical-Multi-Agent-RAG-System

遇到复杂问题时，让负责规划、检索、生成和检查的 Agent 分工合作，一起从资料里寻找答案～

项目结合 **分层切块、向量检索、BM25、图检索与自反思流程**，探索如何组织检索证据、生成带引用的回答。很喜欢这种一边查资料、一边检查自己有没有答偏的小队协作感喵 📖

🔗 [Hierarchical-Multi-Agent-RAG-System](https://github.com/SAYURIqvq/Hierarchical-Multi-Agent-RAG-System)

---

### LLaMA-Factory_Qwen3-4B_QLoRA_QA_Evaluation

一次围绕中文医疗问答的领域微调实验，记录小模型学习专业知识的过程～

使用 **LLaMA-Factory + QLoRA** 微调 Qwen3-4B，围绕 Huatuo26M-Lite 数据集整理数据准备、训练、推理和答案评估流程。除了观察模型学到了什么，也想认真看看它在哪些问题上还会犯迷糊吖～🔎

🔗 [LLaMA-Factory_Qwen3-4B_QLoRA_QA_Evaluation](https://github.com/SAYURIqvq/LLaMA-Factory_Qwen3-4B_QLoRA_QA_Evaluation)

---

### LLM-Training-Pipeline

对模型从“开始学习”到“学会按要求回答”的过程很好奇，所以把不同训练阶段放进了同一个实验项目里喵～

整理了 **预训练、SFT、DPO / PPO / GRPO 与多模态训练**的代码，也探索 DeepSpeed、FlashAttention 和混合精度等训练技术。希望沿着数据、模型和优化过程，把训练这件事一点点弄明白 (ง •̀_•́)ง

🔗 [LLM-Training-Pipeline](https://github.com/SAYURIqvq/LLM-Training-Pipeline)

---

### LangChain4j-Agent

也想把 Agent 接进熟悉的后端服务里，让知识问答、会话记忆和工具调用一起工作～

基于 **Java + Spring Boot + LangChain4j**，整合 RAG、MCP 工具、Redis 会话记忆和流式对话，探索从模型能力到应用服务的连接方式。喜欢 Java 和 AI 应用的小伙伴，可以来这里坐坐吖 ☕

🔗 [LangChain4j-Agent](https://github.com/SAYURIqvq/LangChain4j-Agent)

---

### Mini-LLM-Engine

模型是怎么一个 token、一个 token 地把回答写出来的呢？这个项目就是我的推理引擎拆解笔记喵～

使用 **Python + PyTorch** 实现逐 token 解码、请求队列调度、每请求 KV 缓存和 top-p 采样，并提供 FastAPI 接口。跟着代码看看 prefill、decode 和请求状态如何配合，把推理过程里的小齿轮一个个认清楚 ⚙️

🔗 [Mini-LLM-Engine](https://github.com/SAYURIqvq/Mini-LLM-Engine)

---

## 🌱 还有一个小小实验角

最近也在琢磨：Agent 做长任务时，换了上下文窗口，要怎么记得自己做到哪一步了呢？

[**agent-state-cutover**](https://github.com/SAYURIqvq/agent-state-cutover) 是围绕这个问题的轻量原型，用 **State、Note、Archive 和 Checkpoint** 保存任务状态、工作笔记与原始记录，再通过状态补丁校验来更新事实。希望小助手换了工作台，也能接着把事情做好呀～🐾

更多探索还放在 [我的仓库列表](https://github.com/SAYURIqvq?tab=repositories) 里，欢迎慢慢翻一翻～

---

## 🐾 一点点兴趣方向

- 🐱 Agent 系统、多智能体协作与长程任务记忆
- 🧪 LLM 训练、微调与对齐
- 📚 RAG、知识检索与回答质量评估
- ⚙️ 推理引擎、模型服务与工程实践
- 🌱 让 AI 系统一点点变得更可靠、更好用

---

## 📫 来找我玩呀

- WeChat：LittileBlackCats
- WhatsApp：[点这里来打个招呼～](https://wa.me/60178374097)

欢迎交流项目、讨论想法，也欢迎指出代码里还可以改进的地方喵～

---

## 🌙 小小的想法

> 希望能做出既聪明又可靠的 AI 系统喵 (ฅ´ω`ฅ)<br>
> 一边学习，一边动手，把好奇心慢慢变成能运行的小作品。<br>
> 希望可以和你们成为很好的技术上的朋友吖！！！！

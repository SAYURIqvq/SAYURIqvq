# Hi, I'm XUAN 👋

欢迎来到我的主页喵～ฅ(•̀ω•́)ฅ  
这里记录着我在 LLM、Agent 和 AI 系统上的探索与实践，希望能带来一些有价值的思路～

<p align="center">
  <img src="https://github.com/user-attachments/assets/b918af02-525e-4a84-ae3a-d02cc271d439" width="400"/>
</p>

---

## 项目精选

### 🐱 智能体系统（Agent Systems）

#### 🔹  Plan-and-Execute Agent —— 本地自主执行系统  
一个模块化 LLM Agent 系统，支持多步骤任务的规划、执行与重规划。  
基于 MCP 集成 filesystem、shell、websearch、sqlite 等工具，实现真实环境下的任务执行。  
引入工具调用修正机制（名称、参数、内容）以及 Watchdog 与执行指标（TCA、ArgFit、StepCR），提升系统稳定性与可靠性。

🔗 项目链接：https://github.com/SAYURIqvq/Plan-and-Execute-Agent

---

#### 🔹  ReAct + Plan-and-Solve + Self-Reflection Agent  
融合 ReAct 推理、结构化规划与自反思机制的混合智能体系统。  
用于提升多步骤推理任务中的一致性，并降低错误累积问题。

🔗 项目链接：https://github.com/SAYURIqvq/ReAct_Plan-and-solve_Self-Reflection_Agent

---

### 🐶 模型训练与微调（LLM Training & Fine-tuning）

#### 🔹  LLM Training Pipeline —— 完整训练系统  
覆盖预训练、监督微调（SFT）与对齐（DPO / PPO / GRPO）的完整 LLM 训练流程。  
基于 DeepSpeed、FlashAttention 与混合精度（FP8）构建，支持高效可扩展训练。

🔗 项目链接：https://github.com/SAYURIqvq/LLM-Training-Pipeline

---

#### 🔹  Qwen3-4B 医疗领域微调（QLoRA）  
基于 LLaMA-Factory 与 QLoRA 对 Qwen3-4B 进行领域微调。  
使用中文医疗问答数据集，提升模型在医疗场景下的知识理解与回答质量。

🔗 项目链接：https://github.com/SAYURIqvq/LLaMA-Factory_Qwen3-4B_QLoRA_QA_Evaluation

---

---

### 📚 RAG 与知识系统

#### 🔹  Hierarchical Multi-Agent RAG System

一个分层式多智能体 RAG 系统，结合 GraphRAG 与自反思机制。

通过多策略检索（向量检索、关键词检索、图检索）与多 Agent 协作，提高复杂知识问答任务中的准确性与稳定性。

🔗 项目链接：https://github.com/SAYURIqvq/Hierarchical-Multi-Agent-RAG-System

---

#### 🔹  Automotive RAG QA System

面向垂直领域（汽车知识）的问答系统。

结合检索优化与生成策略，在专业知识场景中提升回答质量与一致性。

🔗 项目链接：https://github.com/SAYURIqvq/RAG-Automotive-QA-System

---

### 🧠 多模态 AI

#### 🔹  Medical VQA System

一个面向医疗影像的视觉问答系统。

基于 CNN + BERT 与 BLIP 架构，并结合 Grad-CAM 实现模型可解释性，用于辅助医疗图像理解。

🔗 项目链接：https://github.com/SAYURIqvq/MED_VQA-main

---

### ⚙️ 系统与部署

#### 🔹  Mini LLM Engine

一个基于 PyTorch 从零实现的轻量级推理引擎。

支持 continuous batching、paged KV cache 与 INT8 量化，并与 vLLM 进行性能对比。

🔗 项目链接：https://github.com/SAYURIqvq/Mini-LLM-Engine

---

#### 🔹  vLLM FastAPI Serving（Qwen2-7B）

基于 vLLM 与 FastAPI 构建的高性能推理服务系统。

支持流式输出与高并发部署，适用于实际应用场景。

🔗 项目链接：https://github.com/SAYURIqvq/vLLM-FastApi-Qwen2_7B_Instruct

---

## 🐾 一点点兴趣方向

- Agent 系统与多智能体协作喵  
- LLM 训练、微调与对齐  
- RAG 与知识驱动 AI  
- 更可靠、更稳定的 AI 系统设计  
- 面向真实世界约束的工程实践  

---

## 📫 联系方式

- WeChat：LittileBlackCats  - WhatsApp：https://wa.me/60178374097  

---

## 🌙 小小的想法

> 希望能做出既聪明又可靠的 AI 系统喵 (ฅ´ω`ฅ)
> 希望可以和你们成为很好的技术上的朋友吖！！！！！

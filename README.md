# Hi, I'm XUAN 👋

欢迎来到我的主页喵～ฅ(•̀ω•́)ฅ  
这里记录着我在 LLM、Agent 和 AI 系统上的探索与实践，希望能带来一些有价值的思路～

<p align="center">
  <img src="https://github.com/user-attachments/assets/b918af02-525e-4a84-ae3a-d02cc271d439" width="400"/>
</p>

---

## 项目精选

### 智能体系统（Agent Systems）

#### Plan-and-Execute Agent —— 本地自主执行系统  
一个模块化 LLM Agent 系统，支持多步骤任务的规划、执行与重规划。  
基于 MCP 集成 filesystem、shell、websearch、sqlite 等工具，实现真实环境下的任务执行。  
引入工具调用修正机制（名称、参数、内容）以及 Watchdog 与执行指标（TCA、ArgFit、StepCR），提升系统稳定性与可靠性。

🔗 项目链接：https://github.com/SAYURIqvq/Plan-and-Execute-Agent

---

#### ReAct + Plan-and-Solve + Self-Reflection Agent  
融合 ReAct 推理、结构化规划与自反思机制的混合智能体系统。  
用于提升多步骤推理任务中的一致性，并降低错误累积问题。

🔗 项目链接：https://github.com/SAYURIqvq/ReAct_Plan-and-solve_Self-Reflection_Agent

---

### 模型训练与微调（LLM Training & Fine-tuning）

#### LLM Training Pipeline —— 完整训练系统  
覆盖预训练、监督微调（SFT）与对齐（DPO / PPO / GRPO）的完整 LLM 训练流程。  
基于 DeepSpeed、FlashAttention 与混合精度（FP8）构建，支持高效可扩展训练。

🔗 项目链接：https://github.com/SAYURIqvq/LLM-Training-Pipeline

---

#### Qwen3-4B 医疗领域微调（QLoRA）  
基于 LLaMA-Factory 与 QLoRA 对 Qwen3-4B 进行领域微调。  
使用中文医疗问答数据集，提升模型在医疗场景下的知识理解与回答质量。

🔗 项目链接：https://github.com/SAYURIqvq/LLaMA-Factory_Qwen3-4B_QLoRA_QA_Evaluation

## 张予嘉/ Yujia Zhang

约翰霍普金斯大学计算机科学硕士(预计 2026 年 12 月毕业)。
MS in Computer Science, Johns Hopkins University (Dec 2026).

**[vision-robustness-toolkit](https://github.com/z8ri/vision-robustness-toolkit)** — 工业质检场景下的抗干扰图像分类:物理退化协议、小波域样本自适应注意力模块、按切片划分的鲁棒性评估、校准后的选择性预测、ONNX 导出。PyTorch,198 个纯 CPU 测试。
Corruption-robust industrial defect classification: physical degradation protocol, wavelet-domain sample-adaptive attention, slice-based robustness evaluation, calibrated selective prediction, ONNX export. PyTorch, 198 CPU-only tests.

**[job-intelligence-agent](https://github.com/z8ri/job-intelligence-agent)** — 基于 LangGraph 的求职搜索 Agent:按查询自适应的检索策略(BM25 / Dense / RRF 融合)、LLM 精排、规则验证器、跨轮偏好记忆。Python,MySQL,OpenAI API。
LangGraph job-search agent: per-query retrieval planning (BM25 / dense / RRF), LLM reranking, rule-based verification, cross-turn preference memory. Python, MySQL, OpenAI API.

**[mcp-multi-tool-agent](https://github.com/z8ri/mcp-multi-tool-agent)** — 一个从零手写的 LangGraph 状态图驱动的多工具 ReAct Agent:带熔断器和健康检查的 MCP 工具网关、通过 `interrupt()` 实现的真实人工确认暂停/恢复、SQLite 持久化会话。FastAPI,Vue3,LangGraph。
Multi-tool ReAct agent on a hand-written LangGraph state machine: MCP tool gateway with per-server circuit breakers and health checks, human-in-the-loop pause/resume via `interrupt()`, SQLite-backed session persistence. FastAPI, Vue3, LangGraph.

**[agent-regression-bench](https://github.com/z8ri/agent-regression-bench)** — 每晚自动运行的 Agent 工具调用回归基准:30 道任务跑在 5 个沙箱化 MCP 工具上,确定性规则打分 + 一个边界卡得很窄的 LLM judge,通过 OpenRouter 横跨 5 个模型。LangChain agents,GitHub Actions。
Nightly regression benchmark for agent tool-calling: 30 tasks on 5 sandboxed MCP tools, deterministic rule-based scoring plus a narrowly-scoped LLM judge, run across 5 models via OpenRouter. LangChain agents, GitHub Actions.

本科计算机科学,华东理工大学。
BS in CS, ECUST.

### 👋 Hi, I'm Wang Zhongyou

Agent Infra 工程师，构建 AI 编程助手与智能体基础设施。

- 🔭 项目方向：AI 编程助手 · AI 阅读器 · LLM 网关 · 工作流引擎 · Agent 沙箱 · 向量数据库 · 全文搜索 · 网络爬虫
- 🧰 技术栈：Go · LLM 集成 · 分布式系统

---

### 📌 精选项目

#### Agent 应用

| 项目 | 简介 |
| :--- | :--- |
| **[baize](https://github.com/wzhongyou/baize)** | Baize（白泽）— AI 编程 Agent，本地运行，帮你写代码、读代码、跑命令。 |
| **[gewu](https://github.com/wzhongyou/gewu)** | Gewu（格物）— AI 阅读器浏览器插件，已上架 Chrome 商店。支持网页/PDF 原地翻译 + Side Panel 对话问答，v0.2。 |

#### Agent Infra

通用 Agent 基础设施模块，可独立使用也可组合嵌入。

| 项目 | 简介 |
| :--- | :--- |
| **[llmgate](https://github.com/wzhongyou/llmgate)** | Go 实现的高性能 LLM 网关 — 统一接入 20+ 模型服务商，内置自动降级、流量控制与调试工具。Go SDK / HTTP Gateway / Web Console 三种使用方式，支持 function calling 与成本感知路由。 |
| **[carrel](https://github.com/wzhongyou/carrel)** | Go 实现的轻量级 AI Agent 安全沙箱运行时，为智能体提供隔离执行环境。 |
| **[weave](https://github.com/wzhongyou/weave)** | Go 原生通用图执行引擎 — 服务编排、工作流、ETL 管道的轻量级库，节点+边+状态机模型，内置熔断、重试、超时、舱壁等弹性保障，零外部依赖，单二进制部署，嵌入即用。 |

#### 数据基础设施

| 项目 | 简介 |
| :--- | :--- |
| **[flux](https://github.com/wzhongyou/flux)** | C++17 轻量级向量数据库召回引擎 — 自研 HNSW / IVF / BM25 混合检索，单二进制部署，HTTP API 即开即用。 |
| **[vortex](https://github.com/wzhongyou/vortex)** | C++17 高性能倒排索引（全文搜索）引擎 — 轻量嵌入库，FST 字典、SIMD-BP128 压缩、RCU 快照隔离，零拷贝读取。 |
| **[kuafu](https://github.com/wzhongyou/kuafu)** | Python 轻量、易扩展的工业级网络爬虫引擎，支持分布式抓取与插件式反反爬策略。 |

---

*为智能体时代构建更好的基础设施。*

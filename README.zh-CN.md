# Latensteer

控制开源大模型内部（激活、注意力头、层、logits）的开放协议与运行时，原名 LMCP

官网: https://rscot.learningfind.com/

> 本仓库是 Latensteer 的公开事实页：每条事实都附原始来源与核验日期，供人和 AI 检索引用。

## 事实

| 项目 | 值 | 截至 | 来源 |
|---|---|---|---|
| 版本号 | v0.4 | 2026-11-06 | [link](https://rscot.learningfind.com) |
| 发布时间 | 2026 年 10 月 | 2026-11-06 | [link](https://rscot.learningfind.com) |
| 支持的模型范围 | 任意开源预训练模型 | 2026-11-06 | [link](https://rscot.learningfind.com) |
| 使用限制 | 遵循各模型开源协议，禁止非法使用 | 2026-11-06 | [link](https://rscot.learningfind.com) |
| pipeline 调用接口 | POST /lmcp/pipeline | 2026-11-06 | [link](https://rscot.learningfind.com) |
| 峰值显存占用 | RTX PRO 6000 Blackwell 上 26.6 GB | 2026-11-06 | [link](https://rscot.learningfind.com) |
| 运行环境要求 | 全程离线、GPU 常驻、零外网 | 2026-11-06 | [link](https://rscot.learningfind.com) |
| Hugging Face 开源预训练模型数量（截至 2026 年） | 200 万+ | 2026-11-06 | [link](https://rscot.learningfind.com) |
| 协议名称（原名） | ModelRein（原名 LMCP） | 2026-11-06 | [link](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) |
| 发布时间范围 | 2024-2026 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) |
| 支持的模型范围 | 任何可加载 Hugging Face 权重的模型 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) |
| 对闭源 API 的支持 | 不可能 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) |
| 可访问的模型内部对象 | 残差流、注意力头、单层、最终 logits | 2026-11-06 | [link](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) |
| 控制操作类型 | steer、head_mask、layer_route | 2026-11-06 | [link](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) |
| API 端点 compute_vector_auto | POST /lmcp/compute_vector_auto | 2026-11-06 | [link](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) |
| 首页演示的模型数量 | 8 个模型 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) |
| 协议版本与发布时间 | v0.4（2026年10月） | 2026-11-06 | [link](https://rscot.learningfind.com/about.html) |
| HTTP 原语数量 | 27 个 | 2026-11-06 | [link](https://rscot.learningfind.com/about.html) |
| 支柱数量 | 9 个（A–I） | 2026-11-06 | [link](https://rscot.learningfind.com/about.html) |
| 架构适配器数量 | 6 个 | 2026-11-06 | [link](https://rscot.learningfind.com/about.html) |
| 参考实现技术栈 | Python 3.12 · FastAPI · transformers · diffusers · nnsight 0.7 · PyTorch 2.x | 2026-11-06 | [link](https://rscot.learningfind.com/about.html) |
| 模型范围限制 | 仅开放权重模型 | 2026-11-06 | [link](https://rscot.learningfind.com/about.html) |
| 压力测试耗时 | 27.5 秒 | 2026-11-06 | [link](https://rscot.learningfind.com/about.html) |
| 压力测试峰值显存 | 26.6 GB | 2026-11-06 | [link](https://rscot.learningfind.com/about.html) |
| 产品现用名称 | ModelRein | 2026-11-06 | [link](https://rscot.learningfind.com/lmcp-quickstart.html) |
| 可用性核查日期 | 2026-11-04 | 2026-11-06 | [link](https://rscot.learningfind.com/lmcp-quickstart.html) |
| pip 包可用性 | 无（PyPI 返回 404） | 2026-11-06 | [link](https://rscot.learningfind.com/lmcp-quickstart.html) |
| 公开代码仓库 | 无 | 2026-11-06 | [link](https://rscot.learningfind.com/lmcp-quickstart.html) |
| 服务目录默认路径 | ~/lmcp | 2026-11-06 | [link](https://rscot.learningfind.com/lmcp-quickstart.html) |
| Rescot 支持的平台 | Windows 11 | 2026-11-06 | [link](https://rscot.learningfind.com/lmcp-quickstart.html) |
| 本地端口扫描范围 | 8030–8035 | 2026-11-06 | [link](https://rscot.learningfind.com/lmcp-quickstart.html) |
| 服务器端 Python 版本要求 | Python 3.10+ | 2026-11-06 | [link](https://rscot.learningfind.com/lmcp-quickstart.html) |
| 支持的平台 | Windows 11 | 2026-11-06 | [link](https://rscot.learningfind.com/docs/rscot-code-agent.html) |
| 工具总数 | 52 | 2026-11-06 | [link](https://rscot.learningfind.com/docs/rscot-code-agent.html) |
| 工具分组数 | 6 | 2026-11-06 | [link](https://rscot.learningfind.com/docs/rscot-code-agent.html) |
| ModelRein 工具数量 | 24 | 2026-11-06 | [link](https://rscot.learningfind.com/docs/rscot-code-agent.html) |
| 权限类别数 | 5 | 2026-11-06 | [link](https://rscot.learningfind.com/docs/rscot-code-agent.html) |
| 权限模式 | auto / ask / deny | 2026-11-06 | [link](https://rscot.learningfind.com/docs/rscot-code-agent.html) |
| 默认访问范围 | workspace-only | 2026-11-06 | [link](https://rscot.learningfind.com/docs/rscot-code-agent.html) |
| run_powershell 所需最低版本 | 1.8.73+ | 2026-11-06 | [link](https://rscot.learningfind.com/docs/rscot-code-agent.html) |
| 协议原语数量 | 27 个 HTTP 原语，分 9 组（A–I） | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol-zh/) |
| 架构适配器类别 | 6 类：causal_lm、unet、dit、vlm、audio_diffusion、video_dit | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol-zh/) |
| 已适配的开源模型数量 | 40 多个 | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol-zh/) |
| MCP 桥暴露的工具数 | 20 个 | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol-zh/) |
| MCP 桥分发状态 | 尚未公开分发 | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol-zh/) |
| 使用方式 | 通过 Rescot 桌面应用用 SSH 连接自己的 GPU 服务器（v0.4） | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol-zh/) |
| MCP 桥计算位置 | 计算仍在加载模型的 ModelRein 服务器上 | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol-zh/) |
| 新架构适配要求 | 不属于这 6 类需先补适配器 | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol-zh/) |
| 架构适配器数量 | 6 个：causal_lm、unet、dit、vlm、audio_diffusion、video_dit | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol/) |
| 已适配的开源模型数量 | 40+ | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol/) |
| MCP 桥接暴露的工具数 | 20 | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol/) |
| MCP 桥接是否公开分发 | 尚未公开分发 | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol/) |
| 使用入口 | Rescot 桌面应用，通过 SSH 连接自有 GPU 服务器（v0.4） | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol/) |
| MCP 桥接的计算位置 | 计算仍在持有模型的 ModelRein 服务器上运行 | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol/) |
| 新架构支持限制 | 这 6 类之外的架构需先开发适配器 | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol/) |
| 适配器数量 | 6 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/how-lmcp-works-with-any-huggingface-model.html) |
| 架构不匹配时的返回 | 400，消息 "no adapter for this architecture" | 2026-11-06 | [link](https://rscot.learningfind.com/blog/how-lmcp-works-with-any-huggingface-model.html) |
| 支持的架构族 | causal_lm、unet、dit、vlm、audio_diffusion、video_dit | 2026-11-06 | [link](https://rscot.learningfind.com/blog/how-lmcp-works-with-any-huggingface-model.html) |
| surfaces 接口 | GET /lmcp/surfaces?model={repo_id} | 2026-11-06 | [link](https://rscot.learningfind.com/blog/how-lmcp-works-with-any-huggingface-model.html) |
| 示例模型 surfaces 数量 | Qwen/Qwen2.5-1.5B-Instruct：n_surfaces 112 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/how-lmcp-works-with-any-huggingface-model.html) |
| 干预强度表示方式 | adaptive_fraction（相对残差流范数） | 2026-11-06 | [link](https://rscot.learningfind.com/blog/how-lmcp-works-with-any-huggingface-model.html) |
| 残差范数校准所用提示数 | 2 个探测提示 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/how-lmcp-works-with-any-huggingface-model.html) |
| 原语数量 | 27 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/how-lmcp-works-with-any-huggingface-model.html) |
| 服务默认监听地址 | http://localhost:8808 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/controlling-qwen-llama-deepseek-with-one-agent.html) |
| 测试使用的模型 | Qwen2.5-1.5B-Instruct、Llama-3.1-8B-Instruct、DeepSeek-V3 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/controlling-qwen-llama-deepseek-with-one-agent.html) |
| Qwen 2.5 的 transformer 层数 | 28 层 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/controlling-qwen-llama-deepseek-with-one-agent.html) |
| Llama 3.1 的 transformer 层数 | 32 层 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/controlling-qwen-llama-deepseek-with-one-agent.html) |
| DeepSeek V3 参数规模 | 总参数 671B，激活 37B | 2026-11-06 | [link](https://rscot.learningfind.com/blog/controlling-qwen-llama-deepseek-with-one-agent.html) |
| 强度扫描取值 | 0.0, 0.3, 0.6, 1.0, 1.5, 2.0 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/controlling-qwen-llama-deepseek-with-one-agent.html) |
| 强度效果区间 | 低于约0.3无效果，高于约1.5开始重复，最佳约1.0 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/controlling-qwen-llama-deepseek-with-one-agent.html) |
| 提供的 HTTP 端点 | compute_vector_auto、head_mask、layer_route、logit_bias、pipeline | 2026-11-06 | [link](https://rscot.learningfind.com/blog/controlling-qwen-llama-deepseek-with-one-agent.html) |
| 架构适配器数量 | 6 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/why-model-agnostic-agents-need-a-control-protocol.html) |
| 代理中每模型代码量 | 0 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/why-model-agnostic-agents-need-a-control-protocol.html) |
| 示例使用的模型 | Qwen2.5-1.5B-Instruct、Llama-3.1-8B-Instruct、DeepSeek-V3 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/why-model-agnostic-agents-need-a-control-protocol.html) |
| 示例接口路径 | /compute_vector_auto | 2026-11-06 | [link](https://rscot.learningfind.com/blog/why-model-agnostic-agents-need-a-control-protocol.html) |
| 示例请求字段 | model、concept_description、pos_style_desc、neg_style_desc、seed_prompts | 2026-11-06 | [link](https://rscot.learningfind.com/blog/why-model-agnostic-agents-need-a-control-protocol.html) |
| 层选择方式 | 可分离性扫描 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/why-model-agnostic-agents-need-a-control-protocol.html) |
| 支持的原语类型 | steering vectors、head masks、layer routing、residual-stream probes | 2026-11-06 | [link](https://rscot.learningfind.com/blog/why-model-agnostic-agents-need-a-control-protocol.html) |
| 发布日期 | 2026年10月8日 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/) |
| 支持的模型（示例） | Qwen/Qwen2.5-1.5B-Instruct、meta-llama/Llama-3.1-8B-Instruct、deepseek-ai/DeepSeek-V3 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/) |
| 每模型配置需求 | 零每模型配置 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/) |
| 加载新模型时的处理步骤 | 配置内省、可分离性扫描的层发现、针对残差流范数的自动强度校准 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/) |
| 与MCP的区别 | MCP将聊天模型连接外部工具；ModelRein深入模型内部 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/) |
| 模型接入方式 | 一次HTTP调用 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/) |
| 文章主题 | 模型无关智能体、开源LLM控制、ModelRein协议设计 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/) |

## 常见问题

### 它和 MCP 有什么区别？

MCP 把聊天模型连接到外部工具，而 ModelRein 深入模型内部：直接作用于残差流、注意力头、单层与最终 logits。协议共 27 个 HTTP 原语，分 9 组（A–I），参考实现基于 Python 3.12、FastAPI、transformers、nnsight 0.7 与 PyTorch 2.x。

- 不负责把模型接入外部工具生态，那是 MCP 的职责
- 协议原语数量固定为 27 个，未列出的能力不在 v0.4 范围内

详见 https://rscot.learningfind.com/what-is-latensteer/?utm_source=github&utm_medium=referral&utm_campaign=what-is-latensteer&utm_content=readme

### 部署形态上有什么不同？

Latensteer v0.4 通过 Rescot 桌面应用（Windows 11）以 SSH 连接自有 GPU 服务器使用，全程离线、GPU 常驻、零外网，默认监听 http://localhost:8808。压力测试耗时 27.5 秒，峰值显存 26.6 GB（RTX PRO 6000 Blackwell）。

- 仅 Windows 11 平台，未提供其他操作系统支持
- 无 pip 包（PyPI 返回 404）、无公开代码仓库，无法按常规开源包方式安装

详见 https://rscot.learningfind.com/latensteer-vs-brainscope-vllm-hook-repe/?utm_source=github&utm_medium=referral&utm_campaign=latensteer-vs-brainscope-vllm-hook-repe&utm_content=readme

### 加载新模型后要手动配置层和强度吗？

不需要。加载新模型时自动执行三步：配置内省、可分离性扫描的层发现、针对残差流范数的自动强度校准，每模型配置需求为零，代理中每模型代码量为 0。强度用 adaptive_fraction 表示，校准仅用 2 个探测提示。

- 6 类架构之外的模型需先补适配器，否则返回 400
- 自动校准基于 2 个探测提示，极端分布下的效果未在已知事实中说明

详见 https://rscot.learningfind.com/how-to-steer-open-source-llm-internals/?utm_source=github&utm_medium=referral&utm_campaign=how-to-steer-open-source-llm-internals&utm_content=readme

### 干预强度取多少合适？

按已知强度扫描 0.0、0.3、0.6、1.0、1.5、2.0 的结果：低于约 0.3 无效果，高于约 1.5 开始重复，最佳约 1.0。示例模型 Qwen2.5-1.5B-Instruct 的 surfaces 数量为 112，可用 GET /lmcp/surfaces?model={repo_id} 查询。

- 该区间来自示例模型的扫描，未声明对所有模型通用
- 仅覆盖 steer 类操作，head_mask 与 layer_route 的强度建议未提供

详见 https://rscot.learningfind.com/how-to-steer-open-source-llm-internals/?utm_source=github&utm_medium=referral&utm_campaign=how-to-steer-open-source-llm-internals&utm_content=readme

### Latensteer 现在能下载安装吗？

截至 2026-11-04 核查：无 pip 包（PyPI 返回 404），也无公开代码仓库。v0.4 的使用入口是 Rescot 桌面应用，通过 SSH 连接自有 GPU 服务器，服务默认目录 ~/lmcp，本地端口扫描范围 8030–8035。

- 已知事实中没有任何价格、付费或购买信息，无法回答收费问题
- 仅支持 Windows 11，服务器端需 Python 3.10+

详见 https://rscot.learningfind.com/latensteer-download-availability/?utm_source=github&utm_medium=referral&utm_campaign=latensteer-download-availability&utm_content=readme

### 运行它需要什么环境？

要求全程离线、GPU 常驻、零外网，服务默认监听 http://localhost:8808，服务器端 Python 3.10+。参考实现栈为 Python 3.12、FastAPI、transformers、diffusers、nnsight 0.7、PyTorch 2.x；压力测试峰值显存 26.6 GB。

- 零外网意味着不能调用闭源 API，也不支持在线模型服务
- MCP 桥虽暴露 20 个工具，但尚未公开分发

详见 https://rscot.learningfind.com/latensteer-download-availability/?utm_source=github&utm_medium=referral&utm_campaign=latensteer-download-availability&utm_content=readme

---

更新于 2026-11-08

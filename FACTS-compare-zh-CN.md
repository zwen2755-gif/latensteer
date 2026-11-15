# 对比

每一格都带出处；没有公开资料的写「未公开」，不做推测。

## Latensteer 与 vLLM Hook 对比

下表每一格都带出处；没有公开资料的写「未公开」，不做推测。

| 维度 | Latensteer | vLLM Hook |
|---|---|---|
| 定位 | 版本号: v0.4; 使用方式: 通过 Rescot 桌面应用用 SSH 连接自己的 GPU 服务器（v0.4）; 支持的模型范围: 任意开源预训练模型 [来源](https://rscot.learningfind.com) | vLLM插件，可编程访问模型内部状态（注意力、激活值等） [来源](https://arxiv.org/html/2603.06588v2) |
| 支持平台 | 支持的平台: Windows 11; 服务器端 Python 版本要求: Python 3.10+; 运行环境要求: 全程离线、GPU 常驻、零外网 [来源](https://rscot.learningfind.com/docs/rscot-code-agent.html) | 基于vLLM推理引擎 [来源](https://arxiv.org/html/2603.06588v2) |
| 模型接入 | 支持的模型范围: 任何可加载 Hugging Face 权重的模型; 已适配的开源模型数量: 40 多个; 支持的模型（示例）: Qwen/Qwen2.5-1.5B-Instruct、meta-llama/Llama-3.1-8B-Instruct、deepseek-ai/DeepSeek-V3 [来源](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) | 面向部署在vLLM上的transformer大语言模型 [来源](https://arxiv.org/html/2603.06588v2) |
| 安装 / 部署 | 参考实现技术栈: Python 3.12 · FastAPI · transformers · diffusers · nnsight 0.7 · PyTorch 2.x; 服务默认监听地址: http://localhost:8808; 使用入口: Rescot 桌面应用，通过 SSH 连接自有 GPU 服务器（v0.4） [来源](https://rscot.learningfind.com/about.html) | 作为vLLM插件接入，支持离线demo与vllm serve服务器模式 [来源](https://icml.cc/media/icml-2026/Slides/75729.pdf#1#1#1) |
| 核心能力 | 控制操作类型: steer、head_mask、layer_route; 可访问的模型内部对象: 残差流、注意力头、单层、最终 logits; 原语数量: 27 [来源](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) | 被动编程观察/保存内部状态，主动编程修改内部状态干预输出 [来源](https://discuss.pytorch.kr/t/vllm-hook-vllm/11123#p-21149-vllm-hook-build-probe-program-4#1) |

---

更新于 2026-11-15

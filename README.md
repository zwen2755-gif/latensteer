# Latensteer

控制开源大模型内部（激活、注意力头、层、logits）的开放协议与运行时，原名 LMCP

Official site: https://rscot.learningfind.com/

> Public fact sheet for Latensteer. Every fact links to its primary source and the date it was checked.

## Facts

| Fact | Value | As of | Source |
|---|---|---|---|
| Version | v0.4 | 2026-11-06 | [link](https://rscot.learningfind.com) |
| Release date | October 2026 | 2026-11-06 | [link](https://rscot.learningfind.com) |
| Supported model scope | Any open-source pretrained model | 2026-11-06 | [link](https://rscot.learningfind.com) |
| Usage restriction | Follow each model's license; no illegal use | 2026-11-06 | [link](https://rscot.learningfind.com) |
| Pipeline endpoint | POST /lmcp/pipeline | 2026-11-06 | [link](https://rscot.learningfind.com) |
| Peak VRAM usage | 26.6 GB on RTX PRO 6000 Blackwell | 2026-11-06 | [link](https://rscot.learningfind.com) |
| Runtime requirement | Fully offline, GPU-resident, zero external network | 2026-11-06 | [link](https://rscot.learningfind.com) |
| Open-source pretrained models on Hugging Face as of 2026 | 2+ million | 2026-11-06 | [link](https://rscot.learningfind.com) |
| Protocol name (formerly) | ModelRein (formerly LMCP) | 2026-11-06 | [link](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) |
| Publication timeframe | 2024-2026 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) |
| Supported model scope | Any model with loadable Hugging Face weights | 2026-11-06 | [link](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) |
| Support for closed APIs | Impossible | 2026-11-06 | [link](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) |
| Accessible model internals | Residual stream, attention heads, individual layers, final logits | 2026-11-06 | [link](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) |
| Control operations | steer, head_mask, layer_route | 2026-11-06 | [link](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) |
| API endpoint compute_vector_auto | POST /lmcp/compute_vector_auto | 2026-11-06 | [link](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) |
| Number of models in front-page demo | 8 models | 2026-11-06 | [link](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) |
| Spec version and release date | v0.4 (October 2026) | 2026-11-06 | [link](https://rscot.learningfind.com/about.html) |
| Number of HTTP primitives | 27 | 2026-11-06 | [link](https://rscot.learningfind.com/about.html) |
| Number of pillars | 9 (A–I) | 2026-11-06 | [link](https://rscot.learningfind.com/about.html) |
| Number of architecture adapters | 6 | 2026-11-06 | [link](https://rscot.learningfind.com/about.html) |
| Reference implementation stack | Python 3.12 · FastAPI · transformers · diffusers · nnsight 0.7 · PyTorch 2.x | 2026-11-06 | [link](https://rscot.learningfind.com/about.html) |
| Model scope restriction | Open-weight only | 2026-11-06 | [link](https://rscot.learningfind.com/about.html) |
| Stress test wall clock | 27.5s | 2026-11-06 | [link](https://rscot.learningfind.com/about.html) |
| Stress test peak VRAM | 26.6 GB | 2026-11-06 | [link](https://rscot.learningfind.com/about.html) |
| Current product name | ModelRein | 2026-11-06 | [link](https://rscot.learningfind.com/lmcp-quickstart.html) |
| Availability checked date | 2026-11-04 | 2026-11-06 | [link](https://rscot.learningfind.com/lmcp-quickstart.html) |
| pip package availability | None (PyPI returns 404) | 2026-11-06 | [link](https://rscot.learningfind.com/lmcp-quickstart.html) |
| Public code repository | None | 2026-11-06 | [link](https://rscot.learningfind.com/lmcp-quickstart.html) |
| Default service directory | ~/lmcp | 2026-11-06 | [link](https://rscot.learningfind.com/lmcp-quickstart.html) |
| Rescot supported platform | Windows 11 | 2026-11-06 | [link](https://rscot.learningfind.com/lmcp-quickstart.html) |
| Local port scan range | 8030–8035 | 2026-11-06 | [link](https://rscot.learningfind.com/lmcp-quickstart.html) |
| Server-side Python version requirement | Python 3.10+ | 2026-11-06 | [link](https://rscot.learningfind.com/lmcp-quickstart.html) |
| Supported platform | Windows 11 | 2026-11-06 | [link](https://rscot.learningfind.com/docs/rscot-code-agent.html) |
| Total number of tools | 52 | 2026-11-06 | [link](https://rscot.learningfind.com/docs/rscot-code-agent.html) |
| Number of tool families | 6 | 2026-11-06 | [link](https://rscot.learningfind.com/docs/rscot-code-agent.html) |
| Number of ModelRein tools | 24 | 2026-11-06 | [link](https://rscot.learningfind.com/docs/rscot-code-agent.html) |
| Number of permission categories | 5 | 2026-11-06 | [link](https://rscot.learningfind.com/docs/rscot-code-agent.html) |
| Permission modes | auto / ask / deny | 2026-11-06 | [link](https://rscot.learningfind.com/docs/rscot-code-agent.html) |
| Default access scope | workspace-only | 2026-11-06 | [link](https://rscot.learningfind.com/docs/rscot-code-agent.html) |
| Minimum version for run_powershell | 1.8.73+ | 2026-11-06 | [link](https://rscot.learningfind.com/docs/rscot-code-agent.html) |
| Number of protocol primitives | 27 HTTP primitives in 9 groups (A–I) | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol-zh/) |
| Architecture adapter categories | 6 types: causal_lm, unet, dit, vlm, audio_diffusion, video_dit | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol-zh/) |
| Number of adapted open-source models | More than 40 | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol-zh/) |
| Number of tools exposed by MCP bridge | 20 | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol-zh/) |
| MCP bridge distribution status | Not publicly distributed | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol-zh/) |
| Usage method | Via Rescot desktop app over SSH to your own GPU server (v0.4) | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol-zh/) |
| MCP bridge computation location | Computation remains on the ModelRein server loading the model | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol-zh/) |
| Requirement for new architectures | Must add an adapter first if not among the 6 types | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol-zh/) |
| Architecture adapters | 6: causal_lm, unet, dit, vlm, audio_diffusion, video_dit | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol/) |
| Open-source models adapted | 40+ | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol/) |
| Tools exposed by the MCP bridge | 20 | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol/) |
| MCP bridge publicly distributed | Not publicly distributed yet | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol/) |
| Usage entry point | Rescot desktop app over SSH to your own GPU server (v0.4) | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol/) |
| Compute location for MCP bridge | Compute still runs on the ModelRein server that holds the model | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol/) |
| New architecture limitation | A new architecture outside these 6 families needs an adapter first | 2026-11-06 | [link](https://rscot.learningfind.com/answers/model-control-vs-tool-protocol/) |
| number of adapters | 6 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/how-lmcp-works-with-any-huggingface-model.html) |
| response on unmatched architecture | 400 with message "no adapter for this architecture" | 2026-11-06 | [link](https://rscot.learningfind.com/blog/how-lmcp-works-with-any-huggingface-model.html) |
| supported architecture families | causal_lm, unet, dit, vlm, audio_diffusion, video_dit | 2026-11-06 | [link](https://rscot.learningfind.com/blog/how-lmcp-works-with-any-huggingface-model.html) |
| surfaces endpoint | GET /lmcp/surfaces?model={repo_id} | 2026-11-06 | [link](https://rscot.learningfind.com/blog/how-lmcp-works-with-any-huggingface-model.html) |
| example model surface count | Qwen/Qwen2.5-1.5B-Instruct: n_surfaces 112 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/how-lmcp-works-with-any-huggingface-model.html) |
| intervention strength representation | adaptive_fraction (relative to residual-stream norm) | 2026-11-06 | [link](https://rscot.learningfind.com/blog/how-lmcp-works-with-any-huggingface-model.html) |
| probe prompts used for residual-norm calibration | 2 probe prompts | 2026-11-06 | [link](https://rscot.learningfind.com/blog/how-lmcp-works-with-any-huggingface-model.html) |
| number of primitives | 27 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/how-lmcp-works-with-any-huggingface-model.html) |
| Default server address | http://localhost:8808 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/controlling-qwen-llama-deepseek-with-one-agent.html) |
| Models used in walkthrough | Qwen2.5-1.5B-Instruct, Llama-3.1-8B-Instruct, DeepSeek-V3 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/controlling-qwen-llama-deepseek-with-one-agent.html) |
| Qwen 2.5 transformer layer count | 28 layers | 2026-11-06 | [link](https://rscot.learningfind.com/blog/controlling-qwen-llama-deepseek-with-one-agent.html) |
| Llama 3.1 transformer layer count | 32 layers | 2026-11-06 | [link](https://rscot.learningfind.com/blog/controlling-qwen-llama-deepseek-with-one-agent.html) |
| DeepSeek V3 parameter scale | 671B total, 37B active | 2026-11-06 | [link](https://rscot.learningfind.com/blog/controlling-qwen-llama-deepseek-with-one-agent.html) |
| Strength sweep values | 0.0, 0.3, 0.6, 1.0, 1.5, 2.0 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/controlling-qwen-llama-deepseek-with-one-agent.html) |
| Strength effect range | Below ~0.3 nothing happens; above ~1.5 repeats; sweet spot ~1.0 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/controlling-qwen-llama-deepseek-with-one-agent.html) |
| Provided HTTP endpoints | compute_vector_auto, head_mask, layer_route, logit_bias, pipeline | 2026-11-06 | [link](https://rscot.learningfind.com/blog/controlling-qwen-llama-deepseek-with-one-agent.html) |
| number of architecture adapters | 6 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/why-model-agnostic-agents-need-a-control-protocol.html) |
| per-model code in the agent | 0 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/why-model-agnostic-agents-need-a-control-protocol.html) |
| models used in example | Qwen2.5-1.5B-Instruct, Llama-3.1-8B-Instruct, DeepSeek-V3 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/why-model-agnostic-agents-need-a-control-protocol.html) |
| example endpoint path | /compute_vector_auto | 2026-11-06 | [link](https://rscot.learningfind.com/blog/why-model-agnostic-agents-need-a-control-protocol.html) |
| example request fields | model, concept_description, pos_style_desc, neg_style_desc, seed_prompts | 2026-11-06 | [link](https://rscot.learningfind.com/blog/why-model-agnostic-agents-need-a-control-protocol.html) |
| layer selection method | separability scan | 2026-11-06 | [link](https://rscot.learningfind.com/blog/why-model-agnostic-agents-need-a-control-protocol.html) |
| supported primitive types | steering vectors, head masks, layer routing, residual-stream probes | 2026-11-06 | [link](https://rscot.learningfind.com/blog/why-model-agnostic-agents-need-a-control-protocol.html) |
| Publication date | Oct 8, 2026 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/) |
| Supported models (examples) | Qwen/Qwen2.5-1.5B-Instruct, meta-llama/Llama-3.1-8B-Instruct, deepseek-ai/DeepSeek-V3 | 2026-11-06 | [link](https://rscot.learningfind.com/blog/) |
| Per-model configuration requirement | Zero per-model configuration | 2026-11-06 | [link](https://rscot.learningfind.com/blog/) |
| Steps when loading a new model | Config introspection, layer discovery via separability scan, auto-strength calibration against the residual-stream norm | 2026-11-06 | [link](https://rscot.learningfind.com/blog/) |
| Difference from MCP | MCP connects a chat model to external tools; ModelRein reaches into the model itself | 2026-11-06 | [link](https://rscot.learningfind.com/blog/) |
| Model access method | One HTTP call | 2026-11-06 | [link](https://rscot.learningfind.com/blog/) |
| Article topics | Model-agnostic agents, open-source LLM control, ModelRein protocol design | 2026-11-06 | [link](https://rscot.learningfind.com/blog/) |

## Questions

---

Updated 2026-11-09

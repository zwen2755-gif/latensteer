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

## Questions people ask

### Can I clamp or patch specific attention heads to force a model to answer differently?

Sparse localization has been demonstrated: one study identified only three attention heads that independently govern persona and style formation, localized via geometric analysis of internal representations. [src2](https://icml.cc/virtual/2026/poster/61348) Another line of work locates concept-specific attention modules and then applies scalar interventions to amplify or suppress a concept's influence. [src4](https://m.36kr.com/p/3378214604724740) [src5](https://eu.36kr.com/zh/p/3378214604724740) Head selection alone is described as under-constrained, because a difference-of-means update within selected heads still carries off-target axes, so finer subspace constraints have been proposed to limit the intervention. [src3](https://arxiv-org.ezproxy.obspm.fr/html/2609.31122v1) Patching can also be framed as counterfactual activation replacement, swapping a head's activation from one prompt with the corresponding activation from a contrastive prompt while re-running the rest of the model unchanged. [src8](https://www.emergentmind.com/topics/generative-causal-mediation-gcm) Reported goals emphasize sparse control that preserves overall fluency and relevance rather than blanket perturbation of the network, and effectiveness has been observed to depend on model-specific attention characteristics, being particularly effective when those characteristics match. [src6](https://www.jstage.jst.go.jp/article/pjsai/JSAI2026/0/JSAI2026_5E3GS6e04/_article/-char/ja) [src8](https://www.emergentmind.com/topics/generative-causal-mediation-gcm)


### How do I find which layers to intervene on in an open model without hand-tuning?

Automated layer selection can be done by scoring each layer with a cheap, data-driven metric and then intervening only on the top-ranked layers, rather than searching layer combinations by hand. [src4](https://www.scnet.cn/help/docs/mainsite/ai/practice/application/layernavigator/index.html) [src6](https://arxiv.org/html/2611.01493v1) One approach computes a per-layer steerability score from distinguishability and consistency and picks the Top-K layers, avoiding combinatorial brute-force search. [src4](https://www.scnet.cn/help/docs/mainsite/ai/practice/application/layernavigator/index.html) Another derives layer scores from the same cached activations used to build steering vectors, so no held-out steering evaluations or auxiliary selector training are needed. [src6](https://arxiv.org/html/2611.01493v1) Layer choice is task-dependent and varies across tasks, so a dynamic selection strategy is used to determine the optimal layer for each task. [src2](http://arxiv.org.ezproxy.obspm.fr/pdf/2410.09343) Reported selections are model-specific, for example layer 15 for one 7B chat model and layer 21 for a 14B model, with injection strength set to 2. [src3](https://huggingface.co/buckets/huggingchat/papers-content/tree/2602/2602.01654.md?code=true) In one table, selected layers ranged from 20 of 28 layers up to 32 of 40 layers across model sizes, with PCA retaining over 90% of variance. [src7](https://arxiv.org/html/2609.24066)


### How do people currently steer open models without fine-tuning—prompting, activation editing, or logit manipulation?

另一类方法在概率分布层面做细粒度干预，通过两次前向计算识别方向性差距并重新分配 token 级输出概率，属于轻量、免训练、与模型无关的框架。 [src2](https://aclanthology.org/people/feiyang-li-3246/) [src3](https://aclanthology.org/2026.findings-acl.953/) 还有方法在激活空间构造引导向量，例如对正负样本激活差取均值，或用主成分分析提取方差最大的方向作为引导向量。 [src1](https://ojs.aaai.org/index.php/AAAI/article/view/40696/44657) 基于残差干预的偏好对齐方法则利用选中与拒绝激活差异在幅度上显著、在方向上较为一致的特点，蒸馏出可泛化的聚合引导向量。 [src4](https://www.research-collection.ethz.ch:443/bitstream/handle/20.500.11850/733074/Xie_Jiaqing.pdf?sequence=1&isAllowed=y) 有研究将推理时激活空间干预视为一种独立的模型适配范式，并提出八项功能评估标准，将其定位为基于激活空间的局部可逆行为修改方法。 [src6](https://aclanthology.org/people/patrick-queiroz-da-silva/)


### How much latency does activation steering add compared to normal inference?

Activation steering can add effectively zero latency when implemented as a fixed multiplicative gate during the standard forward pass. [src3](https://export.arxiv.org/pdf/2605.17144) Additive steering approaches shift activations along a single rank-one vector, and the main inference overhead is attributed to retrieving the relevant steering vectors from a set. [src2](https://huggingface.co/buckets/huggingchat/papers-content/tree/2510/2510.27206.md?code=true) [src3](https://export.arxiv.org/pdf/2605.17144) Reported latency figures vary by method and configuration, so no single number applies universally. [src3](https://export.arxiv.org/pdf/2605.17144) [src6](https://github.com/zhaoyang97/Paper-Notes/blob/main/docs/ICLR2026/optimization/exploring_diverse_generation_paths_via_inference-time_stiefel_activation_steerin.md)


### Is it possible to intervene on only a few layers and still get a strong behavioral change?

是，可以只干预少数层而获得较强的行为改变，但效果取决于干预深度与目标结构的匹配，并非任意少数层都足够。 [src1](https://zenodo.org/records/20736385/files/Behavioral%20Attractors.pdf?download=1) [src8](https://openreview.net/challenge?redirect=%2Fpdf%3Fid%3DNIwL22qGYy) 干预可按深度分为五级，从在既有选项内选择、偏好某条轨迹，到改变生成器、改变生成规则，层级越深所触及的结构越基础。 [src1](https://zenodo.org/records/20736385/files/Behavioral%20Attractors.pdf?download=1) 在表示层面，推理时直接扰动中间激活、保持参数不变的做法，可在单模态或多模态隐藏状态上操作，说明局部层的干预具备可行性。 [src8](https://openreview.net/challenge?redirect=%2Fpdf%3Fid%3DNIwL22qGYy) 不过干预位置的选择往往是在多个维度之间的折中，且行为受环境可供性、个体能力与社会规制共同形成的吸引子约束，因此少数层干预的强度会受这些条件限制。 [src2](http://eprints.lse.ac.uk/117713/1/how_to_change_consumer_behaviours.pdf?_x_tr_sch=http) 此外，干预顺序的意义被强调为优先于速度，顺序不当可能削弱预期效果。 [src5](https://zenodo.org/records/17926263/files/5T%20S%E1%BB%91ng%20%E2%80%93%20BEHAVIOR%20OS_V2.pdf?download=1)


### Is there a way to auto-discover layers and calibrate intervention strength when loading a model?

目前没有单一方法能同时完成层自动发现与干预强度校准，但相关组件可以组合使用。 [src3](https://circuitkit.lexsi.ai/api-reference/flat-api/) [src5](https://papers.cool/arxiv/2605.28722) 层自动发现方面，有工具在加载模型时自动设置所需的 hook 标志，并可从模型本身发现注意力模块、检查 hook 目标是否可用。 [src2](http://zjureal.com/EasySteer/latest/user-guide/attention/) [src3](https://circuitkit.lexsi.ai/api-reference/flat-api/) 干预强度方面，有方法指出合适的干预方向和强度因样本而异，统一施加固定干预会在良性输入上造成能力退化，因此采用多适配器机制自适应确定方向与强度，并用基于能量的门控模块区分适合干预的输入。 [src1](https://www.semanticscholar.org/paper/Multi-Adapter-Representation-Interventions-via-Yu-Li/643698be8a30e3b4cbcb3c4a1d7a26f820388525/figure/7) [src5](https://papers.cool/arxiv/2605.28722) 另有方法将校准方向设计为与另一子空间正交，从而在调整某一属性时不改变其他属性。 [src6](https://comfy.icu/node/LCSSharpnessIntervene) 这些组件的适用范围有限制，例如部分干预点仅支持标准解码器多头或分组查询注意力，且张量并行规模为 1。 [src2](http://zjureal.com/EasySteer/latest/user-guide/attention/) 因此可行路径是分别选用层发现与强度校准组件，并核对其各自的支持范围。 [src2](http://zjureal.com/EasySteer/latest/user-guide/attention/) [src3](https://circuitkit.lexsi.ai/api-reference/flat-api/) [src5](https://papers.cool/arxiv/2605.28722)


### What's the difference between activation patching, steering vectors, and logit bias in practice?

Activation patching, steering vectors, and logit bias differ in where and how they intervene: patching replaces internal activations with vectors from a contrastive run, steering adds a direction vector to activations at inference, and logit bias adjusts output logits directly. [src2](https://actionable-interpretability.github.io/posters/52_steering_off_course_reliability_challenges_in_steering_language_models%20-%20Patrick%20Da%20Silva.pdf) [src7](https://github.com/QianJinGuo/wiki-public/blob/main/concepts/activation-engineering.md) [src8](https://raw.githubusercontent.com/QianJinGuo/wiki-public/refs/heads/main/concepts/activation-engineering.md) Activation patching is primarily used for causal tracing, requiring a clean/corrupted prompt pair to test whether a behavior is restored. [src5](https://github.com/garry-x/llm-course/blob/main/chapters/ch05.html) Steering vectors are extracted by comparing activations with and without a concept, then adding that direction during inference, but they are post-hoc interventions that cannot explain how a concept is internally represented. [src7](https://github.com/QianJinGuo/wiki-public/blob/main/concepts/activation-engineering.md) [src8](https://raw.githubusercontent.com/QianJinGuo/wiki-public/refs/heads/main/concepts/activation-engineering.md) 0% of the time respectively. [src1](https://export.arxiv.org/pdf/2511.18635) [src3](https://arxiv.org/html/2511.18635v1) Evaluations across different model families also show high variance in steering method performance, indicating poor generalization. [src2](https://actionable-interpretability.github.io/posters/52_steering_off_course_reliability_challenges_in_steering_language_models%20-%20Patrick%20Da%20Silva.pdf)


### how to change an LLM's behavior at inference time without fine-tuning

在推理时改变大模型行为而不做微调，主流做法是激活引导（activation steering）：从对比样本中提取“引导向量”，在前向传播时加到残差流上。 [src6](https://aclanthology.org/2024.acl-long.828/) [src8](https://rotalabs.ai/blog/steering-vectors-runtime-control/) 具体方法是取正负样本对在残差流激活上的差值并取平均，得到方向向量，推理时在用户提示之后的各 token 位置按正负系数叠加。 [src6](https://aclanthology.org/2024.acl-long.828/) 这类干预无需重新训练，且可与微调、系统提示设计等方法叠加使用，对能力的削弱相对有限。 [src6](https://aclanthology.org/2024.acl-long.828/) 也有工作在解码阶段用轻量预测器识别重复、冗长等行为，并在采样时做可逆的定向干预。 [src4](https://zenodo.org/records/18331052) 多种特质组合时，可迭代地在已被先前特质修改的残差流上重新训练探针，使引导向量成为可复用的模块化组件。 [src2](https://icml.cc/virtual/2026/poster/66145) 从机制上看，上下文干预与激活干预都可视为改变模型对潜在概念的信念，其中引导主要作用于概念先验。 [src5](https://icml.cc/virtual/2026/poster/63788)


### How can I run activation patching on residual stream positions to localize a behavior?

Activation patching on residual stream positions works by running a clean prompt and a corrupt prompt, then copying the clean activation at a specific layer and position into the corrupt run to see whether the clean answer is restored. [src1](https://github.com/ndif-team/nnsight/blob/de7fec4d207fc8e0deacaa44fb68f8d0412506ef/docs/patterns/activation-patching.md) [src3](https://ndif-team.github.io/nnterp/tutorials/activation-patching/) , the output leaving a block) at one position, and the same line can run on sequential, parallel, or post-norm blocks. [src3](https://ndif-team.github.io/nnterp/tutorials/activation-patching/) You can patch either the full residual stream or a position-specific slice, using a hook that replaces only the chosen position's rows. [src2](https://github.com/mytechnotalent/mechanistic_interpretability/blob/main/README.md) [src7](https://raw.githubusercontent.com/ARENA-education/ARENA_materials/refs/heads/main/chapter1_transformer_interp/instructions/pages/21_%5B1.4.1%5D_Indirect_Object_Identification.md) 797 probability, while the unpatched run serves as the baseline. [src3](https://ndif-team.github.io/nnterp/tutorials/activation-patching/) To localize a behavior, sweep layers and positions and record a patching metric on the logits for each combination. [src7](https://raw.githubusercontent.com/ARENA-education/ARENA_materials/refs/heads/main/chapter1_transformer_interp/instructions/pages/21_%5B1.4.1%5D_Indirect_Object_Identification.md) Note that standard activation patching measures a component's total effect, whereas path patching isolates a direct sender-to-receiver effect by freezing other heads and optionally MLPs. [src6](https://ukplab.github.io/murano/docs/reference/steps/path_patch/)


### How do I avoid fooling myself with cherry-picked examples when editing internal activations?

要避免在编辑内部激活时被挑选过的样本误导，应预先固定评估集并完整报告所有结果，而不是只展示有利案例。 [src1](https://zenodo.org/records/22012341/files/NobleJackal_99_Errors_in_GEO_AR_v1.0.0.pdf) [src3](https://human.libretexts.org/@api/deki/pages/51536/pdf/3.4%253A%2bEthical%2bAnalysis%2bof%2bData.pdf) 具体做法包括：对比预期记录数与实际报告数，获取全部原始输出并逐条记录每个排除项及其理由；计算正向、负向和未知（UNKNOWN）的分布，并检查是否按系统、语言、时期或特定情形进行了选择性抽取。 [src1](https://zenodo.org/records/22012341/files/NobleJackal_99_Errors_in_GEO_AR_v1.0.0.pdf) 使用小而多样的真实样本（如10到50个带预期结果的例子）进行客观比较，可减少用挑选出的成功案例自我欺骗的风险。 [src2](https://www.promptise.com/questions/prompt-engineering-datasets) 若对数据进行修剪，必须向读者说明修剪的比例，且不得仅为支持自身论点而修剪。 [src3](https://human.libretexts.org/@api/deki/pages/51536/pdf/3.4%253A%2bEthical%2bAnalysis%2bof%2bData.pdf) 此外，应披露实质性协助、交叉核验生成内容，并归档模型、提示、数据与代码以支持可复现性。 [src6](https://zenodo-rdm.web.cern.ch/records/17349510/files/Shigapov_Questionable_Practices_in_the_use_of_AI.pdf?download=1)


### How do I design a control experiment to rule out that my intervention effect is just noise?

设计控制实验以排除“效应只是噪声”的核心做法，是设置对照条件并借助随机分配与统计功效计算来区分真实效应与随机波动。 [src1](https://www.tandfonline.com/doi/pdf/10.1080/00031305.2025.2554756?__cf_chl_tk=Y1SksjRv52XrJQhhrEg2Q4rqzOTU5emVpr8E.7JYoaE-1766623851-1.0.1.1-kpzf6.3Ul3jzmxClLqa0HxAmQQIw2qtB295s3sGZPK4) [src2](https://indico.cern.ch/event/1622011/contributions/6951790/attachments/3291697/5885976/Lab_experiments_in_innovation_research.pdf) [src4](https://publications.gc.ca/collections/collection_2019/bcp-pco/CP22-174-2019-eng.pdf) 对照条件本身编码了一种假设，因此需要明确对照所代表的反事实情形，并据此解释结果。 [src1](https://www.tandfonline.com/doi/pdf/10.1080/00031305.2025.2554756?__cf_chl_tk=Y1SksjRv52XrJQhhrEg2Q4rqzOTU5emVpr8E.7JYoaE-1766623851-1.0.1.1-kpzf6.3Ul3jzmxClLqa0HxAmQQIw2qtB295s3sGZPK4) 随机分配是排除替代解释的有效方式，在无法随机分配时可退而采用非随机分配的准实验设计来近似复现其严谨性。 [src4](https://publications.gc.ca/collections/collection_2019/bcp-pco/CP22-174-2019-eng.pdf) 05、功效80%，效应减半大致需要四倍样本。 [src2](https://indico.cern.ch/event/1622011/contributions/6951790/attachments/3291697/5885976/Lab_experiments_in_innovation_research.pdf) 还可用安慰剂检验，例如把干预时间前移到真实干预之前，若在虚假时点仍出现较大效应，说明两组在干预前已存在漂移。 [src3](https://tidyecology.com/posts/placebo-tests-for-panel-causal/) 需注意，并非所有自变量都可被实验操纵，这是实验设计的一项固有限制。 [src7](https://is.muni.cz/el/fss/podzim2019/BSSb1104/um/Kellstedt_cap.3-5.pdf)


### How do I log and reproduce an intervention experiment so others can rerun it?

To make an intervention experiment rerunnable, package a frozen confirmatory manifest, the required code and environment specification, a small reference dataset or deterministic test, and instructions for reproducing one principal analysis, including an expected checksum or numerical tolerance and steps to regenerate one published figure or table. [src1](https://zenodo.org/records/22857230) Keep computational reproduction (same code, data, and specification regenerate the reported result) separate from scientific replication. [src1](https://zenodo.org/records/22857230) Preregister protocols, hypotheses, or analysis plans, and document planned materials, instrumentation, software environments, and calibration procedures. [src2](https://eprints.whiterose.ac.uk/id/eprint/245379/2/UoL_x_Buttercrumble_-_Open_Research_-_Experimental.pdf) Maintain structured, timestamped, contemporaneous records of procedures, protocol deviations, environmental conditions, and instrument settings, and record how design adjustments in iterative or multi-phase work affect later runs. [src2](https://eprints.whiterose.ac.uk/id/eprint/245379/2/UoL_x_Buttercrumble_-_Open_Research_-_Experimental.pdf) Do all data preparation and analysis in code, build analysis from primary data files, fully describe variables, document every empirical claim, and archive files. [src7](https://isps.yale.edu/sites/default/files/files/YSPH-reproducibility_April2018-Peer(1).pdf) Note that laboratory packages alone may not transfer tacit knowledge between original experimenters and replicators, so plan for that gap. [src4](https://idus.us.es/server/api/core/bitstreams/990bcac7-a3db-4fa0-b852-904fa2fcfc22/content)


### How do people currently do ablation studies on attention heads without retraining?

目前常见的做法是在不重新训练的前提下，对预训练模型中的注意力头做零化或整单元移除，再观察指标变化。 [src4](https://export.arxiv.org/pdf/2610.28214) [src5](https://arxiv.org/html/2601.04398v1) 具体操作上，一种方式是把某个头的输入、循环权重、门偏置以及下一层对应列置零，从而完全静默该头。 [src4](https://export.arxiv.org/pdf/2610.28214) 评估时通常对比准确率、困惑度或损失等指标，但不同指标可能给出相互矛盾的头部重要性排序。 [src5](https://arxiv.org/html/2601.04398v1) 此外，重要性排序会随数据集和任务显著变化，在某一分布上关键的头在另一分布上可能冗余。 [src5](https://arxiv.org/html/2601.04398v1) 也有研究通过头消融验证交互模式，并据此抑制干扰头或剪除冗余头，以考察鲁棒性与精度保持情况。 [src1](https://www.openaccess.thecvf.com/content/CVPR2026F/papers/Lu_Discovering_Attention_Head_Interactions_in_Vision_Transformers_CVPRF_2026_paper.pdf) [src3](https://ieeexplore.ieee.org/document/11697664)



## Questions

---

Updated 2026-11-13

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

### What hardware do I need to intervene on activations of a large open model in real time?

Probe-based monitors reuse activations already being computed, adding virtually no latency and minimal marginal cost, so multiple probes can run in parallel on the same hardware. [src8](https://www.goodfire.com/blog/probe-monitors-101?trk=public_post_comment-text) Its GPU tests passed on an NVIDIA L4 with a specific serving version, run by hand, with no GPU CI yet and only that version supported. [src2](https://pypi.org/project/undercurrent/0.1.0/) [src3](https://pypi.org/project/undercurrent/)


### How do I avoid breaking the model when editing attention heads at runtime?

Editing attention heads at runtime is safer when changes are validated through controlled ablation and causal intervention rather than visual inspection alone. [src7](https://github.com/cdavid817/agent-interview/blob/b2c9666031c0f96f61a37d1e9a1feaa1aa318600/docs/01-foundations/transformer/attention.md) Candidate configurations should be compared under identical parameter count, data, and training budget, using perplexity, downstream tasks, long-context behavior, training stability, time-to-first-token, tokens-per-second, and memory as criteria. [src7](https://github.com/cdavid817/agent-interview/blob/b2c9666031c0f96f61a37d1e9a1feaa1aa318600/docs/01-foundations/transformer/attention.md) Head-level interventions such as masking, zeroing, permutation, pruning, or replacement should be evaluated by the resulting degradation in perplexity and task performance, since a head that consistently damages a task when removed shows causal contribution. [src7](https://github.com/cdavid817/agent-interview/blob/b2c9666031c0f96f61a37d1e9a1feaa1aa318600/docs/01-foundations/transformer/attention.md) When pruning ratios vary by depth, a logarithmic schedule from the first to the last layer has been used to mitigate error accumulation in shallow layers while avoiding excessive pruning in deeper layers. [src3](https://proceedings.neurips.cc/paper_files/paper/2024/file/c1c44e46358e0fb94dc94ec495a7fb1a-Paper-Conference.pdf)

- Accessible model internals: Residual stream, attention heads, individual layers, final logits ([source](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html), 2026-11-06)

### How do I compare different runtimes for activation steering on the same open model?

To compare runtimes for activation steering on the same open model, hold the model, inputs, and steering configuration fixed and measure latency and accuracy under identical conditions. [src1](https://github.com/johnmarktaylor91/torchlens/blob/83b65778d8fe0804bfcfac28d6ae604e92c210e6/docs/guides/fast_paths.md) [src6](https://arxiv.org/html/2603.18329v1) Report a median over repeated calls rather than a single run, and state the hardware, thread count, sequence length, and whether gradient mode is on, since these settings change the measured ratios. [src1](https://github.com/johnmarktaylor91/torchlens/blob/83b65778d8fe0804bfcfac28d6ae604e92c210e6/docs/guides/fast_paths.md) Separate the cost of the steering intervention from the cost of any capture or instrumentation path, and verify that the faster path produces outputs equal to the reference path before trusting its timings. [src1](https://github.com/johnmarktaylor91/torchlens/blob/83b65778d8fe0804bfcfac28d6ae604e92c210e6/docs/guides/fast_paths.md) Compare at least one weak and one moderate intervention strength, because accuracy and efficiency can trade off differently across that range. [src3](https://arxiv.org/html/2601.03093v3)


### Where can I download a runtime that lets me steer model layers and logits at inference time?

A runtime that supports inference-time steering of layers and logits can be obtained from several open-source packages distributed via PyPI and GitHub. [src1](https://pypi.org/project/brainscope/0.3.0/) [src4](https://pypi.org/project/rotalabs-steer/) [src7](http://zjureal.com/EasySteer/dev/) One option is a pip-installable server that exposes residual-stream access and per-request steering through an API, with a documented `/steer` endpoint and policy-based controls. [src1](https://pypi.org/project/brainscope/0.3.0/) [src3](https://github.com/moudrkat/brainscope) Another package provides tools for extracting and applying steering vectors at inference time without retraining, including pre-extracted vectors and optional integration with agent frameworks. [src4](https://pypi.org/project/rotalabs-steer/) A third engine modifies intermediate activations—decoder hidden states, attention head outputs, and router logits—while keeping weights fixed, and is built on a specific serving engine version with continuous batching and caching support. [src7](http://zjureal.com/EasySteer/dev/) Reported trade-offs include that extraction quality largely determines results and that over-steering can degrade model behavior, so the full steering guide should be reviewed before production use. [src3](https://github.com/moudrkat/brainscope)


### Can I control an open model's logits to constrain its outputs to a specific format?

Yes—constrained decoding works by masking invalid tokens at each generation step so the model can only emit output matching a required format. [src5](https://pkg.go.dev/github.com/townsendmerino/goinfer@v0.1.2/constrain) [src7](https://www.ultralytics.com/glossary/constrained-decoding) At every decode step, each vocabulary token is checked against the grammar, and tokens that would break the format have their logits set to −∞ so the sampler cannot pick them. [src5](https://pkg.go.dev/github.com/townsendmerino/goinfer@v0.1.2/constrain) [src7](https://www.ultralytics.com/glossary/constrained-decoding) It plugs into local inference through a logits processor hook, and several inference engines support such processors. [src6](https://dottxt-ai.github.io/outlines/1.0.0/features/advanced/logits_processors/)


### What are the security and access-control considerations for a runtime that exposes internal model state?

A runtime that exposes internal model state should treat that state as sensitive and enforce access control at the boundary rather than relying on storage encryption alone. [src2](https://github.com/fluxzero-io/fluxzero-sdk-java/blob/bd7b8c1f0f6395f4e88683957f5cea4b5db1fb29/docs/agents/articles/sdk/models/state-boundaries.md) [src7](https://www.orgn.com/blog/secure-llm) State and history should be classified as sensitive, and model output and tool input derived from the model should be treated as untrusted and validated against schemas and permission gates. [src6](https://github.com/puristajs/harness/blob/4173f7bee27f8fbe960069f06d0fd14c33b9b0fc/docs/security/security-model.md) Because plaintext exists in memory during inference even when network and storage layers are encrypted, hardware-backed confidential computing can isolate that memory boundary. [src7](https://www.orgn.com/blog/secure-llm)


### open source llm runtime controller

Open-source LLM runtime controllers generally act as a control plane that starts, stops, and switches local inference engines behind a stable endpoint rather than performing inference themselves. [src2](https://pypi.org/project/local-engine-router/0.7.1/) [src4](https://github.com/BartRuSec/llm-runtime-dock) They commonly expose OpenAI- or Anthropic-compatible HTTP APIs so existing clients can point at one address while the underlying engine changes. [src2](https://pypi.org/project/local-engine-router/0.7.1/) [src4](https://github.com/BartRuSec/llm-runtime-dock) Lifecycle control endpoints such as status and switch are typically restricted to loopback and refused when the gateway binds to a non-loopback address, even if an API key is configured. [src8](https://socket.dev/npm/package/llm-runtime-dock) Process management often uses fail-closed behavior: if discovery finds zero or multiple candidate child processes, startup is aborted and spawned launchers are reclaimed to avoid orphans. [src5](https://github.com/IkariKr/RuntimeDeck) State is frequently persisted outside the source tree with atomic file replacement and locking, and stale PID records are discarded without sending termination signals. [src5](https://github.com/IkariKr/RuntimeDeck)


### model layer activation editing tool

Model layer activation editing is typically implemented through activation-level intervention, weight-level ablation, or selector-based model surgery rather than a single unified tool. [src6](https://ukplab.github.io/murano/docs/guides/patch/) [src7](https://deepwiki.com/google-deepmind/penzai/5.3-model-surgery-and-modification) Selector-based approaches treat models as data structures and follow a select-transform-deselect pattern, creating new model copies while preserving the original. [src7](https://deepwiki.com/google-deepmind/penzai/5.3-model-surgery-and-modification) Activation steering instead adds a fixed direction to the residual stream at inference time, and that direction can be built from text edits rather than contrastive examples. [src4](https://export.arxiv.org/pdf/2611.03040) Editing support varies by artifact format: some formats allow validated graph and tensor subset editing with export, others allow only tensor-level changes, and some permit inspection only. [src1](https://pypi.org/project/nneditor/1.0.0/)

Steps when loading a new model：Config introspection, layer discovery via separability scan, auto-strength calibration against the residual-stream norm Number of tool families：6


### representation engineering alternatives

Representation engineering is one approach among several for controlling model behavior, and it is commonly compared with mechanistic interpretability, prompt engineering, and fine-tuning. [src2](https://axi.lims.ac.uk/paper/2502.17601) Steering vectors can be applied at inference time without retraining, whereas weight-level modification such as orthogonalization changes weights permanently. [src4](https://huggingface.co/spaces/sub314xxl/obliteratus/blob/2bc8e46328189646d8ab6bb3439fe8c4b778d7a2/docs/mechanistic_interpretability_research.md?code=true) [src8](https://www.ultralytics.com/glossary/steering-vectors) Reported risks include performance decrease, increased compute time, and steerability issues. [src2](https://axi.lims.ac.uk/paper/2502.17601)


---

Updated 2026-11-15

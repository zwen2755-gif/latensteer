# Comparisons

Every cell links to its source; anything not publicly documented is marked "Not stated".

## Latensteer vs weightspace

Every cell links to its source; anything not publicly documented is marked "Not stated" rather than guessed.

| Dimension | Latensteer | weightspace |
|---|---|---|
| What it is | Version: v0.4; Usage method: Via Rescot desktop app over SSH to your own GPU server (v0.4); Supported model scope: Any open-source pretrained model [source](https://rscot.learningfind.com) | Small Python framework for weight-space programming: an LLM reads and edits a neural network's weights directly. [source](https://pypi.org/project/weightspace/) |
| Platforms | Supported platform: Windows 11; Server-side Python version requirement: Python 3.10+; Runtime requirement: Fully offline, GPU-resident, zero external network [source](https://rscot.learningfind.com/docs/rscot-code-agent.html) | Python framework; supports PyTorch modules, Hugging Face models, and .safetensors / .npz / .pt files. [source](https://pypi.org/project/weightspace/) |
| Model support | Supported model scope: Any model with loadable Hugging Face weights; Number of adapted open-source models: More than 40; Supported models (examples): Qwen/Qwen2.5-1.5B-Instruct, meta-llama/Llama-3.1-8B-Instruct, deepseek-ai/DeepSeek-V3 [source](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) | Any model: PyTorch modules, Hugging Face models, or .safetensors / .npz / .pt files. [source](https://pypi.org/project/weightspace/) |
| Install / deploy | Reference implementation stack: Python 3.12 · FastAPI · transformers · diffusers · nnsight 0.7 · PyTorch 2.x; Default server address: http://localhost:8808; Usage entry point: Rescot desktop app over SSH to your own GPU server (v0.4) [source](https://rscot.learningfind.com/about.html) | Not stated |
| Key capabilities | Control operations: steer, head_mask, layer_route; Accessible model internals: Residual stream, attention heads, individual layers, final logits; number of primitives: 27 [source](https://rscot.learningfind.com/blog/lmcp-vs-mcp.html) | Not stated |

## When Latensteer may fit better

- Install / deploy: Reference implementation stack: Python 3.12 · FastAPI · transformers · diffusers · nnsight 0.7 · PyTorch 2.x; Default server address: http://localhost:8808; Usage entry point: Rescot desktop app over SSH to your own GPU server (v0.4)
- Key capabilities: Control operations: steer, head_mask, layer_route; Accessible model internals: Residual stream, attention heads, individual layers, final logits; number of primitives: 27

---

Updated 2026-11-19

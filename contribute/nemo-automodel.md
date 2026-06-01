---
repo: "NeMo Automodel"
slug: nemo-automodel
issues_count: 6
updated: 2026-06-01
---

# NeMo Automodel — Contribution Opportunities

YAML tooling, docs, dataset PRs merge fast. zeel2104 has 3 PRs. NVIDIA name on resume.

← [[../nemo-automodel|Back to NeMo Automodel]]

## Open Issues (6)

- **[#2356 Integrate FlashQLA](https://github.com/NVIDIA-NeMo/Automodel/issues/2356)** `enhancement`
  opened 2026-05-29 · 0 comments
  > https://github.com/QwenLM/FlashQLA

- **[#2355 Refactor gemma4 drafter specific from recipes/vlm/finetune.py](https://github.com/NVIDIA-NeMo/Automodel/issues/2355)**
  opened 2026-05-29 · 0 comments
  > Move `_is_gemma4_joint_target` to a model specific file since we want to keep `recipes/vlm/finetune.py` generic.  Plan is to add a marker `__nemo_recipe_target__ = True` to class `Gemma4WithDrafter`  

- **[#2342 Integrate Transformer Engine EP](https://github.com/NVIDIA-NeMo/Automodel/issues/2342)** `enhancement`
  opened 2026-05-28 · 0 comments
  > https://github.com/NVIDIA/TransformerEngine/pull/3035

- **[#2337 Support MiniCPM5-1B](https://github.com/NVIDIA-NeMo/Automodel/issues/2337)** `enhancement` `good first issue` `community-request`
  opened 2026-05-28 · 0 comments
  > https://huggingface.co/openbmb/MiniCPM5-1B

- **[#2329 [NeMo AutoModel] 26.06 Roadmap](https://github.com/NVIDIA-NeMo/Automodel/issues/2329)** `enhancement`
  opened 2026-05-28 · 0 comments
  > # [26.06] AutoModel Roadmap  This issue tracks major AutoModel work planned for the 26.06 release. Items link to GitHub issues where possible. PRs are included only when they are the clearest implemen

- **[#2327 Bug: deepseekv3_pretrain.yaml fails on first forward with DeepEP dispatch timeout](https://github.com/NVIDIA-NeMo/Automodel/issues/2327)** `bug`
  opened 2026-05-27 · 0 comments
  > **Describe the bug**  DeepSeek-V3 pretraining fails on the first forward pass when using the `examples/llm_pretrain/deepseekv3_pretrain.yaml` recipe with expert parallelism and DeepEP dispatch. The ru

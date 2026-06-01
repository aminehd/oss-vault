---
repo: "PEFT"
slug: peft
issues_count: 3
updated: 2026-06-01
---

# PEFT — Contribution Opportunities

Adding new PEFT methods is a well-defined contribution path.

← [[../peft|Back to PEFT]]

## Open Issues (3)

- **[#3265 prepare_model_for_kbit_training adds ~1 GB CUDA reserved memory in 500 ms — undocumented cost that breaks memory-constrained training on 8 GB unified-memory devices](https://github.com/huggingface/peft/issues/3265)**
  opened 2026-05-26 · 1 comments
  > ### Summary  `peft.prepare_model_for_kbit_training` allocates approximately **1024 MB of CUDA reserved memory in 500 ms** during the fp32 upcast of layer norms + gradient-flow setup. On 8 GB unified-m

- **[#3182 RFC: Improve code to resolve LoRA variants](https://github.com/huggingface/peft/issues/3182)**
  opened 2026-04-21 · 10 comments
  > In PEFT, we support different LoRA variants, e.g. DoRA. Which LoRA variant, if any, should be used is currently implemented in `resolve_lora_variant`. For `lora.Linear`, the method looks like this:  h

- **[#2310 Comparison of Different Fine-Tuning Techniques for Conversational AI](https://github.com/huggingface/peft/issues/2310)** `good first issue` `help wanted` `contributions-welcome`
  opened 2025-01-07 · 71 comments
  > ### Feature request  It would be incredibly helpful to have a clear comparison or support for various fine-tuning techniques specifically for conversational AI. This feature could include insights int

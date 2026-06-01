---
repo: "NeMo Automodel"
slug: nemo-automodel
commits_7d: 40
updated: 2026-06-01
---

# NeMo Automodel — Recent Commits (7d)

**40 commits this week** · [GitHub](https://github.com/NVIDIA-NeMo/Automodel/commits)

← [[../nemo-automodel|Back to NeMo Automodel]]

## Commits

- `be47708` [perf(datasets): skip full-conversation re-tokenization in chat loss mask (#2363)](https://github.com/NVIDIA-NeMo/Automodel/commit/be4770875100265300c6c9855c377c9ab896e3b8) — khazzz1c · 2026-05-31
- `0d1b8ce` [fix(datasets): tag agent SFT row errors with the example id (#2361)](https://github.com/NVIDIA-NeMo/Automodel/commit/0d1b8ce9ba32eb02709ca1916400ae648c7f8dc7) — khazzz1c · 2026-05-31
- `0b60a08` [feat(vlm): wire BitsAndBytes QLoRA quantization into VLM finetune recipe (#2358)](https://github.com/NVIDIA-NeMo/Automodel/commit/0b60a084157cdd569f3fa0d592b2dc0b8c15434a) — Huiying · 2026-05-31
- `07610c1` [feat(eval): add tool-call accuracy evaluator for agent SFT validation (#2338)](https://github.com/NVIDIA-NeMo/Automodel/commit/07610c118ac409f586ede5b3ee4e6d04a40ab51e) — khazzz1c · 2026-05-30
- `53b1b1b` [feat(datasets): drop history reasoning_content from agent SFT prompt (#2349)](https://github.com/NVIDIA-NeMo/Automodel/commit/53b1b1b40ebfd7fa2f455900b5210bf899c5908a) — khazzz1c · 2026-05-30
- `7dc827c` [perf(diffusion): improve Flux training throughput (#2251)](https://github.com/NVIDIA-NeMo/Automodel/commit/7dc827ca9108b2e45eb3beaba8a3cd148bfc658f) — Pranav Thombre · 2026-05-29
- `9238c3e` [feat: Add gemma4 drafter model support (#2240)](https://github.com/NVIDIA-NeMo/Automodel/commit/9238c3e65b3b2ee8e614ce64f1ecbd9a21d35747) — Abhishree Thittenamane · 2026-05-29
- `7251f20` [ci: override ep size for benchmark gptoss 120b (#2352)](https://github.com/NVIDIA-NeMo/Automodel/commit/7251f20e5a842312f2af8839a008270369f334a3) — Dong Hyuk Chang · 2026-05-29
- `38e301c` [feat(datasets): add train_on_last_turn_only to agent chat SFT dataset (#2347)](https://github.com/NVIDIA-NeMo/Automodel/commit/38e301cc3c14c9799078bcf36a5b9dce7048a758) — khazzz1c · 2026-05-29
- `04af8cc` [ci: add cluster_tag for reserved-cluster opt-in (#2353)](https://github.com/NVIDIA-NeMo/Automodel/commit/04af8cca850b4d3a30041e76bfdbb6fd88646fa5) — Dong Hyuk Chang · 2026-05-29
- `3fc9a4b` [ci: Clear up disk space for lint jobs (#2346)](https://github.com/NVIDIA-NeMo/Automodel/commit/3fc9a4b7e45be2a9cda6ab12f3e0500a2620cf74) — Charlie Truong · 2026-05-29
- `b59f1ac` [feat(datasets): preserve and optionally mask reasoning_content in agent SFT (#2348)](https://github.com/NVIDIA-NeMo/Automodel/commit/b59f1ac61acd5e685874eb4996514621db035fb7) — khazzz1c · 2026-05-29
- `a122288` [feat: support Qwen2.5-Omni model (#2345)](https://github.com/NVIDIA-NeMo/Automodel/commit/a1222887af3cabf20c144bd6194e4c3cbfd003cc) — Yuekai Zhang · 2026-05-29
- `80e9fc6` [feat: Add StepFun 3.7 support (#2344)](https://github.com/NVIDIA-NeMo/Automodel/commit/80e9fc661aacea2cb9c9f22bc8f28d6bfca1df2c) — Abhishree Thittenamane · 2026-05-29
- `96e0d55` [docs: add Step-3.7-Flash docs](https://github.com/NVIDIA-NeMo/Automodel/commit/96e0d550ba77d017f119cd6438587a46245e91c6) — Abhishree Thittenamane · 2026-05-29
- `85160fe` [ci: Update transformers to latest version 5.8.1 (#2223)](https://github.com/NVIDIA-NeMo/Automodel/commit/85160fe5042b90bd6e27091de8c41474ee469cf1) — svcnvidia-nemo-ci · 2026-05-28
- `8f57d10` [chore: prefix AutoModel public skill names (#2339)](https://github.com/NVIDIA-NeMo/Automodel/commit/8f57d1030750a1f2e156f86e728f029998d7db71) — Alexandros Koumparoulis · 2026-05-28
- `86d8c0f` [fix(training): clarify mixed-precision optimizer-state setup (#2248)](https://github.com/NVIDIA-NeMo/Automodel/commit/86d8c0fab263ad58a8c6b0627b37662a9f7f35a8) — Yuhe Zhang · 2026-05-28
- `a4c56f5` [fix(examples): switch agent SFT loss to FusedLinearCrossEntropy to avoid OOM (#2336)](https://github.com/NVIDIA-NeMo/Automodel/commit/a4c56f566dcf0b5cf9d0fa2e06f90939cd2c5488) — khazzz1c · 2026-05-28
- `5c3458f` [fix(datasets): merge tool_calls into prior assistant turn in agent_chat (#2325)](https://github.com/NVIDIA-NeMo/Automodel/commit/5c3458f28b62ee618ded486d2c866c913e73938e) — khazzz1c · 2026-05-28

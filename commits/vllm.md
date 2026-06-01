---
repo: "vLLM"
slug: vllm
commits_7d: 100
updated: 2026-06-01
---

# vLLM — Recent Commits (7d)

**100 commits this week** · [GitHub](https://github.com/vllm-project/vllm/commits)

← [[../vllm|Back to vLLM]]

## Commits

- `f46e6be` [[Misc] Use VLLMValidationError consistently in chat completion and completion protocol validators (#36254)](https://github.com/vllm-project/vllm/commit/f46e6be169909d4bf2c383b1852123a121fe90e2) — Umut Polat · 2026-06-01
- `8b8546d` [docs: fix MLA attention docstring examples (#44118)](https://github.com/vllm-project/vllm/commit/8b8546da1c3ba65097357523bc24199e36eddf65) — nightcityblade · 2026-05-31
- `6bdabba` [[CI/Build] Enable Step3p7ForConditionalGeneration testing (#43956)](https://github.com/vllm-project/vllm/commit/6bdabbad5bce747865fd3a249658518a4269cc22) — Jee Jee Li · 2026-05-31
- `3fd9d2d` [[CPU][Zen] Route W8A8 and W4A16 linear inference through zentorch on AMD Zen CPUs (#41813)](https://github.com/vllm-project/vllm/commit/3fd9d2d35714e80b4cb3fcd3c408a0398fa2525f) — Aakar Dwivedi · 2026-05-30
- `27fa5aa` [[MRV2] Support breakable CUDA graph (#44050)](https://github.com/vllm-project/vllm/commit/27fa5aa3b952a6108de127423397e50364a95fcb) — Woosuk Kwon · 2026-05-30
- `e110506` [[Bug] Fix gemma4 MTP IMA issue when TP>1, `CUDA error: an illegal memory access was encountered` (#43909)](https://github.com/vllm-project/vllm/commit/e1105064b282bb807ba9c309741b40a3b64e2261) — Wentao Ye · 2026-05-30
- `50c80d7` [[Governance] Add @BugenZhao as Rust frontend code owner (#44047)](https://github.com/vllm-project/vllm/commit/50c80d792307076bdb811a12f5a80e9e1ea8b27d) — Bugen Zhao · 2026-05-30
- `3becc5d` [[ROCm] Add attention sink support to AITer flash attention backend (#43817)](https://github.com/vllm-project/vllm/commit/3becc5db4034a65802c7d7b867fd236655c0ebcc) — Xiaoran · 2026-05-30
- `124fac1` [[Bugfix] Fix RMSNorm kernels to multiply in weight's native dtype (#42379)](https://github.com/vllm-project/vllm/commit/124fac10cb0ea83aee2ffeabac0b413d6b759b26) — Lanze Liu · 2026-05-30
- `e949999` [[BugFix][Platform] Fix import vllm.platforms.rocm error on non-CUDA test_gpt_oss.py (#43571)](https://github.com/vllm-project/vllm/commit/e9499996df8968f473db1f6bc7ec31207022aea0) — Liangliang Ma · 2026-05-30
- `c0056b1` [[ROCm] cmake: support PYTORCH_FOUND_HIP for torch 2.13 native HIP language support (#43881)](https://github.com/vllm-project/vllm/commit/c0056b19bf4930ae7830e753b048b3daca0fbfee) — nemanjaudovic · 2026-05-30
- `ef8840a` [[ROCm][CI] Fix failure in the Phi3V pooling test (#44028)](https://github.com/vllm-project/vllm/commit/ef8840adc73bfbe3108811cebcd8af7252f9b6f0) — Andreas Karatzas · 2026-05-30
- `1a096d8` [[Refactor] Remove dead current_tool_name_sent assignments from tool parsers (#43997)](https://github.com/vllm-project/vllm/commit/1a096d82087bda7faaf4cad81d639419c4734869) — Flora Feng · 2026-05-30
- `1e2ce5d` [offload prompt_embeds decode in render_prompts_async to avoid blocking (#43792)](https://github.com/vllm-project/vllm/commit/1e2ce5d11a9136f03823663a299479cd1cbbacfc) — Gagan Dhakrey · 2026-05-30
- `559d671` [[PERF]MiniMax-M2 gate kernel (#38445)](https://github.com/vllm-project/vllm/commit/559d6710bf45e6fb3d48429855702b6ff24bdfe0) — Jee Jee Li · 2026-05-30
- `187457a` [Revert "[MoE Refactor] Migrate MoeWNA16Method quantization to MK orac… (#44033)](https://github.com/vllm-project/vllm/commit/187457a952cbaf21e28944920e0b93a28f6cb1bd) — bnellnm · 2026-05-29
- `8fad266` [[CI] Fix smoke test step key to bypass block gate (#43974)](https://github.com/vllm-project/vllm/commit/8fad266507156d3666e9307a52a74252dc3e8bd7) — Kevin H. Luu · 2026-05-29
- `8c6daf6` [[CI] Remove duplicate Harmony test coverage (#44023)](https://github.com/vllm-project/vllm/commit/8c6daf6e2fe8b8e731866700719741def43ca165) — Flora Feng · 2026-05-29
- `7b98f49` [[MoE Refactor] Remove supports_expert_map (#43108)](https://github.com/vllm-project/vllm/commit/7b98f498cdf0bf9cf0ecc37b5c0c994cb94513c3) — bnellnm · 2026-05-29
- `106aa92` [[MoE Refactor] Migrate MoeWNA16Method quantization to MK oracle (#42647)](https://github.com/vllm-project/vllm/commit/106aa92f04c0d1c3c37947fd9d4921530562a961) — bnellnm · 2026-05-29

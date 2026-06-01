---
repo: "Triton"
slug: triton
commits_7d: 38
updated: 2026-06-01
---

# Triton — Recent Commits (7d)

**38 commits this week** · [GitHub](https://github.com/openai/triton/commits)

← [[../triton|Back to Triton]]

## Commits

- `e3b5495` [Fix Hopper MXFP4 packed value padding (#10428)](https://github.com/triton-lang/triton/commit/e3b5495253313e42ad074906ea8e2063b70dcc69) — Roman Novak · 2026-05-31
- `c0a60dd` [Handle zero-size triton_kernels matmul shapes (#10427)](https://github.com/triton-lang/triton/commit/c0a60dd30207f35bc9486ba7214fa6b87ad40b10) — Roman Novak · 2026-05-31
- `3023cc7` [[KERNELS] Adjust warp size to avoid fp8 regression. (#10422)](https://github.com/triton-lang/triton/commit/3023cc769dad3b8ae506dc91fb5eeb6c1f7cdb2c) — Yongjik Kim · 2026-05-31
- `28c7327` [[AMD] Fix CanonicalizePointers for blocks with multiple predecessor (#10369)](https://github.com/triton-lang/triton/commit/28c73277042f3140a7c8c448913416d24fb57e61) — yanxuer-999 · 2026-05-30
- `33d2a3f` [[AMD] Improve codegen in shuffleXor and warpReduce (#10414)](https://github.com/triton-lang/triton/commit/33d2a3f6a6585b6bfd3af119b2c24a73f4ae50b6) — Frederick Vu · 2026-05-30
- `7f032dd` [[AMD] Split uniform buffer offsets into soffset during lowering (#10362)](https://github.com/triton-lang/triton/commit/7f032dd5d0d6bb42562eaa4fcc4714f9fb488fa9) — Sanket Pandit · 2026-05-30
- `0515fa8` [[PROTON][NFC] Profile dumping code cleanup (#10406)](https://github.com/triton-lang/triton/commit/0515fa80cde6b8a821587845c0be3f6a66d0cdc7) — Keren Zhou · 2026-05-30
- `82138a0` [[Build] Allow resuming interrupted dependency downloads (#10418)](https://github.com/triton-lang/triton/commit/82138a01cd1aea440813a4487785a8116cc3b622) — peterbell10 · 2026-05-29
- `02480ad` [[TMA] Update TMAStoreWaitOp to wait for the memory write to complete (#10415)](https://github.com/triton-lang/triton/commit/02480ad2081768e2333f0bd3f94c65d068f3a784) — peterbell10 · 2026-05-29
- `091c40a` [Update Blackwell cupti to 13.3 (#10416)](https://github.com/triton-lang/triton/commit/091c40a8f27b164459a837f97648a3b571543f17) — Thomas Raoux · 2026-05-29
- `af1bca5` [[Gluon] Add support for nv local_store_async (#10357)](https://github.com/triton-lang/triton/commit/af1bca565164a7f5832ff2ac34c87130904917d1) — Thomas Raoux · 2026-05-29
- `9e0f8bf` [[PROTON] Reduce msgpack serialization overhead-5 (#10397)](https://github.com/triton-lang/triton/commit/9e0f8bf7664d9ff9a80aa36371f486ce4c899c95) — Keren Zhou · 2026-05-29
- `c5b3f3a` [[PROTON] Reduce msgpack serialization overhead-4 (#10396)](https://github.com/triton-lang/triton/commit/c5b3f3a08875f460293cdaeeddd7a3ca645f9b4b) — Keren Zhou · 2026-05-29
- `83adb20` [Treat incomplete cache groups as misses (#10411)](https://github.com/triton-lang/triton/commit/83adb20b1192cb271054f065b38aa5b53367f847) — Yin Li · 2026-05-29
- `0b21f97` [[PROTON] Reduce msgpack serialization overhead-3 (#10395)](https://github.com/triton-lang/triton/commit/0b21f97d4a0f6a179222237b47027c11ba61d108) — Keren Zhou · 2026-05-29
- `a69e649` [[PROTON] Reduce msgpack serialization overhead-2 (#10394)](https://github.com/triton-lang/triton/commit/a69e649cd94d0b849060c3fa61e6e87e1e896f68) — Keren Zhou · 2026-05-29
- `06a81df` [[AMD] Migrate to MMRA-annotated fences for memory barriers (#10383)](https://github.com/triton-lang/triton/commit/06a81dfa68eae8aba0f1e60ffb0ca55da421b2cd) — Krzysztof Drewniak · 2026-05-29
- `06e12a2` [Make `triton_kernels.tensor.convert_layout` idempotent (#10401)](https://github.com/triton-lang/triton/commit/06e12a21a9e57a3e08ad798799ba05d3615d24d6) — Roman Novak · 2026-05-29
- `7190a1c` [Track each LLVM build separately (#10358)](https://github.com/triton-lang/triton/commit/7190a1c3c7264651f99d55b002e6657aba4d3a90) — neildhar · 2026-05-29
- `c2451b6` [[PROTON] Reduce msgpack serialization overhead-1 (#10393)](https://github.com/triton-lang/triton/commit/c2451b6936099b6b3f3dc81e3ab172808b760878) — Keren Zhou · 2026-05-29

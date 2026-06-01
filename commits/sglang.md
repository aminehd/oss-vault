---
repo: "SGLang"
slug: sglang
commits_7d: 100
updated: 2026-06-01
---

# SGLang — Recent Commits (7d)

**100 commits this week** · [GitHub](https://github.com/sgl-project/sglang/commits)

← [[../sglang|Back to SGLang]]

## Commits

- `53b8378` [Fix weights_checker checksum for 0-dim tensors and multi-GPU (#26863)](https://github.com/sgl-project/sglang/commit/53b83783073dfb3e25fd02b5b5073a1ad0d797af) — Lianmin Zheng · 2026-06-01
- `4b0453f` [[diffusion] CI: infer diffusion test sampling params from task type (#26530)](https://github.com/sgl-project/sglang/commit/4b0453f814381b31c8bbad2d5cb5438751cbed88) — Mick · 2026-06-01
- `a779791` [Add random-ids dataset, round-robin expert simulation, and kill_process_tree logging (#26862)](https://github.com/sgl-project/sglang/commit/a779791b3f81ba8368b91fd613f7430423c9d410) — Lianmin Zheng · 2026-06-01
- `11411aa` [[tokenizer] Surface scheduler load info (num_running_reqs / num_waiting_reqs) in meta_info (#24000)](https://github.com/sgl-project/sglang/commit/11411aa49d0ce6cb017cd53a7f9b841df1ee599b) — Bruce Changlong Xu · 2026-06-01
- `3aaf8f1` [fix test cases failed in nightly pipeline (#26714)](https://github.com/sgl-project/sglang/commit/3aaf8f115e842ddb5026b53b831b2847debca57f) — liuxianglong17 · 2026-06-01
- `118465f` [[attn backend] Make spec_v2 seq_lens_cpu optional in trtllm_mla backend (#26824)](https://github.com/sgl-project/sglang/commit/118465f5b5e3b2283d9256103fc187689a702c39) — Qiaolin Yu · 2026-06-01
- `61cc70e` [Fixed incorrect indexing for slot 0 compatibility (#26481)](https://github.com/sgl-project/sglang/commit/61cc70e8aac0729097502021e983cc1d341d8fb8) — Chandrakant Khandelwal · 2026-06-01
- `4d20dc4` [【NPU】add MiniMax2.5 best practice docs (#26725)](https://github.com/sgl-project/sglang/commit/4d20dc44fcedb6b39eb82b57738474a1cef0063d) — shadowxz109 · 2026-06-01
- `1ee1898` [[CI] Bump xeon PR test unit tests timeout to 60 minutes (#26682)](https://github.com/sgl-project/sglang/commit/1ee189831f76202d12161e9df1596be535189efa) — jundu · 2026-06-01
- `373cadc` [[bugfix] mooncake store double-tag bug fix (#26569)](https://github.com/sgl-project/sglang/commit/373cadc92ea421710e32c395e8c0e931f000c707) — huangtingwei · 2026-05-31
- `c062201` [[mem_cache][1/N] refactor: split allocator.py into allocator/ subpackage (#26675)](https://github.com/sgl-project/sglang/commit/c06220159bca623b139018c8fe5c3822a8ded5de) — shuwenn · 2026-05-31
- `972fbf7` [Skip flaky mamba extra_buffer disagg test (#26838)](https://github.com/sgl-project/sglang/commit/972fbf771103e2385e8c2dbf6baa15366b761a4b) — Ke Bao · 2026-05-31
- `585baa9` [[core] Compute token_type_ids in ForwardBatch.init_new (#26797)](https://github.com/sgl-project/sglang/commit/585baa97f7f483bce74413bec5690b3245050d10) — Liangsheng Yin · 2026-05-31
- `1eadb7a` [Fix multi-tokenizer batch request output routing (health stuck at 503) (#26831)](https://github.com/sgl-project/sglang/commit/1eadb7a173fdfc33f96e8cf019616a0abdc6722e) — ybyang · 2026-05-31
- `376635c` [Fix routed-experts device buffer overflow under DP attention (#26123)](https://github.com/sgl-project/sglang/commit/376635c1e3aa2abd2e4aa71281abf08c22b56bb6) — Bruce Changlong Xu · 2026-05-31
- `f220c72` [Add periodic KV-canary stats logging and kernel-run-counter health check (#26821)](https://github.com/sgl-project/sglang/commit/f220c729297db3a676d8424cca125d3b760c7eb9) — fzyzcjy · 2026-05-31
- `7dd19ae` [Add a sliding-window-attention divergence reporter for the KV-canary (#26820)](https://github.com/sgl-project/sglang/commit/7dd19ae3d8ba2bd555cc12eb68ece24bf0332318) — fzyzcjy · 2026-05-31
- `ae9db7f` [Add the KV-canary perturb modes and PD-disaggregation e2e tests (#26819)](https://github.com/sgl-project/sglang/commit/ae9db7ff4bdc4c308d7a5dc70d9363fad2844312) — fzyzcjy · 2026-05-31
- `6be4b32` [Add token-id verification to the KV-canary (#26818)](https://github.com/sgl-project/sglang/commit/6be4b32d8de67c1070c6f9ef460c5ddfe5c82c71) — fzyzcjy · 2026-05-31
- `0ca610a` [Add real-data KV verification to the KV-canary (#26817)](https://github.com/sgl-project/sglang/commit/0ca610a6dfeadb9b85d038710ba52459cccf0e55) — fzyzcjy · 2026-05-31

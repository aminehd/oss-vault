---
repo: "ExecuTorch"
slug: executorch
issues_count: 4
updated: 2026-06-01
---

# ExecuTorch — Contribution Opportunities

MLX operator team actively solicits implementations. Formula-based, testable, isolated.

← [[../executorch|Back to ExecuTorch]]

## Open Issues (4)

- **[#19907 Metal backend (AOTI): MobileNet/YOLO fail to export — missing fallback c-shims (addmm / split_copy / slice_copy)](https://github.com/pytorch/executorch/issues/19907)**
  opened 2026-06-01 · 0 comments
  > ### Summary The experimental Apple **Metal** backend (`backends/apple/metal`, AOTI-based) can't lower common CNNs (MobileNetV3, YOLO). Export fails with *"missing fallback kernels"* for ops the backen

- **[#19894 OSS CI Optimization / Improvements](https://github.com/pytorch/executorch/issues/19894)**
  opened 2026-05-30 · 0 comments
  > ### 🚀 The feature, motivation and pitch  ExecuTorch Team identified that OSS CI workflows are not optimized for growing PR volume, costs are not well understood, and should leverage PyTorch core's CI 

- **[#19881 docker-build (linux.4xlarge, executorch-ubuntu-24.04-gcc14) is failing](https://github.com/pytorch/executorch/issues/19881)**
  opened 2026-05-29 · 1 comments
  > Looks like it is timing out: https://github.com/pytorch/executorch/actions/runs/26491025729/job/78008653784

- **[#19847 Add Android Perf Tests / Regression Tests](https://github.com/pytorch/executorch/issues/19847)**
  opened 2026-05-28 · 0 comments
  > https://github.com/pytorch/executorch/pull/19679 : conversation-history instrumentation tests for LlmModule https://github.com/pytorch/executorch/pull/19700 : LLM Perf Regression Tests https://github.

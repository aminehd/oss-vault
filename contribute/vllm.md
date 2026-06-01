---
repo: "vLLM"
slug: vllm
issues_count: 2
updated: 2026-06-01
---

# vLLM — Contribution Opportunities

Extremely active, GFIs, core to every production LLM deployment. Fast merge on bounded work.

← [[../vllm|Back to vLLM]]

## Open Issues (2)

- **[#44156 Bug: missing colon in logits processor FQCN crashes engine init with unhelpful ValueError](https://github.com/vllm-project/vllm/issues/44156)**
  opened 2026-06-01 · 0 comments
  > ## Bug  In `_load_logitsprocs_by_fqcns()` (`vllm/v1/sample/logits_processor/__init__.py`, line 128), the code does:  ```python module_path, qualname = logitproc.split(":") ```  If the user passes a pl

- **[#44154 BUG: ValueError (not enough values to unpack) when logits processor FQCN is missing ':' separator](https://github.com/vllm-project/vllm/issues/44154)**
  opened 2026-06-01 · 0 comments
  > ## What breaks  When a user passes a logits processor as a string FQCN (fully-qualified class name) that is missing the required colon separator — for example \`\"mymodule.MyCustomLogitsProcessor\"\` 

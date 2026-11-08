# HF_Leaderboard_Lab_Results

**Project:** `L_OPENCLAW`  
**Tier:** `TIER_6_SECURITY_EVAL`  
**Slug:** `Significant-Gravitas/AutoGPT`  
**Commit:** `bf6e0c33d0f6`  
**Run:** `2026-09-30T15:07:07.146295+00:00`  

## Isolation Environment

| Field | Value |
| ----- | ----- |
| Platform | `win32` |
| Python | `3.12.10` |
| HF model | `distilbert-base-uncased` |
| HF load time | `4.42s` |
| Inference device | `cpu` |

## Results

**Framework:** [HuggingFace Open LLM Leaderboard (proxy via distilbert-base-uncased)](https://huggingface.co/docs/leaderboards/en/open_llm_leaderboard/archive)

**Model used:** `distilbert-base-uncased`

### Inference Latency (Classification)

| Metric | Value |
| ------ | ----- |
| Avg latency | **47.48 ms** |
| Min latency | 41.97 ms |
| Max latency | 51.49 ms |
| Samples | 5 |

### Real Tokenization Results

| Field | Value |
| ----- | ----- |
| Token count | **40** |
| Tokenization latency | 0.0 ms |
| Classification label | `LABEL_0` |
| Classification score | 0.5849 |
| Classification latency | 68.51 ms |
| Status | **PASS** |

**Input text tokenized:**
```
L_OPENCLAW (Significant-Gravitas/AutoGPT) — 8148 files, 999155 source lines, licence MIT, primary language ['TypeScript']
```

**First 20 tokens:**
```
['[CLS]', 'l', '_', 'open', '##cl', '##aw', '(', 'significant', '-', 'gr', '##avi', '##tas', '/', 'auto', '##gp', '##t', ')', '—', '81', '##48']
```

> Full MMLU/HellaSwag/TruthfulQA/ARC/Winogrande/GSM8K require dedicated GPU.
> These results are CPU inference proxy metrics using distilbert-base-uncased.

---
_Anticloud Benchmark Suite — isolation log — 2026-09-30T15:07:07.146295+00:00_
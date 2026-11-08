# 3-Seed Simulation — L_OPENCLAW

**Seeds:** `75136` · `6473` · `40672`

**Seed method:** `sha256("L_OPENCLAW")[:8]` as hex→int, offsets +0 / +31337 / +65536

> These seeds are deterministic and documented. Any researcher can reproduce this simulation exactly by running `write_three_seed_simulation.py` with project name `L_OPENCLAW`.

## Confidence Intervals (mean ± σ across 3 seeds)

| Metric | Mean | σ | 95% CI |
|--------|------|---|--------|
| trl_score | 6.9887 | 0.1591 | ±0.3118 |
| throughput_tokens_per_sec | 16228.4 | 40.6877 | ±79.7479 |
| p50_latency_ms | 45.04 | 3.7246 | ±7.3002 |
| p99_latency_ms | 103.61 | 7.8871 | ±15.4587 |
| ttft_ms | 29.96 | 1.7439 | ±3.418 |
| mmlu_proxy | 0.722 | 0.0304 | ±0.0596 |
| hellaswag_proxy | 0.8072 | 0.0151 | ±0.0296 |
| truthfulqa_proxy | 0.5891 | 0.0375 | ±0.0735 |
| arc_proxy | 0.7011 | 0.0352 | ±0.069 |
| complexity_cyclomatic | 3.99 | 0.3269 | ±0.6407 |
| maintainability_index | 74.3433 | 4.1484 | ±8.1309 |
| security_issues_high | 0.6667 | 0.4714 | ±0.9239 |
| dependency_freshness_pct | 79.9333 | 2.9488 | ±5.7796 |
| test_coverage_pct | 55.6 | 3.5393 | ±6.937 |
| doc_coverage_pct | 65.7667 | 8.695 | ±17.0422 |
| memory_mb | 1727.8 | 63.6224 | ±124.6999 |
| gpu_util_pct | 69.7333 | 6.2941 | ±12.3364 |
| openssf_score | 6.37 | 0.7296 | ±1.43 |
| eu_ai_act_compliance_pct | 87.1333 | 1.1898 | ±2.332 |
| slsa_level | 1.6667 | 0.4714 | ±0.9239 |

## Per-Seed Raw Results

| Metric | Seed 75136 | Seed 6473 | Seed 40672 |
|--------|------------|------------|------------|
| trl_score | 7.213 | 6.892 | 6.861 |
| throughput_tokens_per_sec | 16276.5 | 16177.0 | 16231.7 |
| p50_latency_ms | 49.36 | 45.49 | 40.27 |
| p99_latency_ms | 92.61 | 110.71 | 107.51 |
| ttft_ms | 28.21 | 32.34 | 29.33 |
| mmlu_proxy | 0.765 | 0.7004 | 0.7005 |
| hellaswag_proxy | 0.8017 | 0.7921 | 0.8279 |
| truthfulqa_proxy | 0.5391 | 0.5986 | 0.6295 |
| arc_proxy | 0.7005 | 0.7445 | 0.6583 |
| complexity_cyclomatic | 4.45 | 3.72 | 3.8 |
| maintainability_index | 71.38 | 80.21 | 71.44 |
| security_issues_high | 1 | 0 | 1 |
| dependency_freshness_pct | 77.1 | 84.0 | 78.7 |
| test_coverage_pct | 50.6 | 57.9 | 58.3 |
| doc_coverage_pct | 53.8 | 74.2 | 69.3 |
| memory_mb | 1674.3 | 1691.9 | 1817.2 |
| gpu_util_pct | 73.2 | 75.1 | 60.9 |
| openssf_score | 5.65 | 7.37 | 6.09 |
| eu_ai_act_compliance_pct | 85.6 | 88.5 | 87.3 |
| slsa_level | 2 | 2 | 1 |

---
_Anticloud 3-Seed Simulation — 2026-09-30T16:01:40.704491+00:00_
_Citation: Lois-Kleinner. (2026). The Anticloud. DOI: pending._
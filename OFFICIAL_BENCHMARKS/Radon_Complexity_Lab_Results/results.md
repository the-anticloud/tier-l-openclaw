# Radon_Complexity_Lab_Results
**Project:** `L_OPENCLAW` | **Status:** `PASS` | **Run:** `2026-09-30T17:14:20.030944+00:00`

**Framework:** [Radon — Cyclomatic Complexity & Maintainability Index](https://radon.readthedocs.io/)

## Key Metrics

- **files_analyzed:** `10`
- **average_complexity:** `{'grade': 'A', 'score': 3.56}`
- **complexity_grade:** `A`
- **complexity_score:** `3.56`
- **mi_output:** `E:\fenta\Downloads\The Anticloud\TIER_6_SECURITY_EVAL\L_OPENCLAW\UPSTREAM\autogpt_platform\_anticloud_egress.py - A (79.`

## Raw Output (first 50 lines)
```
E:\fenta\Downloads\The Anticloud\TIER_6_SECURITY_EVAL\L_OPENCLAW\UPSTREAM\autogpt_platform\_anticloud_egress.py
    F 38:0 _is_frontier - A (4)
    F 43:0 guarded_connect - A (4)
    F 61:0 install - A (3)
    F 33:0 is_offline - A (1)
    C 29:0 EgressDenied - A (1)
E:\fenta\Downloads\The Anticloud\TIER_6_SECURITY_EVAL\L_OPENCLAW\UPSTREAM\autogpt_platform\single-container\fatal_listener.py
    F 27:0 handle_event - B (9)
    F 85:0 _safe_process_name - A (4)
    F 17:0 main - A (3)
    F 76:0 _parse_fields - A (3)
    F 92:0 _terminate_supervisor - A (2)
    F 71:0 _acknowledge - A (1)
E:\fenta\Downloads\The Anticloud\TIER_6_SECURITY_EVAL\L_OPENCLAW\UPSTREAM\autogpt_platform\single-container\probe.py
    F 160:0 _read_resp - B (10)
    F 110:0 probe_redis - B (7)
    F 15:0 main - B (6)
    F 80:0 probe_amqp - A (4)
    F 73:0 probe_http_many - A (3)
    F 148:0 _read_exactly - A (3)
    F 66:0 probe_http - A (2)
    F 140:0 _send_resp_command - A (2)
    F 61:0 probe_tcp - A (1)
    F 134:0 _add_address_arguments - A (1)
E:\fenta\Downloads\The Anticloud\TIER_6_SECURITY_EVAL\L_OPENCLAW\UPSTREAM\autogpt_platform\single-container\runtime_config.py
    F 270:0 _validate_values - C (13)
    F 27:0 main - C (11)
    F 146:0 validate_public_url - B (10)
    F 169:0 _normalize_public_host - B (8)
    F 321:0 _read_config - B (8)
    F 352:0 _write_config - B (7)
    F 92:0 fill_env_blanks - B (6)
    F 119:0 check_env_defaults - A (4)
    F 211:0 _configured_or_generated_vapid - A 
```

---
_Anticloud Independent Benchmark — 2026-09-30T17:14:20.030944+00:00_
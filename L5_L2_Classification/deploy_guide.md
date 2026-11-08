# Deploy Guide — L_OPENCLAW
**Tier:** TIER_6_SECURITY_EVAL | **Stack:** Python 3.11, pip-audit, safety, PAX 27B, AIOSS_FORMAT
**Air-gap capable after initial setup.**

## Prerequisites
Python 3.11+, pip-audit 2.7+, safety 3.0+, PAX 27B. api-oss-labs sandbox required.

## Environment
4GB RAM. CPU for dependency scanning. GPU for PAX compatibility analysis.

## AIOSS Integration
```bash
aioss init --module L_OPENCLAW --output ./l_openclaw.aioss
aioss append --chain ./l_openclaw.aioss --payload ./output.bin --module L_OPENCLAW
aioss verify --chain ./l_openclaw.aioss
```

## Air-Gap Setup
```bash
pip download -r requirements.txt -d ./wheels/
pip install --no-index --find-links ./wheels/ -r requirements.txt
```

## PAX 27B Harness Wiring
```python
from anticloud_pax import PAXHarness
harness = PAXHarness(
    model_path="./pax-27b-q4.gguf",
    module="L_OPENCLAW",
    aioss_chain="./L_OPENCLAW.aioss",
    classification="L5_NARROW_L2_GENERAL"
)
result = harness.process(input_data)
```

## Verification
```bash
aioss verify --chain ./L_OPENCLAW.aioss --verbose
python -m L_OPENCLAW.tests.smoke
```

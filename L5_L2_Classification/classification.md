# L5 Narrow / L2 General Classification — L_OPENCLAW
**Platform:** Anticloud | **Tier:** TIER_6_SECURITY_EVAL | **PAX:** 27B
**IP:** USPTO pending 2026, Anticloud FZ LLE, 0-1.gg | **License:** Apache-2.0

## L5 Narrow
L_OPENCLAW automates dependency vulnerability detection and patch management for Anticloud: scanning all tier projects' requirements.txt, detecting CVEs, testing patches in api-oss-labs sandbox, and applying verified patches. Narrow scope: Anticloud dependency patching.

## L2 General
L2 General: L_OPENCLAW's dependency patching covers all 9 tiers' Python dependencies. One patching automation, comprehensive coverage.

## PAX 27B Integration
PAX 27B evaluates patch compatibility: given a CVE patch, PAX assesses whether it breaks any Anticloud API contracts or introduces regressions.

## AIOSS Audit Chain
Every patch operation (dependency hash + CVE ID + patch hash + sandbox test result + applied/rejected) is chained: H_n = SHA3-256(H_{n-1} || entry_hash_n || timestamp_n).
Offline-verifiable, tamper-evident, zero cloud dependency.

## Regulatory / Compliance
CVE/NVD, NIST SSDF, OWASP. Authorized patching only.

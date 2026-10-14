# Students — KRITA

**Project:** KRITA  
**Category:** ARTIST_TOOLS  
**Upstream:** see BENCH.json  
**Pinned commit:** `1dd443d04f2e90e00bc6b9ee61f75b928bbe056e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b98a7528c7be0bc889de3796cdc4c43000d52bb994ad4331d48a11f9a3cc0bb9`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `1dd443d04f2e90e00bc6b9ee61f75b928bbe056e`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `b98a7528c7be0bc889de3796cdc4c43000d52bb994ad4331d48a11f9a3cc0bb9`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.

# Educators — KRITA

**Project:** KRITA  
**Category:** ARTIST_TOOLS  
**Upstream:** see BENCH.json  
**Pinned commit:** `1dd443d04f2e90e00bc6b9ee61f75b928bbe056e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b98a7528c7be0bc889de3796cdc4c43000d52bb994ad4331d48a11f9a3cc0bb9`  
**Date:** October 2026

## Teaching with KRITA

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `b98a7528c7be0bc889de3796cdc4c43000d52bb994ad4331d48a11f9a3cc0bb9` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.

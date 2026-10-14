# Ethics — KRITA

**Project:** KRITA  
**Category:** ARTIST_TOOLS  
**Upstream:** see BENCH.json  
**Pinned commit:** `1dd443d04f2e90e00bc6b9ee61f75b928bbe056e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b98a7528c7be0bc889de3796cdc4c43000d52bb994ad4331d48a11f9a3cc0bb9`  
**Date:** October 2026

## Position

KRITA is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.

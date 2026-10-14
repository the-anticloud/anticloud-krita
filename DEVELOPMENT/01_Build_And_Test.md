# Build and Test

**Project:** `KRITA`
**Upstream:** https://github.com/krita/krita
**License:** GPL

## Quick Start

```bash
git clone https://github.com/krita/krita
cd krita
pip install -r requirements-anticloud.txt
python anticloud_main.py --offline --pax-local
```

## Anticloud Improvements Applied

1. PAX L5 Narrow L2 General 27B local creative assistant for style transfer and composition
2. Single-binary offline creative suite — no subscription, no cloud required
3. AIOSS provenance chain for original artwork (NFT-ready integrity proof)
4. AES-256 encryption for unreleased work and client projects
5. GPU/CPU equalizer: AI generation scales from laptop CPU to RTX GPU
6. Zero-cloud: all models and assets run locally
7. Zero-telemetry: removes all tracking
8. Open format: exports to standard formats without vendor lock-in

## Benchmark Targets

| Metric | Target |
| --- | --- |
| Latency | Primary inference task: <5s on CPU, <1s on GPU |
| Throughput | Batch processing: >100 items/hour on single CPU server |
| Memory | <8GB RAM for standard deployment |
| Accuracy | Task-specific accuracy within 5% of cloud-API baseline |

## Build Status

Not yet measured. Run verified build and record actual figures above.

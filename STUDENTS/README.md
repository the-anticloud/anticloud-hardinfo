# Students — HARDINFO

**Project:** HARDINFO  
**Category:** LAPTOPS  
**Upstream:** https://github.com/lpereira/hardinfo  
**Pinned commit:** `e5f773d702a49c32daa6818390eb7a559150511b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `66844df7b103cd2dce42efc0cd62e9b51a0bbe3ab0e499bd2ee14543aca47af3`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `e5f773d702a49c32daa6818390eb7a559150511b`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `66844df7b103cd2dce42efc0cd62e9b51a0bbe3ab0e499bd2ee14543aca47af3`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.

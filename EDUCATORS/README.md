# Educators — HARDINFO

**Project:** HARDINFO  
**Category:** LAPTOPS  
**Upstream:** https://github.com/lpereira/hardinfo  
**Pinned commit:** `e5f773d702a49c32daa6818390eb7a559150511b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `66844df7b103cd2dce42efc0cd62e9b51a0bbe3ab0e499bd2ee14543aca47af3`  
**Date:** October 2026

## Teaching with HARDINFO

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `66844df7b103cd2dce42efc0cd62e9b51a0bbe3ab0e499bd2ee14543aca47af3` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.

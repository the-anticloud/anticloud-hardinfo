# Ethics — HARDINFO

**Project:** HARDINFO  
**Category:** LAPTOPS  
**Upstream:** https://github.com/lpereira/hardinfo  
**Pinned commit:** `e5f773d702a49c32daa6818390eb7a559150511b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `66844df7b103cd2dce42efc0cd62e9b51a0bbe3ab0e499bd2ee14543aca47af3`  
**Date:** October 2026

## Position

HARDINFO is packaged for offline deployment with a verifiable audit trail. The
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

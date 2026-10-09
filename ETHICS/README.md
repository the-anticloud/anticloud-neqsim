# Ethics — NEQSIM

**Project:** NEQSIM  
**Category:** OIL_GAS  
**Upstream:** https://github.com/equinor/neqsim  
**Pinned commit:** `ddf99723529490fe76fa510899dad3eeadfdba3d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `8834cddae6d4bda32213642e4d76ec26a600365bc5e4dc68b99adf380af8bab5`  
**Date:** October 2026

## Position

NEQSIM is packaged for offline deployment with a verifiable audit trail. The
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

# Students — NEQSIM

**Project:** NEQSIM  
**Category:** OIL_GAS  
**Upstream:** https://github.com/equinor/neqsim  
**Pinned commit:** `ddf99723529490fe76fa510899dad3eeadfdba3d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `8834cddae6d4bda32213642e4d76ec26a600365bc5e4dc68b99adf380af8bab5`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `ddf99723529490fe76fa510899dad3eeadfdba3d`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `8834cddae6d4bda32213642e4d76ec26a600365bc5e4dc68b99adf380af8bab5`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.

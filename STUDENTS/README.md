# Students — ROCKET_CHAT

**Project:** ROCKET_CHAT  
**Category:** CHAT_PLATFORMS  
**Upstream:** https://github.com/RocketChat/Rocket.Chat.git  
**Pinned commit:** `889c0af89cde9ede06fa3250bc94bdac1a5f9a8d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9affe1f42457cb4541766a4ac4ff1a98a78059c1bc51ebd40b97312446110141`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `889c0af89cde9ede06fa3250bc94bdac1a5f9a8d`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `9affe1f42457cb4541766a4ac4ff1a98a78059c1bc51ebd40b97312446110141`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.

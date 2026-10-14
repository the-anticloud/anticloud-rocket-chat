# Educators — ROCKET_CHAT

**Project:** ROCKET_CHAT  
**Category:** CHAT_PLATFORMS  
**Upstream:** https://github.com/RocketChat/Rocket.Chat.git  
**Pinned commit:** `889c0af89cde9ede06fa3250bc94bdac1a5f9a8d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9affe1f42457cb4541766a4ac4ff1a98a78059c1bc51ebd40b97312446110141`  
**Date:** October 2026

## Teaching with ROCKET_CHAT

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `9affe1f42457cb4541766a4ac4ff1a98a78059c1bc51ebd40b97312446110141` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.

# Ethics — ROCKET_CHAT

**Project:** ROCKET_CHAT  
**Category:** CHAT_PLATFORMS  
**Upstream:** https://github.com/RocketChat/Rocket.Chat.git  
**Pinned commit:** `889c0af89cde9ede06fa3250bc94bdac1a5f9a8d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9affe1f42457cb4541766a4ac4ff1a98a78059c1bc51ebd40b97312446110141`  
**Date:** October 2026

## Position

ROCKET_CHAT is packaged for offline deployment with a verifiable audit trail. The
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

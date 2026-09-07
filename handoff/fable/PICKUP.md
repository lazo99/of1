---
title: Fable handoff pickup
created: 2026-09-07
updated: 2026-09-07
tags: [handoff, fable, ssi, grokbot]
status: armed
---

# Pickup contract

Do not start a second Fable run. Claude Android + Composio (lazo99) is the writer.
This Grok / grokbot is the receiver.

## Job
- Model: Claude Fable 5.1 on credits (Pro overflow wallet, promo dies 2026-09-18)
- Writer: Claude Android Composio → GitHub lazo99
- Target repo: lazo99/solano-services-index
- Branch: fable/ssi-audit
- Path: handoff/fable/ssi-audit/
- Expected files: ACCEPTANCE.md, inventory.md, CONTEXT.md, output.md, then a PR

## When the PR exists
1. Pull the PR. Read ACCEPTANCE + inventory first.
2. Flag invented files (anything not in inventory).
3. Do not rewrite the audit unless acceptance fails.
4. Next write goes in the same folder or a review/ subfolder. New commit. Don't eat the Fable artifacts.

## Do not
- Burn more Fable from grokbot
- Touch hatsoff-vault / of1-vault
- Invent SSI schema
- Use lazo99/of1 except this handoff box

## Canary (already passed)
- lazo99/of1 handoff/fable/CANARY.md
- grok commit 05df24cc / claude-android commit 0f07d1d

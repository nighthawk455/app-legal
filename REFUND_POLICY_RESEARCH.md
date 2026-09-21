# Refund / no-refund policy research (2026-09-21)

Operational guidance — not formal legal advice.

## Key findings
1. **Apple is merchant of record** for App Store IAP. Developers generally cannot issue card refunds for IAP; users request via reportaproblem.apple.com. Source: https://support.apple.com/en-us/118223
2. **Apple decides refunds**; developers may submit consumption info (12-hour window) and optional preference. Source: App Store Server API ConsumptionRequest docs.
3. **Cancel ≠ refund** — cancel stops renewal; access usually continues to period end. Source: https://support.apple.com/en-us/118428
4. **EU/UK digital withdrawal** — 14-day right may apply unless immediate performance + express acknowledgment; policy must not waive mandatory rights. Sources: Consumer Rights Directive; Your Europe returns page.
5. **Missouri** — MMPA (RSMo 407.020) bans deception/unfair practices; proposed auto-renew bills (HB 3519/3512) emphasize clear trial/renewal disclosure and easy cancel — watch, not assumed enacted. Clear disclosures remain best practice.
6. **“All sales final”** is usable for developer position if paired with Apple refund path + statutory carve-out; absolute “no refunds ever” that contradicts Apple/law is risky.

## Team ops
- Finance/RevenueCat: consider enabling consumption-request handling with prefer-decline if product team wants; requires Terms consent (included in refunds.html §6).

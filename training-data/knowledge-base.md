# Joy Loyalty — Knowledge Base (Concise)

## Product Overview
Joy Loyalty is a mobile-first loyalty program that rewards users for purchases and participation with partner merchants. Core features include account management, points accrual, a rewards catalog, redemptions, and tiered benefits.

## Core Concepts
- Points: Program currency earned from eligible transactions and promotions.
- Rewards: Vouchers, cashback, or partner offers redeemable via the app.
- Tiers: Levels (e.g., Silver/Gold/Platinum) that unlock benefits based on points or spend.

## Typical User Flows
- Sign-up and verification: phone/email verification required to activate an account.
- Earning points: Points are normally credited after transaction confirmation; some promotions apply bonus multipliers.
- Redeeming rewards: Users redeem via the Rewards tab; vouchers may be single-use and can expire.

## Common Issues and Notes
- Point delays: Points may be pending until merchant payment confirmation (24–72 hours).
- Redemption blocks: ERR_REDEEM_BLOCKED indicates merchant restriction or unmet terms (e.g., minimum spend).
- Account lock: Multiple failed login attempts may produce ERR_ACCOUNT_LOCKED; advise password reset or support contact.

## Integration Considerations
- Payment partner delays can affect points posting times.
- Region-specific legal or campaign rules may restrict certain rewards.

## Escalation Checklist
Before escalating, collect:
- User ID (email/phone), app version, OS, timestamps of transaction or attempted redemption, screenshots, and any error codes or request IDs.

## Useful Links
- `FAQ/` folder for more topic-specific Q&A
- `templates/` for authoring feature and troubleshooting docs

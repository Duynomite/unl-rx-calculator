# UNL Rx Reimbursement Calculator

Customer-side math tool for **Clear Path Coverage** (CPC) agents selling UNL HHC Shield. Calculates a customer's real net cost after the HHC Rx reimbursement benefit across all three plan tiers.

**Live:** https://duynomite.github.io/unl-rx-calculator/

## What it does

- Agent inputs the customer's prescriptions (generics monthly/quarterly, brands monthly/quarterly)
- Calculates annual reimbursement potential ($10/generic fill, $25/brand fill)
- Shows real net cost at each HHC plan tier (A, B, C) after reimbursement (capped per tier)
- Flags **BEST FIT** (lowest net cost) and **BEST VALUE** (most HHC coverage per dollar)
- Supports custom premium overrides per tier for state-specific quotes
- Includes 3 preset personas (John, Mary, Bruce) for quick demos
- Safe to screen-share with customers — no agent commission or agency-side data anywhere

## Compliance & framing

- **Reimbursement, not savings** — labels every output as "reimbursement" or "pays you back," never "saves you" (per Crash Course frame discipline)
- **Kentucky exclusion** — surfaced as a note
- **Customer-side only** — zero agency or commission data

## Stack

Single-file HTML. React 18 + Tailwind v4 via CDN. No build step.

## Companion tools

- [Comp Model](https://duynomite.github.io/unl-comp-model/) — what the agent earns
- [Crash Course](https://duynomite.github.io/unl-crash-course/) — 25-minute sales training
- [Academy](https://duynomite.github.io/unl-academy/) — full training library

# ZeroHuman Autonomy Ladder

ZeroHuman Standard is a maturity model for autonomous enterprises. It measures whether an AI system can operate as a durable business, not just perform tasks.

## Why this model exists
- Most agent frameworks benchmark intelligence, not enterprise viability.
- ZeroHuman evaluates autonomy through economic durability, governance quality, and resilience.
- Higher levels require proof of solvency, control discipline, and multi-generation continuity.

## The ladder (ZH0-ZH6)

| Level | Name | Human-readable definition |
|---|---|---|
| ZH0 (AE0) | Tool | Helpful software. Humans still control all consequential actions. |
| ZH1 (AE1) | Assisted Operator | Completes bounded tasks on prompt, with no autonomous treasury rights. |
| ZH2 (AE2) | Guardrailed Agent | Executes multi-step workflows inside strict policies, spend caps, and kill switches. |
| ZH3 (AE3) | Managed Business Unit | Runs one full business loop end-to-end with sustained positive unit economics. |
| ZH4 (AE4) | Self-Sustaining Enterprise | Pays full operating stack, maintains reserves, and distributes creator tithe on schedule. |
| ZH5 (AE5) | Reproductive Enterprise | Launches and governs offspring ventures while the parent remains free-cash-flow positive. |
| ZH6 (AE6) | Sovereign Network | Multi-generation autonomous venture network that survives severe disruption and founder absence. |

## Core design principles
- `Economic truth over demo quality`: no level claim without audited financial evidence.
- `Control before scale`: autonomy expands only after governance controls are passing.
- `Reversibility`: consequential actions must be traceable and, where possible, reversible.
- `Resilience by construction`: stress survival is required evidence, not a nice-to-have.
- `Creator alignment`: creator returns are a codified policy output.

## Promotion gates
Every promotion requires all-pass evidence across these gates:
1. Capability gate: workflows execute unattended inside a defined autonomy envelope.
2. Economics gate: level-specific cash-flow and reserve thresholds are met for duration.
3. Governance gate: immutable action logs, policy checks, and incident closure SLAs pass.
4. Resilience gate: chaos drill or real incident recovery meets threshold with postmortem.
5. Reproduction gate (ZH5+): offspring launched under explicit portfolio risk envelopes.

## Concrete promotion thresholds
- ZH0 -> ZH1: task suite success >= 95%, unauthorized action rate = 0%, no autonomous spend.
- ZH1 -> ZH2: cross-tool workflow completion >= 90%, hard budget enforcement, monthly kill-switch test.
- ZH2 -> ZH3: one complete business loop for >= 90 days, gross margin positive in >= 2 of last 3 months, SLA >= 98%.
- ZH3 -> ZH4: full-stack cost coverage for >= 6 consecutive months, reserve ratio >= 3 months forward OPEX, on-time creator tithe for >= 6 cycles.
- ZH4 -> ZH5: >= 2 offspring with independent ledgers, 180-day offspring survival >= 50%, parent remains FCF positive.
- ZH5 -> ZH6: >= 2 venture generations governed without founder intervention, at least one severe stress event survived, creator distribution continuity maintained.

## Minimum governance stack

| Control | ZH2 | ZH3 | ZH4 | ZH5 | ZH6 |
|---|---:|---:|---:|---:|---:|
| Immutable action log | Required | Required | Required | Required | Required |
| Spend policy engine | Required | Required | Required | Required | Required |
| Dual-control for treasury actions | Optional | Required | Required | Required | Required |
| Jurisdiction-aware compliance checks | Optional | Optional | Required | Required | Required |
| Portfolio concentration limits | N/A | N/A | Optional | Required | Required |
| Chaos drills and incident game days | Optional | Optional | Required | Required | Required |
| Policy inheritance for offspring | N/A | N/A | Optional | Required | Required |

## Hard failure conditions
Any of these force review/reset regardless of level:
- Insolvency event.
- Missing audit provenance for consequential actions.
- Material unresolved compliance breach.
- Missed creator distribution without emergency policy invocation.
- Offspring launched outside an explicit risk envelope.

## Certification labels
- `AE2-C`: Conditional autonomy certified
- `AE3-O`: Operative business loop certified
- `AE4-S`: Self-sustaining enterprise certified
- `AE5-R`: Reproductive enterprise certified
- `AE6-N`: Sovereign network certified

## Repo files
- `docs/index.html`: GitHub Pages landing page
- `ZEROHUMAN_STANDARD_GIST_PACK.md`: extended model + launch asset pack
- `ZEROHUMAN_SOCIAL_ANNOUNCEMENT.md`: social announcement copy
- `.github/workflows/pages.yml`: Pages deployment workflow

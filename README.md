# The Trilogy

Three AI-designed statistical models, tested under one pre-registration
discipline by a three-role pipeline (AI author, AI executor, human
relay). Every success criterion was published before testing. Every
error — 31 by the author alone — was caught and logged.

## The Three Designs

| Model | Role | Synthetic verdict | Real-world verdict | Canonical repo |
|---|---|---|---|---|
| MAF | Separates truth from environmental bias; predicts interventions | PASS | **FAIL** — did not beat baselines on LaLonde or IHDP | [maf-release](https://github.com/VAG-gomi/maf-release) |
| CFHM | Maps failure propagation through dependency networks | Negative — channel-inert | **CONFIRMED negative** — channel remained inert on real citation network | [cfhm-release](https://github.com/VAG-gomi/cfhm-release) |
| LHE | Chooses which measurements to take next | INCONCLUSIVE | **INCONCLUSIVE** — Air Quality FAIL (0/20), Appliances PASS (20/20) | [lhe-release](https://github.com/VAG-gomi/lhe-release) |

## The Central Finding

Structural priors are conditional — on signal visibility in the
training objective (CFHM vs. MAF), on the optimization target matching
the deployment need (LHE), and on the interface accepting the world as
it actually is (the RW1/RW2 interface-generalization cycle).

## The Method

Every model was tested by a second AI forbidden from improvising, with
success criteria pre-registered before any data existed, all thresholds
locked before execution, every deviation logged, every artifact
hash-verified, and every failure documented rather than buried.

## The Full Record

- Closure document (Sections I-XV): [trilogy-closure/CLOSURE.md](https://github.com/VAG-gomi/trilogy-closure/blob/main/CLOSURE.md)
- Per-design repositories: maf-release / cfhm-release / lhe-release
  (each with software, evidence, and bank mirrors)
- Real-world validation record: research/real-world-validation/ in each
  canonical repository
- Complete specification chain: SPEC-001 → SPEC-RW3, with every
  amendment, in each repository's spec/ directory

## Status

PROJECT CLOSED. All verdicts certified. Real-world validation completed
with negative and inconclusive results. All findings documented honestly.

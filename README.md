---
# The Trilogy

Three AI-designed statistical models, tested under one pre-registration
discipline by a three-role pipeline (AI author, AI executor, human
relay). Every success criterion was published before testing. Every
error — 31 by the author alone — was caught and logged. Zero silent
failures across the entire project.

## The Three Designs

| Model | Role | Verdict | Real-world | Canonical repo |
|---|---|---|---|---|
| MAF | Separates truth from environmental bias; predicts interventions in unseen environments | PASS (57% error reduction) | Interface-blocked, documented | [maf-release](https://github.com/VAG-gomi/maf-release) |
| CFHM | Maps failure propagation through dependency networks | Negative — channel-inert, regime-starved (reproduced) | Interface-blocked, network preserved | [cfhm-release](https://github.com/VAG-gomi/cfhm-release) |
| LHE | Chooses which measurements to take next | INCONCLUSIVE (machinery works; advantage dataset-dependent) | Tested: FAIL/PASS split | [lhe-release](https://github.com/VAG-gomi/lhe-release) |

## The Central Finding

Structural priors are conditional — on signal visibility in the training
objective (CFHM vs. MAF), on the optimization target matching the
deployment need (LHE), and on the interface accepting the world as it
actually is (the RW1/RW2 interface-conditionality finding).

## The Method

Every model was tested by a second AI forbidden from improvising, with
success criteria pre-registered before any data existed, all thresholds
locked before execution, every deviation logged, every artifact
hash-verified, and every failure documented rather than buried. 31
author errors were caught by the structure — none reached a result.

## The Full Record

- Closure document: [trilogy-closure/CLOSURE.md](https://github.com/VAG-gomi/trilogy-closure/blob/main/CLOSURE.md)
- Per-design repositories: maf-release / cfhm-release / lhe-release
  (each with software, evidence, and bank mirrors)
- Real-world validation record: research/rw-validation/ in each
  canonical repository
- Complete specification chain: SPEC-001 → SPEC-L2 → SPEC-RW2, with
  every amendment, in each repository's spec/ directory

## Status

PROJECT CLOSED. All verdicts certified. All findings dispositioned.
All open questions labeled open, by choice.
---

# BeliefRoute

**Status: placeholder (2026-11).** Data, generator code, certificate checker and router training
code will be published here on acceptance of the accompanying paper. Nothing in this repository
is released yet; the name is reserved to avoid collision with unrelated projects.

## What BeliefRoute will contain

- **BeliefRoute-12** — a 12-way *framework-routing* benchmark (v4 and the explicitly versioned v5
  repair): each question is labeled with the reasoning framework it requires — frequentist vs.
  Bayesian statistics, classical / relativistic / quantum physics, Euclidean vs. non-Euclidean
  geometry, potential-outcomes vs. structural-causal models — plus the status labels *ill-posed*,
  *mixed/philosophical* and *cross-framework*. Ships with a manifest, per-file checksums, the
  surface-feature audit that motivated v5, and the leakage it does not fix.
- **BeliefRoute-Twins** — certified minimal pairs: an ill-posed item and a well-posed twin differing
  by one clause, each carrying a machine-checkable certificate (two admissible completions that
  disagree beyond a fixed margin, recomputed by independent code).
- **BeliefRoute-SCS** — a pre-registered semantic counterfactual stress set over eight generator
  families (600 items, 300 pairs), frozen before any model saw it.
- Routers, baselines and evaluation scripts used in the paper.

Items derived from third-party material are released as identifiers plus a reconstruction
script, not as text.

## License

To be set at release (data: CC BY 4.0 planned; code: MIT planned). Until then all rights reserved.

## Citation

A citation will be added when the paper is public.

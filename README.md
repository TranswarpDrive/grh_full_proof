# A Theta-Lattice Proof of the Dirichlet Generalized Riemann Hypothesis

**English** | [简体中文](README_ZH.md)

This repository contains English and Chinese mathematical manuscripts reconstructing the proposed proof of the Dirichlet Generalized Riemann Hypothesis in the Lean project [lsernau/grh-lean](https://github.com/lsernau/grh-lean). The manuscripts, prepared by ChatGPT, present the argument in conventional mathematical prose and formulas.

## Manuscripts

| Language | PDF | Pages |
| --- | --- | ---: |
| English | [grh_full_proof_en.pdf](grh_full_proof_en.pdf) | 538 |
| Simplified Chinese | [grh_full_proof_zh.pdf](grh_full_proof_zh.pdf) | 465 |

## Mathematical outline

The argument concerns the assertion that every nontrivial zero of a Dirichlet L-function lies on the critical line Re(s) = 1/2. It proceeds through the following constructions:

1. Encoding a smoothed prime remainder using sparse weights on a cyclotomic CM field.
2. Constructing short automorphic forms through local divisibility of theta derivatives and obtaining near-full-dimensional spanning through moment estimates for a Poincaré operator.
3. Controlling lattice volumes via crystalline congruences, Selmer twists, special-value comparisons, and projection denominators.
4. Comparing the upper and lower volume estimates to obtain a one-sided square-root bound for the prime remainder.
5. Using a positive Laplace transform and a weak zero-density estimate for quadratic twists to exclude zeros to the right of the critical line, then applying the functional equation.

## Source and attribution

- Original Lean project: [lsernau/grh-lean](https://github.com/lsernau/grh-lean).
- Source revision: [`72fead102f663d5c7a407964a13dc0cf9d977207`](https://github.com/lsernau/grh-lean/tree/72fead102f663d5c7a407964a13dc0cf9d977207).
- Manuscript preparation: ChatGPT, 26 November 2026.

The underlying mathematical argument is attributed to the original project. These manuscripts are an AI-generated natural-language reconstruction for study and review, not an independent discovery or a certification of the proof. Lean was not run in preparing them, and they have not been independently peer-reviewed.

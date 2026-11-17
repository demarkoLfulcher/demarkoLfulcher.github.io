---
title: "LeanSMILES: Formally Verified Molecular Machine Learning in Lean 4"
order: 1
period: "Oct 2026"
tools: "Lean 4, Mathlib"
excerpt: "A molecular ML pipeline written in Lean 4, from SMILES parsing to ridge regression, with machine-checked proofs that its solvers converge and certificates that guarantee error bounds before training."
demo: "https://leansmiles.netlify.app/"
code:   # add the repository URL here
---

LeanSMILES is a molecular machine learning pipeline written and verified in Lean 4. It is demonstrated on **aqueous solubility prediction**.

## What I built

- **Verified iterative solvers.** I implemented ridge regression solvers (gradient descent, Jacobi, and Gauss–Seidel) and proved in Mathlib that each converges to the loss minimizer, using contraction bounds under weighted diagonal dominance.
- **Certified error bounds.** Exact rational-arithmetic certificate checks guarantee, *before training*, that a model will reach a given error tolerance. Each check is proved sound.
- **End-to-end pipelines.** I designed the Pipelines module, which links SMILES parsing, molecular fingerprint representations and certified regression into verified end-to-end ML pipelines.

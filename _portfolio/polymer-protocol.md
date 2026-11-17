---
title: "Formal Methods Security Analysis of the Polymer Protocol"
order: 3
period: "Aug 2024 – May 2025"
tools: "CPSA, Dolev–Yao model"
excerpt: "A formal analysis in CPSA of Polymer, a post-quantum symmetric key agreement protocol. It found a malicious trust agent attack caused by improper low-depth HARPS key generation."
paper:  # add a link to the paper here
---

Polymer is a post-quantum symmetric key agreement framework that combines **HARPS** and **Leighton–Micali** schemes. We analyzed it formally with the Cryptographic Protocol Shapes Analyzer (CPSA) under the Dolev–Yao threat model.

## Approach

- Modeled the multi-party protocol strands in CPSA.
- Wrote custom encryption macros to simulate XOR, which CPSA does not support natively.

## Result

We found a **malicious trust agent attack** caused by improper low-depth HARPS key generation. We wrote a paper documenting the findings and the methods and tools we used.

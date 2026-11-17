---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
{% include toc title="On this page" icon="list" %}

## Education

**M.S., Computer Science** · Feb 2026 – May 2027 (expected)  
University of Maryland, Baltimore County (UMBC), Baltimore, MD

**B.A., Mathematics** · Aug 2020 – May 2025  
University of Maryland, Baltimore County (UMBC), Baltimore, MD

## Experience

### Graduate Research Assistant, ATOMS Lab, UMBC
*July 2026 – Present* · AI-Theory Oriented Molecular Science Lab · funded by an Amazon Scientist grant

- Define statistical thermodynamic ensembles in a formal environment and formalize the mathematics needed to derive their properties.
- Implement Markov chain Monte Carlo code, in general and for simulations of molecular systems in particular, and verify it using definitions and theorems.
- Develop training materials that teach scientists and engineers to use these methods and to reason rigorously about chemistry and chemical engineering.

### Graduate Teaching Assistant, Protocol Analysis Lab (PAL), UMBC
*Sep 2025 – Aug 2026*

- Ran interactive Cryptographic Protocol Shapes Analyzer (CPSA) workshops that taught students the core methods of formal verification and security protocol analysis.
- Guided students in building formal models of complex cryptographic protocols and in using CPSA to analyze their structural security properties and find vulnerabilities.
- Taught students to apply the Dolev–Yao threat model to judge how well a protocol holds up against active network adversaries.

### IT Intern, Bello Machre
*Jan 2026 – May 2026*

- Tracked and documented end-of-life IT inventory slated for recycling, keeping records fully compliant and 100% accurate across retired hardware.
- Ran IT onboarding for new hires end to end: provisioned user accounts, set access permissions, and gave initial technical support.
- Configured, cataloged and deployed workstations, mobile devices and peripherals for incoming staff, making sure all hardware met the organization's security and performance standards.

### Student Intern, AI4ALL
*Jul 2024 – Dec 2024*

- Guided students through foundational AI/ML coursework, explaining algorithms, the underlying math and core machine learning concepts.
- Supported students through end-to-end ML projects, with hands-on help on model architecture, data preprocessing, hyperparameter tuning and debugging.
- Helped students turn theory into working supervised and unsupervised models, neural networks and data pipelines.

## Projects

See the [Projects page](/projects/) for more detail on each.

### LeanSMILES: Formally Verified Molecular Machine Learning in Lean 4
*Oct 2026* · [Demo](https://leansmiles.netlify.app/)

- Implemented iterative ridge regression solvers (gradient descent, Jacobi, Gauss–Seidel) in Lean 4 and proved in Mathlib that they converge to the loss minimizer, using contraction bounds under weighted diagonal dominance.
- Built exact rational-arithmetic certificate checks that guarantee, before training, that a model will reach a given error tolerance, and proved each check sound.
- Designed the Pipelines module, which links SMILES parsing, molecular fingerprints and certified regression into verified end-to-end ML pipelines, demonstrated on aqueous solubility prediction.

### Source Code Review of SEAL-C
*Feb 2026 – June 2026*

- Reviewed the source of the SEAL-C digital media authentication framework for memory safety, reliability, and the correctness of its cryptographic signing and validation.
- Found critical security flaws, including RSA padding bypasses, revoked-key bypasses, global private key exposure and memory leaks.
- Wrote targeted patches and proposed a memory-safe Rust re-implementation of SEAL to eliminate memory corruption vulnerabilities.

### Formal Methods Security Analysis of the Polymer Protocol
*Aug 2024 – May 2025*

- Formally analyzed Polymer, a post-quantum symmetric key agreement framework that combines HARPS and Leighton–Micali schemes, using CPSA under the Dolev–Yao threat model.
- Modeled multi-party protocol strands, wrote custom encryption macros to simulate XOR (which CPSA does not support natively), and found a malicious trust agent attack caused by improper low-depth HARPS key generation.
- Co-wrote a paper documenting the findings and the methods and tools used in the analysis.

## Competitions

| Competition | Result | Date |
|---|---|---|
| DawgCTF 2025 (national CTF hosted by UMBC) | **1st Place** | Apr 2025 |
| Spring NCL CTF | **13th Place** (98th percentile) | Apr 2025 |
| UMBC Cyber Defense Exercise (CDE) 2024 | **2nd Place** | Oct 2024 |

- **DawgCTF:** solved challenges in web exploitation, reverse engineering, cryptography and forensics, and worked with teammates to analyze vulnerabilities and write custom exploits.
- **NCL:** solved challenges in OSINT, web exploitation, cryptography, network traffic analysis and password cracking.
- **CDE:** secured Windows systems in a simulated enterprise network (Registry, Active Directory, IIS hardening) and set up access controls and network defenses against live simulated attacks.

## Technical Skills

| Area | Tools |
|---|---|
| Programming languages | Python, C, Rust, Haskell |
| Assembly | x86 |
| Theorem provers / SMT | Lean, Rocq, Z3 |
| Program analysis | Ghidra, GDB, angr |
| Virtualization | VMware, VirtualBox, QEMU |
| Development tools | Git, Docker, Nix |
| Linux | NixOS, Arch, Ubuntu |

## Certifications

- **CompTIA Security+ CE**: issued Sep 2025, expires Sep 2028

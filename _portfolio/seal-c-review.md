---
title: "Source Code Review of SEAL-C"
order: 2
period: "Feb 2026 – June 2026"
tools: "C, Rust, manual code review"
excerpt: "A security review of the SEAL-C media authentication framework. It found RSA padding bypasses, revoked-key bypasses, global private key exposure and memory leaks, and led to a proposed memory-safe Rust re-implementation."
code:   # add the repository URL here (e.g. the Rust re-implementation)
---

SEAL is a framework for authenticating digital media. I reviewed the source of its C implementation, SEAL-C, for memory safety, reliability, and the correctness of its cryptographic signing and validation.

## Findings

- RSA padding bypasses
- Revoked-key bypasses
- Global private key exposure
- Memory leaks

## Outcome

I wrote targeted patches for the issues and proposed a memory-safe **Rust re-implementation** of SEAL to eliminate memory corruption vulnerabilities and make media authentication more trustworthy.

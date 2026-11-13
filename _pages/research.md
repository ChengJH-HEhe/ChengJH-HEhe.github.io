---
title: "Research"
permalink: /research/
author_profile: true
---

My research focuses on **systems security and performance optimization**, with complementary interests in AI-assisted systems research and trustworthy AI systems.

- **Systems security and performance:** Microarchitectural security, speculative execution defenses, trusted execution environments (TEEs), and security–performance trade-offs.
- **AI for systems:** AI-assisted vulnerability discovery, attack and defense development, and system performance optimization.
- **Systems for AI:** Security, safety, and performance of AI models, agents, and infrastructure, including AI/agent safety and systems-level security issues.

My goal is to advance **AI for secure and efficient systems**, and **secure and efficient systems for AI**.

## TEE acceleration

**Network Security and Privacy Protection (NSEC) Lab, SJTU** · June 2025–June 2026  
**Advisor:** Prof. Guoxing Chen

My research focused on secure and efficient trusted execution, including whole-program integrity and enclave startup efficiency. I am the second author of **Attest the Whole, Verify Incrementally** — **CCS 2026: Accepted**.

The paper's lazy-verification architecture is implemented on **Intel SGX and AMD SEV-SNP**. My personal design contribution focuses on dynamic enclave-page loading to reduce SGX cold-start work. [Publication details](/publications/attest-the-whole/) · [Project details](/projects/#sgx-cold-start-optimization)

<a id="intel-defense-profiling"></a>

## Defense profiling and overhead evaluation

**DCASL, University of California San Diego** · May 2026–present  
**Advisor:** Prof. Dean Tullsen  
**Collaborators:** Luyi Li and Hosein Yavarzadeh

I study security–performance trade-offs in Intel/AMD branch-predictor defenses, assessing isolation across privilege boundaries and the runtime cost of enforcing it.

- Develop fine-grained microbenchmarks to characterize Intel/AMD defense mechanisms and investigate isolation boundaries across kernel/user transitions and VM/cross-VM contexts.
- Develop controlled overhead benchmarks to quantify mitigation costs across workloads and analyze the security–performance trade-offs of different defense configurations.

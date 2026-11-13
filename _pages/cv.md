---
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
---

[Download CV (PDF)](/files/CV.pdf){: .btn .btn--primary}

*Updated November 12, 2026.*

## Research Interests

My research focuses on **systems security and performance optimization**, with complementary interests in AI-assisted systems research and trustworthy AI systems.

- **Systems security and performance:** Microarchitectural security, speculative execution defenses, trusted execution environments (TEEs), and security–performance trade-offs.
- **AI for systems:** AI-assisted vulnerability discovery, attack and defense development, and system performance optimization.
- **Systems for AI:** Security, safety, and performance of AI models, agents, and infrastructure, including AI/agent safety and systems-level security issues.

My goal is to advance **AI for secure and efficient systems**, and **secure and efficient systems for AI**.

## Education

### Shanghai Jiao Tong University

**Sep. 2023 – Jun. 2027 (expected)**

B.S. in Computer Science, **ACM Honors Class**  
**Cumulative GPA:** 90.0/100  
**Selected coursework:** Mathematical Logic; Principles and Practice of Computer Algorithms; Compiler Design; Computer Architecture; Operating Systems; Machine Learning Systems; Model Checking.

## Research Experience

### Network Security and Privacy Protection (NSEC) Lab, SJTU

**Jun. 2025 – Jun. 2026**

*Advisor: Prof. Guoxing Chen*

- Study secure and efficient trusted execution, focusing on whole-program integrity and enclave startup efficiency; co-authored an accepted CCS 2026 paper as second author.

### DCASL, University of California San Diego

**May 2026 – present**

*Advisor: Prof. Dean Tullsen*  
*Collaborators: Luyi Li and Hosein Yavarzadeh*

- **BHI Defense Profiling (ongoing):** Study security–performance trade-offs in Intel/AMD branch-predictor defenses, assessing isolation across privilege boundaries and the runtime cost of enforcing it.

## Publications

**Attest the Whole, Verify Incrementally: Whole-Program Integrity via Lazy Verification in Trusted Execution Environments**  
Zhen Huang, **Junhong Cheng**, Yijia Ma, Guoxing Chen, Zhezhi He, Yan Meng, Mengmeng Zhou, and Haojin Zhu.  
*ACM Conference on Computer and Communications Security*
([CCS 2026](https://www.sigsac.org/ccs/CCS2026/program/schedule.html)). **Accepted.**

<p style="text-indent: 2em;">Whole-program integrity via compact metadata attestation and first-access block verification on <strong>Intel SGX and AMD SEV-SNP</strong>; evaluated on FaaS, database workloads, and LLM inference.</p>

## Personal Projects

### SGX Cold-Start Optimization

**CCS 2026**

- Designed a dynamic page-loading mechanism for Intel SGX, deferring additional enclave-page loading until after startup to reduce the work required during enclave initialization.
- Integrated deferred page loading with the paper's lazy-verification framework for whole-program integrity, connecting startup efficiency with authenticated access to program contents.

### Defense Profiling and Overhead Evaluation

**May 2026 – present**

*UCSD research internship*

- Develop fine-grained microbenchmarks to characterize Intel/AMD defense mechanisms and investigate isolation boundaries across kernel/user transitions and VM/cross-VM contexts.
- Develop controlled overhead benchmarks to quantify mitigation costs across workloads and analyze the security–performance trade-offs of different defense configurations.

### [Mx Compiler](https://github.com/ChengJH-HEhe/Compiler-Design-Implementation)

**Java**

- Built a compiler for a C-like educational language, with an SSA-based intermediate representation and RISC-V assembly generation.
- Implemented Mem2Reg, aggressive dead-code elimination, and liveness-based register allocation with spilling.

### [Out-of-Order RISC-V CPU](https://github.com/ChengJH-HEhe/CPU-2024)

**Verilog**

- Implemented a RISC-V processor using Tomasulo-style dynamic scheduling for out-of-order instruction execution.
- Built reservation stations, a reorder buffer, and load/store buffering; coordinated operand dependencies and in-order retirement.

### [Raft Replicated Log](https://pdos.csail.mit.edu/6.824/labs/lab-raft1.html)

**Go**

- Implemented leader election and replicated-log consensus for distributed state replication.
- Handled network delays, partitions, message loss, and reordering in the consensus protocol.

## Awards and Honors

**Zhiyuan Honors Scholarship**, 2023 and 2024  ·  **Top 2% at SJTU**

## Teaching Assistant Experience

### Great Ideas in Computer Science

**Fall 2024**

### Principles and Practice of Computer Algorithms

**Summer 2025**

## Skills

**Programming:** C++, Go, Java, Verilog  
**Systems Expertise:** Intel SGX, CPU Microarchitecture  
**Languages:** Chinese (native), English (fluent)  
**TOEFL:** 110/120 (5.5/6.0); Speaking: 5.0/6.0.

## Contact

[cheng_junhong_2023@sjtu.edu.cn](mailto:cheng_junhong_2023@sjtu.edu.cn) · [GitHub](https://github.com/ChengJH-HEhe)

---
title: "Selected Projects"
permalink: /projects/
author_profile: true
---

## SGX Cold-Start Optimization

**CCS 2026**

- Designed a dynamic page-loading mechanism for Intel SGX, deferring additional enclave-page loading until after startup to reduce the work required during enclave initialization.
- Integrated deferred page loading with the paper's lazy-verification framework for whole-program integrity, connecting startup efficiency with authenticated access to program contents.

## Defense Profiling and Overhead Evaluation

**May 2026 – present**

*UCSD research internship*

- Develop fine-grained microbenchmarks to characterize Intel/AMD defense mechanisms and investigate isolation boundaries across kernel/user transitions and VM/cross-VM contexts.
- Develop controlled overhead benchmarks to quantify mitigation costs across workloads and analyze the security–performance trade-offs of different defense configurations.

## [Mx Compiler](https://github.com/ChengJH-HEhe/Compiler-Design-Implementation)

**Java**

- Built a compiler for a C-like educational language, with an SSA-based intermediate representation and RISC-V assembly generation.
- Implemented Mem2Reg, aggressive dead-code elimination, and liveness-based register allocation with spilling.

## [Out-of-Order RISC-V CPU](https://github.com/ChengJH-HEhe/CPU-2024)

**Verilog**

- Implemented a RISC-V processor using Tomasulo-style dynamic scheduling for out-of-order instruction execution.
- Built reservation stations, a reorder buffer, and load/store buffering; coordinated operand dependencies and in-order retirement.

## [Raft Replicated Log](https://pdos.csail.mit.edu/6.824/labs/lab-raft1.html)

**Go**

- Implemented leader election and replicated-log consensus for distributed state replication.
- Handled network delays, partitions, message loss, and reordering in the consensus protocol.

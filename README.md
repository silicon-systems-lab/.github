# Silicon Systems Lab

*Silicon-aware systems engineering experiments  
for modern heterogeneous compute platforms.*

Engineering laboratory exploring **hardware–software interaction**, **runtime behavior**, and **infrastructure for modern silicon platforms**.

The lab focuses on understanding how software interacts with:

- CPU microarchitecture
- memory hierarchy
- kernel subsystems
- accelerator infrastructure

The goal is to develop **silicon-aware infrastructure engineering practices** applicable to modern compute environments.

---

## Research Focus

Primary areas of investigation:

- memory hierarchy behavior and cache locality
- concurrency effects and cache-line interactions
- kernel / syscall boundaries
- deterministic performance measurement
- accelerator host infrastructure
- cross-silicon performance comparison

Experiments emphasize **measurement, reproducibility, and architectural reasoning** rather than application-level benchmarking.

---

## Hardware Platforms

Current platforms used in the lab:

- Apple Silicon (M-series)
- ARM SBC platforms
- x86 host systems

These systems allow controlled experiments across different processor architectures and memory systems.

---

## Core Repositories

```

silicon-systems-lab
│
├─ edge-hw-showcase        (public)
├─ silicon-infra-notes     (private)
├─ ...

```

### edge-hw-showcase

Deterministic systems experimentation framework exploring:

- memory access patterns
- concurrency behavior
- kernel interaction
- accelerator infrastructure

The repository provides reproducible experiments across multiple hardware platforms.

### silicon-infra-notes

Private research notes containing deeper analysis, experiment design, and infrastructure architecture documentation.

---

## Methodology

Experiments follow a structured engineering process:

1. Hypothesis formulation  
2. Deterministic workload execution  
3. Hardware counter measurement  
4. Cross-platform comparison  
5. Root-cause analysis  

Instrumentation frequently includes tools such as:

- Linux performance counters
- low-level profiling
- latency and throughput measurement

---

## Notes / Writeups

- (WIP) Cross-silicon cache locality: M2 vs RK3588 vs x86
- (WIP) Deterministic benchmarking checklist (governor, thermal, kernel pin)
- (WIP) PCIe/NVMe stability knobs on constrained ARM SBC platforms

---

## Contact / Collaboration

- Maintainer: Daniel Chechik
- Topics: systems performance, silicon-aware infrastructure, accelerators
- Collaboration: issues and PRs welcome on public repos; deeper notes remain private.

---

## License

Unless otherwise specified, public repositories follow standard open-source licensing.  
Internal research materials may remain private.

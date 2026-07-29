<div align="center">

# PJ Dailey
**Systems Software & AI Infrastructure Engineer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pjdailey/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pjdailey13@gmail.com)

</div>

---

### About Me

Computer Science & Mathematics student at St. Edward's University (4.0/4.0 GPA) and NCAA Division II student-athlete. Specializing in low-level systems, hardware acceleration, and deterministic execution pipelines. 

* **Focus Areas:** Explicit memory management, custom SIMD vectorization (AVX2/AVX-512), lock-free concurrent data structures, and edge GPU inference.
* **Core Philosophy:** Minimize cache misses, bypass high-overhead runtime abstractions, and profile at the hardware clock-cycle level (`rdtsc`, `perf`).

---

## Current Projects

### SIMD-Accelerated Distributed Vector Database | C23, AVX-512, POSIX, gRPC, HNSW

> **Throughput:** Engineered a vector search core in C, bypassing standard math libraries with custom AVX2 / AVX-512 intrinsics to hit 120 GFLOPS computational throughput and sub-500ms distance calculations.

> **Storage & Indexing:** Implemented POSIX memory-mapped files (mmap) for zero-copy disk persistence with reader-writer locks. Replaced linear scans with a Hierarchical Navigable Small World (HNSW) graph index to guarantee O(log N) search latency at 15,000 QPS.

### Hybrid Limit Order Book Engine | C++23, TypeScript, WebSockets, Docker 

> **Execution:** Designed an institutional financial exchange engine achieving strict O(1) order execution with 3micro-second latency, measured via rdtsc hardware timestamp counters and Google Benchmark.

> **Memory & Concurrency:** Paired custom hash maps with contiguous memory-pooled doubly linked lists to preserve CPU cache locality. Routed live trades through a Single-Producer/Single-Consumer (SPSC) lock-free queue to stream execution updates to 1,000+ concurrent clients with <5ms network jitter.

### Hardware-Accelerated CUDA Inference Engineine | C++23, CUDA, NVIDIA TensorRT, Computer Vision 

> **Edge Performance:**Built a bare-metal computer vision pipeline in C++ to replace high-overhead Python runtimes.

> **GPU Graph Management:** Authored custom CUDA kernels for parallel image pre-processing and Non-Maximum Suppression (NMS), maintaining the entire execution graph on an RTX 3060 Ti to sustain a strict 2.5ms frame latency.

### Sandboxed AI Execution Runtime | Python, Docker, IPC, AST Parsing

> **Isolation & Speed:** : Orchestrated an isolated execution framework evaluating LLM code payloads in pre-warmed container pools (<150ms spin-up latency).

> **Security Pipeline:** Built a low-latency AST parser (<500$\mu s$ evaluation) to sanitize untrusted scripts, streaming stdout/stderr over low-overhead IPC pipelines.

---

## Tech Stack

* **Languages**     : C23, C++23, Java, CUDA, x86 NASM Assembly, Python, TypeScript, SQL
* **Systems/HPC**   : SIMD (AVX-512/AVX2), POSIX mmap, Memory Pools, SPSC Lock-Free Queues, gRPC
* **GPU & AI**      : TensorRT, CUDA Kernels, PyTorch, Computer Vision Pipelines
* **Profiling/Dev** : Perf, Valgrind, Gprof, CMake, Linux, Docker, WebSockets

---

## ⚾ Baseball/Athletics | NCAA Division II Student-Athlete

> Balanced a 4.0 GPA in CS & Math with 5:00 AM weight training, daily 4+ hour practice rotations, and Lone Star Conference game schedules.

```
  ─────────────────────────────────────────
  School    St. Edward's University — NCAA D2
  Team      Hilltoppers
  Profile   gohilltoppers.com/sports/baseball/roster
```

---

<div align="center">

![Visitor Count](https://komarev.com/ghpvc/?username=PjDailey11&style=flat-square&color=58a6ff&label=profile+views)

</div>

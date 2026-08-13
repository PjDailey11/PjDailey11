<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img src="assets/banner-light.svg" width="880" alt="PJ Dailey — Systems Software &amp; AI Infrastructure Engineer. Specializing in SIMD and hardware acceleration, deterministic low-latency execution, CUDA/GPU inference pipelines, and sandboxed AI execution runtimes.">
</picture>

# PJ Dailey
**Systems Software & AI Infrastructure Engineer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pjdailey/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pjdailey13@gmail.com)

</div>

`§ ABOUT`

---

Computer Science & Mathematics student at St. Edward's University (4.0/4.0 GPA) and NCAA Division II student-athlete. Specializing in low-level systems, hardware acceleration, and deterministic execution pipelines.

`§ PROJECTS`

---

### SIMD-Accelerated Distributed Vector Database

![C23](https://img.shields.io/badge/C23-30363D?style=flat-square)
![AVX-512](https://img.shields.io/badge/AVX--512-30363D?style=flat-square)
![POSIX](https://img.shields.io/badge/POSIX-30363D?style=flat-square)
![gRPC](https://img.shields.io/badge/gRPC-30363D?style=flat-square)
![HNSW](https://img.shields.io/badge/HNSW-30363D?style=flat-square)

> **Throughput:** Engineered a vector search core in C, bypassing standard math libraries with custom AVX2 / AVX-512 intrinsics to hit 120 GFLOPS computational throughput and sub-500ms distance calculations.

> **Storage & Indexing:** Implemented POSIX memory-mapped files (mmap) for zero-copy disk persistence with reader-writer locks. Replaced linear scans with a Hierarchical Navigable Small World (HNSW) graph index to guarantee O(log N) search latency at 15,000 QPS.

### Hybrid Limit Order Book Engine

![C++23](https://img.shields.io/badge/C%2B%2B23-30363D?style=flat-square&logo=cplusplus&logoColor=C9D1D9)
![TypeScript](https://img.shields.io/badge/TypeScript-30363D?style=flat-square&logo=typescript&logoColor=C9D1D9)
![WebSockets](https://img.shields.io/badge/WebSockets-30363D?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-30363D?style=flat-square&logo=docker&logoColor=C9D1D9)

> **Execution:** Designed an institutional financial exchange engine achieving strict O(1) order execution with 3 microsecond latency, measured via rdtsc hardware timestamp counters and Google Benchmark.

> **Memory & Concurrency:** Paired custom hash maps with contiguous memory-pooled doubly linked lists to preserve CPU cache locality. Routed live trades through a Single-Producer/Single-Consumer (SPSC) lock-free queue to stream execution updates to 1,000+ concurrent clients with <5ms network jitter.

### Hardware-Accelerated CUDA Inference Engine

![C++23](https://img.shields.io/badge/C%2B%2B23-30363D?style=flat-square&logo=cplusplus&logoColor=C9D1D9)
![CUDA](https://img.shields.io/badge/CUDA-30363D?style=flat-square&logo=nvidia&logoColor=C9D1D9)
![TensorRT](https://img.shields.io/badge/TensorRT-30363D?style=flat-square)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-30363D?style=flat-square)

> **Edge Performance:** Built a bare-metal computer vision pipeline in C++ to replace high-overhead Python runtimes.

> **GPU Graph Management:** Authored custom CUDA kernels for parallel image pre-processing and Non-Maximum Suppression (NMS), maintaining the entire execution graph on an RTX 3060 Ti to sustain a strict 2.5ms frame latency.

### Sandboxed AI Execution Runtime

![Python](https://img.shields.io/badge/Python-30363D?style=flat-square&logo=python&logoColor=C9D1D9)
![Docker](https://img.shields.io/badge/Docker-30363D?style=flat-square&logo=docker&logoColor=C9D1D9)
![IPC](https://img.shields.io/badge/IPC-30363D?style=flat-square)
![AST Parsing](https://img.shields.io/badge/AST%20Parsing-30363D?style=flat-square)

> **Isolation & Speed:** Orchestrated an isolated execution framework evaluating LLM code payloads in pre-warmed container pools (<150ms spin-up latency).

> **Security Pipeline:** Built a low-latency AST parser (<500 microsecond evaluation) to sanitize untrusted scripts, streaming stdout/stderr over low-overhead IPC pipelines.

`§ STACK`

---

| Category | Stack |
|---|---|
| Languages | C23, C++23, Java, CUDA, x86 NASM Assembly, Python, TypeScript, SQL |
| Systems / HPC | SIMD (AVX-512 / AVX2), POSIX mmap, Memory Pools, SPSC Lock-Free Queues, gRPC |
| GPU & AI | TensorRT, CUDA Kernels, PyTorch, Computer Vision Pipelines |
| Profiling / Dev | Perf, Valgrind, Gprof, CMake, Linux, Docker, WebSockets |

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=PjDailey11&style=flat-square&color=E8A33D&label=PROFILE+VIEWS)

<sub>`// EOF`</sub>

</div>

<div align="center">

# PJ Dailey
**Systems Software & AI Infrastructure Engineer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pjdailey/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pjdailey13@gmail.com)

</div>

`ABOUT`

---

Computer Science & Mathematics student at St. Edward's University (4.0/4.0 GPA) and NCAA Division II student-athlete. Specializing in low-level systems, hardware acceleration, and deterministic execution pipelines.

`PROJECTS`

---

### SIMD-Accelerated Distributed Vector Database

![C23](https://img.shields.io/badge/C23-5A4FCF?style=flat-square)
![AVX-512](https://img.shields.io/badge/AVX--512-0071C5?style=flat-square)
![POSIX](https://img.shields.io/badge/POSIX-B85C38?style=flat-square)
![gRPC](https://img.shields.io/badge/gRPC-244B5A?style=flat-square)
![HNSW](https://img.shields.io/badge/HNSW-8E44AD?style=flat-square)

> **Throughput:** Engineered a vector search core in C, bypassing standard math libraries with custom AVX2 / AVX-512 intrinsics to hit 120 GFLOPS computational throughput and sub-500ms distance calculations.

> **Storage & Indexing:** Implemented POSIX memory-mapped files (mmap) for zero-copy disk persistence with reader-writer locks. Replaced linear scans with a Hierarchical Navigable Small World (HNSW) graph index to guarantee O(log N) search latency at 15,000 QPS.

### Hybrid Limit Order Book Engine

![C++23](https://img.shields.io/badge/C%2B%2B23-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-16A085?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

> **Execution:** Designed an institutional financial exchange engine achieving strict O(1) order execution with 3 microsecond latency, measured via rdtsc hardware timestamp counters and Google Benchmark.

> **Memory & Concurrency:** Paired custom hash maps with contiguous memory-pooled doubly linked lists to preserve CPU cache locality. Routed live trades through a Single-Producer/Single-Consumer (SPSC) lock-free queue to stream execution updates to 1,000+ concurrent clients with <5ms network jitter.

### Hardware-Accelerated CUDA Inference Engine

![C++23](https://img.shields.io/badge/C%2B%2B23-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-4B7A00?style=flat-square)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-7C4DFF?style=flat-square)

> **Edge Performance:** Built a bare-metal computer vision pipeline in C++ to replace high-overhead Python runtimes.

> **GPU Graph Management:** Authored custom CUDA kernels for parallel image pre-processing and Non-Maximum Suppression (NMS), maintaining the entire execution graph on an RTX 3060 Ti to sustain a strict 2.5ms frame latency.

### Sandboxed AI Execution Runtime

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Firecracker](https://img.shields.io/badge/Firecracker-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![eBPF](https://img.shields.io/badge/eBPF-1D1E20?style=flat-square)
![KVM](https://img.shields.io/badge/KVM-E34F26?style=flat-square)

> **Hypervisor:** Engineered a bare-metal execution hypervisor using AWS Firecracker and KVM, dropping untrusted code evaluation cold-starts to sub-**125ms** via memory state snapshotting and restoration.
> **Kernel-Level Hardening:** Implements custom **Seccomp-BPF** kernel filters to enforce strict system call allow-lists, proactively neutralizing remote code execution (RCE) and container escape vectors.

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

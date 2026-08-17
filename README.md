<div align="center">

# PJ Dailey
**Systems Software & Quantitative Infrastructure Engineer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pjdailey/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pjdailey13@gmail.com)

</div>

# About Me

Computer Science & Mathematics student at St. Edward's University (4.0/4.0 GPA) and NCAA Division II student-athlete specializing in bare-metal systems, kernel-bypass networking, and ultra-low-latency deterministic execution pipelines.

---

# Projects

### SIMD-Accelerated Distributed Vector Search Engine

![C23](https://img.shields.io/badge/C23-5A4FCF?style=flat-square)
![SIMD Intrinsics](https://img.shields.io/badge/SIMD%20Intrinsics-0071C5?style=flat-square)
![gRPC](https://img.shields.io/badge/gRPC-244B5A?style=flat-square)
![POSIX](https://img.shields.io/badge/POSIX-B85C38?style=flat-square)
![HNSW](https://img.shields.io/badge/HNSW-8E44AD?style=flat-square)

> **Throughput:** Engineered a vector database core in C, bypassing standard math libraries with custom AVX2/AVX-512 SIMD intrinsics to achieve a computational throughput of 120 GFLOPS and sub-500-microsecond distance calculations[cite: 3].

> **Storage & Persistence:** Integrated POSIX memory-mapped files (mmap) for zero-copy disk persistence, utilizing reader-writer locks to safely synchronize concurrent reads and avoid full-dataset RAM loads during search queries[cite: 3].

> **Indexing Strategy:** Replaced linear scans with a Hierarchical Navigable Small World (HNSW) graph index to guarantee O(log N) search latency, utilizing a gRPC network layer to sustain 15,000 queries per second (QPS) during concurrent batch insertions[cite: 3].

### Ultra-Low-Latency C++23 Matching Engine

![C++23](https://img.shields.io/badge/C%2B%2B23-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Linux Kernel](https://img.shields.io/badge/Linux%20Kernel-FCC624?style=flat-square&logo=linux&logoColor=black)
![io_uring](https://img.shields.io/badge/io__uring-16A085?style=flat-square)
![Cache Optimization](https://img.shields.io/badge/Cache%20Optimization-2496ED?style=flat-square)

> **Execution:** Engineered a zero-allocation C++23 matching engine achieving <280ns P99 order execution latency, benchmarked via rdtsc hardware counters and Google Benchmark[cite: 3].

> **Memory Architecture:** Eliminated hot-path heap allocations and L1/L2 cache misses by architecting a price-indexed flat array book backed by pre-allocated intrusive ring-buffer memory pools[cite: 3].

> **Network Stack:** Bypassed Linux kernel network stack latency by implementing an io_uring ring-buffer ingestion pipeline parsing zero-copy Simple Binary Encoding (SBE) frames[cite: 3].

### High-Frequency CUDA Inference Engine

![C++23](https://img.shields.io/badge/C%2B%2B23-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-4B7A00?style=flat-square)
![GPUDirect RDMA](https://img.shields.io/badge/GPUDirect%20RDMA-7C4DFF?style=flat-square)

> **Execution Pipeline:** Engineered a bare-metal C++/CUDA inference pipeline processing time-series market data with sub-15-microsecond tail latency on an RTX 3060 Ti[cite: 3].

> **Kernel Bypass:** Bypassed CPU routing by utilizing GPUDirect RDMA to map network packets directly from the NIC into GPU memory[cite: 3].

> **Quantization:** Accelerated model execution by quantizing PyTorch architectures to INT8 via custom TensorRT entropy calibration, maximizing Tensor Core throughput[cite: 3].

### Deterministic Quant Backtesting Hypervisor

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Firecracker](https://img.shields.io/badge/Firecracker-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![eBPF](https://img.shields.io/badge/eBPF-1D1E20?style=flat-square)
![Seccomp](https://img.shields.io/badge/Seccomp-E34F26?style=flat-square)

> **Hypervisor Isolation:** Engineered a bare-metal execution hypervisor using AWS Firecracker and KVM to isolate and evaluate untrusted quantitative trading models[cite: 3].

> **Snapshot Restoration:** Reduced microVM snapshot restoration latency to sub-5ms by overriding host OS page faults with a custom Rust userspace handler via userfaultfd[cite: 3].

> **Zero-Copy Injection:** Achieved true zero-copy market data injection by mapping host-backed physical memory directly into the guest address space via virtio-pmem, completely bypassing socket buffers[cite: 3].

---

# Stack

### Languages
![C23](https://img.shields.io/badge/C23-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++23](https://img.shields.io/badge/C++23-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)
![x86_64 NASM Assembly](https://img.shields.io/badge/x86__64_NASM_Assembly-%231E1E1E.svg?style=for-the-badge)
![Python 3.14](https://img.shields.io/badge/Python_3.14-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

### Systems & Kernel
![Linux (Arch)](https://img.shields.io/badge/Linux_(Arch)-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![io_uring](https://img.shields.io/badge/io__uring-%232C2C2C.svg?style=for-the-badge)
![eBPF](https://img.shields.io/badge/eBPF-%232C2C2C.svg?style=for-the-badge)
![Seccomp](https://img.shields.io/badge/Seccomp-%232C2C2C.svg?style=for-the-badge)
![KVM](https://img.shields.io/badge/KVM-%232C2C2C.svg?style=for-the-badge)
![POSIX Threads (pthreads)](https://img.shields.io/badge/POSIX_Threads_(pthreads)-%232C2C2C.svg?style=for-the-badge)

### Hardware & Compute
![CUDA](https://img.shields.io/badge/CUDA-%2376B900.svg?style=for-the-badge&logo=nVIDIA&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-%2376B900.svg?style=for-the-badge&logo=nVIDIA&logoColor=white)
![AVX2 / AVX-512 SIMD Intrinsics](https://img.shields.io/badge/AVX2_/_AVX--512_SIMD_Intrinsics-%232C2C2C.svg?style=for-the-badge)

### Profiling & Tooling
![perf](https://img.shields.io/badge/perf-%231E1E1E.svg?style=for-the-badge)
![Valgrind](https://img.shields.io/badge/Valgrind-%231E1E1E.svg?style=for-the-badge)
![GDB](https://img.shields.io/badge/GDB-%231E1E1E.svg?style=for-the-badge)
![CMake](https://img.shields.io/badge/CMake-%23008FBA.svg?style=for-the-badge&logo=cmake&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logo=grpc&logoColor=white)

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=PjDailey11&style=flat-square&color=E8A33D&label=PROFILE+VIEWS)

</div>

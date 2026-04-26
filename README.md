# CUDA Programming

From your first kernel to tiled matmul, streams, atomics and Nsight profiling &mdash; ten visual presentations on writing CUDA from scratch.

**Live index:** https://brendanjameslynskey.github.io/LLM_Hub_CUDA/

## Presentations in this series

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 01 | [GPU Architecture &amp; the CUDA Execution Model](https://brendanjameslynskey.github.io/CUDA_01_GPU_Architecture/) | live | SMs, warps, SIMT execution, thread hierarchy, and how GPU hardware maps to CUDA's programming model. |
| 02 | [Your First CUDA Kernel](https://brendanjameslynskey.github.io/CUDA_02_First_Kernel/) | live | From nvcc setup to vector addition &mdash; host/device workflow, memory allocation, kernel launch syntax, error handling. |
| 03 | [Thread Hierarchy &amp; Indexing](https://brendanjameslynskey.github.io/CUDA_03_Thread_Hierarchy/) | live | Grids, blocks, threads, warps &mdash; mapping problem dimensions to launch configurations with worked index calculations. |
| 04 | [Memory Hierarchy](https://brendanjameslynskey.github.io/CUDA_04_Memory_Hierarchy/) | live | Global, shared, constant, texture, and register memory &mdash; access patterns, bank conflicts, coalescing rules. |
| 05 | [Matrix Multiplication — Naive to Tiled](https://brendanjameslynskey.github.io/CUDA_05_Matrix_Multiply/) | live | Step-by-step optimisation from a naive O(n³) kernel to shared-memory tiled multiplication with benchmarks. |
| 06 | [Synchronisation &amp; Atomics](https://brendanjameslynskey.github.io/CUDA_06_Synchronisation/) | live | __syncthreads(), warp-level primitives, atomic operations, race conditions, parallel reduction patterns. |
| 07 | [Profiling with Nsight](https://brendanjameslynskey.github.io/CUDA_07_Profiling/) | live | Nsight Systems and Nsight Compute &mdash; finding bottlenecks, occupancy analysis, memory throughput. |
| 08 | [Streams &amp; Async Execution](https://brendanjameslynskey.github.io/CUDA_08_Streams/) | live | Overlapping compute and data transfer, CUDA streams, events, concurrency patterns, the default stream trap. |
| 09 | [Libraries &amp; Ecosystem](https://brendanjameslynskey.github.io/CUDA_09_Libraries/) | live | cuBLAS, cuDNN, Thrust, cuRAND, cuFFT &mdash; when to write custom kernels vs use optimised libraries. |
| 10 | [Hardware Platforms for CUDA Learning](https://brendanjameslynskey.github.io/CUDA_10_Hardware/) | live | Practical buying guide &mdash; DGX Spark, consumer GPUs, cloud instances, Colab &mdash; cost, capability, recommendations. |

## Where this fits

Part of the [LLMs hub](https://github.com/BrendanJamesLynskey/LLMs) &mdash; an index of presentation series for AI/LLM engineers.

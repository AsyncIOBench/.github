# NVMe Storage Benchmarking & Optimization

**AsyncIOBench** is a research-driven organization focused on benchmarking and optimizing **NVMe storage performance** using different I/O engines. We analyze how storage technologies like **libaio, io_uring, and SPDK** impact read/write speed, latency, and throughput. 

## What We Do
- **Benchmark NVMe storage** under different workloads.
- **Compare I/O engines** (`libaio`, `io_uring`, and `SPDK`).
- **Analyze performance metrics**: IOPS, latency, and bandwidth.
- **Evaluate RocksDB on NVMe**, optimizing database performance.

## Project Overview
Below is a diagram illustrating the key components of our benchmarking and analysis framework, including the I/O engines, test types, performance metrics (IOPS, latency, and bandwidth), and the comparison of results between `libaio`, `io_uring`, and `SPDK`.

![Project Overview](https://github.com/AsyncIOBench/.github/blob/main/overview.png)

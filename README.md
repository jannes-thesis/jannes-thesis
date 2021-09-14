This profile collects all the code for my Master thesis "An OS-level adaptive thread pool scheme for I/O-heavy workloads".
https://repository.tudelft.nl/islandora/object/uuid%3A5c9b4c42-8fdc-4170-b978-f80cd8f00753?collection=education

## Abstract
Thread pools are a pervasive building block for concurrent applications, but their optimal size is often tedious to determine or it changes during execution. Many modern systems use dedicated thread pools for operations that are restricted to a specific resource (e.g IO-bound), their performance can be correlated to OS metrics such as disk throughput. We propose an OS-level adaptive scheme for disk-IO workloads that can act as drop-in replacement for such use cases. Our approach often performs close to optimally tuned fixed-size pools, while being prone to fluctuations in the chosen target metric. The results warrant further exploration of more sophisticated OS metrics and the development of more tightly integrated global in-kernel implementations.

## Repositories

### linux-kernel
the patch that adds tracesets capability to the linux kernel

### scaling-adapter: 
- scaling adapter module
- adaptive/fixed/watermark threadpool
- benchmarking binary

### rocks-io-benchmark: 
- modififed RocksDB sources
- benchmarking scripts

### node-io-benchmark: 
- modified Node sources 
- benchmarking scripts

### threadpool-c
- fixed and adaptive implementation of threadpool (not used in final benchmarking,
the Rust implementation is used instead)

### bench-runner: 
- scripts for running workloads for adaptive/fixed pool, Node & RocksDB
- collection of results
- scripts for generating graphs for report

The submodules in this repository (poiting to the scaling-adapter, rocks-io-benchmark,
node-benchmark and threadpool-c) are pointing to private repositories
and would have to be udpated to the public repositories on this profile to use the benchmarking script main.py.





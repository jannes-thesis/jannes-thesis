This profile collects all the code for my Master thesis "An OS-level adaptive thread pool scheme for I/O-heavy workloads".

### linux-kerne
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





29 01 25

- Create Project and add Dependencies
  - Pkg.add("Distributed")
    Pkg.add("LinearAlgebra")
    Pkg.add("BenchmarkTools")
    Pkg.add("Plots")
(Done)

- Use Julia's multi-threading capabilities to simulate shared-memory parallelism (e.g., multi-core CPUs).

- Use the Distributed standard library to simulate distributed memory systems.

- Use the MPI.jl package to simulate message-passing between nodes, which is a common pattern in HPC.

- Simulate typical HPC workloads, such as matrix operations, solving differential equations, or running Monte Carlo simulations.

- Use Julia's benchmarking and profiling tools to analyze the performance of your simulated HPC system.

- Simulate GPU-accelerated HPC workloads using packages like CUDA.jl or AMDGPU.jl.

- Use Julia to model the communication patterns and network topologies of an HPC system.
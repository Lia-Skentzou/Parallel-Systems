# Parallel-Systems
School of Electrical and Computer Engineering, NTUA | Parallel Systems Laboratory | Spring 2024

## Summary

This lab investigates key techniques in parallel programming through the implementation and benchmarking of several algorithms. Starting with the Game of Life cellular automaton, we evaluate how thread count and matrix size impact performance. The lab then explores multiple parallel implementations of the K-means clustering algorithm and compares locking mechanisms. Finally, we apply different optimizations to the Floyd-Warshall shortest-path algorithm.

## Topics Covered

- OpenMP-based parallelism
- Thread scheduling and load balancing
- Cache effects and NUMA-aware programming
- Synchronization strategies: atomic, critical, spinlocks, mutexes, CLH, etc.
- Optimization techniques for shared vs. local data structures

## Technologies Used

- C
- OpenMP
- Shell scripting (bash)
- Gnuplot / matplotlib (for plotting)
- Linux (for NUMA and thread affinity configuration)

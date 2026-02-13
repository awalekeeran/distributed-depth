# Sliding Window Pattern

The **Sliding Window** technique is used to perform required operations on a specific window size of a given array or linked list, such as finding the longest subarray containing all unique characters. It optimizes "brute force" solutions from $O(N^2)$ to linear time $O(N)$.

## Table of Contents
1. [Core Logic & Templates](./pattern-template.md)
2. [Complexity Analysis](./theory-and-notes.md)
3. [Real-World System Applications](./real-world-use-cases.md)
4. [Solutions & Performance Benchmarks](./benchmarks.py)

## Why This Matters (Senior Context)
As a Senior Engineer, mastering this isn't just about LeetCode; it's about understanding **stream processing** and **resource efficiency**. Sliding windows are the fundamental mechanism behind:
- **TCP Flow Control:** Managing data packets in transit.
- **API Rate Limiting:** Protecting services from abuse via "Sliding Window Log" algorithms.
- **Analytics:** Calculating rolling metrics in real-time streaming data.

## Types of Sliding Window
- **Fixed-Size Window**
- **Dynamic/Variable-Size Window**

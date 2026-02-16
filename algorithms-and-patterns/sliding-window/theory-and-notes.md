# Why Sliding Window exists ?

Because many problems require:
- "What is the best/maximum/minimum contiguous segment of length **K**?"
- "Process data within the last **X minutes** continously."

## Types of Sliding Windows

### Fixed-Size Sliding Window (Constant Window Size)
Window size = **K**, remains constant.

#### When to use
- "Maximum sum of subarray of size K"
- "First negative in every window of size K"
- "Moving averages/rolling averages"

---

### Variable-Size Sliding Window
Window expands/shrinks based on conditions.

#### When to use
- "Longest substring without repeating characters"
- "Smallest subarray >= target sum"
- "Longest substring with <= K distinct characters"

---

### Sliding Window with Two Pointers
Two pointers (L,R) track the current window.
Useful when:
- Condition-driven resizing
- Operates like variable window
- Efficient for "two-pointer" array/string operations

--- 
### Monotonic Sliding Window (Deque Assisted)
Used when we want:
- min/max in every window
- maintaining a sorted-like window efficiently

---
### Cyclic or Circular Sliding Window
Useful in:
- scheduling (round-robin)
- token bucket / rate limiters

---

## System Design Use-Cases

- ### API Rate Limiting
  Patterns:
  - fixed window counter
  - sliding log
  - sliding window rate limiter
- ### Real-time Monitoring / Analytics
  - number of failed logins in last 10 mins
  - CPU average in last 5 mins
  - Requests per minute(RPM)
- ### Stream Processing (Kafka, Spark, Flink)
  Sliding window computes
  - rolling sums
  - rolling counts
  - anomaly detection
  
  Used in:
  - Streaming ETL jobs
  - Clickstream analytics
  - fraud detection

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

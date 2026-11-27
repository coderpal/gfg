## 01. Scientific Format

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/scientific-format--141631/1?selectedLang=python3)

### Problem Description

**Task:** There are times when your answer is a double data type and you want to show the same in scientific format. You need to take a double data type variable as a and output its value in scientific format upto 4 precision.Examples :Input: a = 5.43

#### Examples

##### Example 1

- **Output:**
```text
5.4300e+00
```

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (Python)

- **Submitted:** 2026-11-27 23:14:53
- **Status:** Correct
- **Marks:** 2

```python
# code here
a = float(input().strip())
print(f"{a:.4e}", end = "")
```

*Generated on: 27/11/2026, 23:15:01*
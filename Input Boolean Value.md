## 01. Input Boolean Value

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/input-boolean-value/1?selectedLang=python3)

### Problem Description

**Task:** Take a boolean value a as an input. The program should display its numeric representation:
1 for "true"
0 for "false"

#### Examples

##### Example 1

- **Input:**
```text
a = true
```
- **Output:**
```text
1
```

##### Example 2

- **Input:**
```text
a = false
```
- **Output:**
```text
0
```

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (Python)

- **Submitted:** 2026-11-27 21:38:46
- **Status:** Correct
- **Marks:** 1

```python
# code here
a = input().strip().lower()
print(1 if a == "true" else 0, end = "")
```

*Generated on: 27/11/2026, 21:38:56*
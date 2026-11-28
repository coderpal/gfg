## 01. 2 Sum - Find a pair with given sum

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/2-sum-find-a-pair-with-given-sum/1)

### Problem Description

**Task:** Given an array arr[] and an integer target, return the pair of elements whose sum equals target. An element cannot be used twice unless it appears multiple times in the array.Note: If no pair exist, return an empty array.Examples:Input: arr[] = [2, 9, 10, 4, 15], target = 12

#### Examples

##### Example 1

- **Output:**
```text
[1, 1]
```
- **Explanation:** Pair with sum equal to 2 is (1, 1).

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(n)
- **Expected Auxiliary Space Complexity:** O(n)

### Accepted Solutions (1)

#### Solution 1 (Python)

- **Submitted:** 2026-11-28 10:24:23
- **Status:** Correct
- **Marks:** 2

```python
class Solution:
    # Complete the below function
    def twoSum(self,arr, target):
        # Your code here
        seen = set()
        
        n = len(arr)
        
        for n in arr:
            
            complement = target - n
            
            if complement in seen:
                return [complement, n]
            
            seen.add(n)
            
        return []
```

*Generated on: 28/11/2026, 10:24:37*
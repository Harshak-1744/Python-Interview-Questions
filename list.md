# Check if the first and last number of a list is the same


## **Problem Statement**

Write a Python function `is_first_and_last_same(numbers)` that takes a list of numbers as input and returns `True` if the first and last number of the list are the same, and `False` otherwise.


**Input:**

- A list of integers `numbers` (1 <= len(numbers) <= 1000), where `numbers` represents a list of numbers.

**Output:**

- `True` if the first and last number in the list are the same.
- `False` if the first and last number in the list are different.

**Example:**

**Input:**
```python
numbers_x = [10, 20, 30, 40, 10]
is_first_and_last_same(numbers_x)
```

**Output:**
```
Given list: [10, 20, 30, 40, 10]
Result is True
```

**Input:**
```python
numbers_y = [75, 65, 35, 75, 30]
is_first_and_last_same(numbers_y)
```

**Output:**
```
Given list: [75, 65, 35, 75, 30]
Result is False
```

**Note:**

- The function should compare the first and last elements of the input list `numbers` to determine if they are the same or different.
- Ensure that the function handles lists of varying lengths and different integer values.

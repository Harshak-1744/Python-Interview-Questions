# Remove first n characters from a string

## **Problem Statement**

Write a Python program that removes characters from the beginning of a string up to the specified index `n` (0-based) and returns a new string.

## **Function Signature:**

```python
def remove_chars(s: str, n: int) -> str:
    pass
```

**Input:**

- A string `s` (1 <= len(s) <= 1000), where `s` is the input string.
- An integer `n` (0 <= n < len(s)), which represents the number of characters to remove from the beginning of the string.

**Output:**

- A new string containing the characters after removing the first `n` characters from the input string.

**Example:**

**Input:**
```python
remove_chars("pynative", 4)
```

**Output:**
```python
"tive"
```

**Input:**
```python
remove_chars("pynative", 2)
```

**Output:**
```python
"native"
```

**Note:**

- The input string can contain letters (both uppercase and lowercase), digits, and special characters.
- Ensure that `n` is within the valid range, i.e., 0 <= n < len(s)

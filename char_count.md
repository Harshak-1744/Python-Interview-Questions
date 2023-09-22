## Problem Statement: Counting Letters, Digits, and Special Symbols in a String

 You are tasked with creating a program or function that takes a string as input and counts the following components within the string: letters, digits, and special symbols. Your goal is to provide an accurate count of each of these categories.

### Input:
- A string containing a combination of letters (uppercase and lowercase), digits (0-9), and special symbols.

### Output:
- Three counts:
  1. The number of letters (both uppercase and lowercase) in the input string.
  2. The number of digits (0-9) in the input string.
  3. The number of special symbols in the input string. Special symbols include any characters that are not letters or digits.

### Constraints:
- The input string may contain any printable characters.
- The input string can have a length of up to 10^6 characters.
- The output counts should be non-negative integers.

#### Sample Input 1:
```python
input_string = "Hello123!@World"
```

#### Sample Output 1:
```python
Letters: 10
Digits: 3
Special Symbols: 2
```

Explanation: In this input string, there are 10 letters (H, e, l, l, o, W, o, r, l, d), 3 digits (1, 2, 3), and 2 special symbols (!, @).

---

#### Sample Input 2:
```python
input_string = "Testing 123"
```

#### Sample Output 2:
```python
Letters: 7
Digits: 3
Special Symbols: 1
```

Explanation: In this input string, there are 7 letters (T, e, s, t, i, n, g), 3 digits (1, 2, 3), and 1 special symbol (space).

---

#### Sample Input 3:
```python
input_string = "NoSpecialChars123"
```

#### Sample Output 3:
```python
Letters: 14
Digits: 3
Special Symbols: 0
```

Explanation: In this input string, there are 14 letters (N, o, S, p, e, c, i, a, l, C, h, a, r, s), 3 digits (1, 2, 3), and no special symbols.

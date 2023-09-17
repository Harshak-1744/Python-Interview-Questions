# Create a function with a default argument

## **Problem Statement:**

Create a Python function named `show_employee` that accepts the employee's name and salary as arguments. If the salary is missing in the function call, assign a default value of 9000 to the salary and display both the name and salary.

**Sample Input:**

You can call the `show_employee` function with the employee's name and, optionally, the salary.

**Sample 1:**

```python
name1 = "Ben"
salary1 = 12000
```

**Sample 2:**

```python
name2 = "Jessa"
```

**Sample Output:**

The function should display the employee's name and salary, where the salary defaults to 9000 if not provided.

**Sample 1 Output:**

```python
show_employee("Ben", 12000)
```

Output:

```
Name: Ben salary: 12000
```

**Sample 2 Output:**

```python
show_employee("Jessa")
```

Output:

```
Name: Jessa salary: 9000
```

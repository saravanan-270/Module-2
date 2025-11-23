# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS

---

### AIM  
To write a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.

---

### ALGORITHM

1. Begin the program.  
2. Use `int(input())` to get two numbers (`num1` and `num2`) from the user.  
3. Define a lambda function `max` that takes two arguments `x` and `y`.  
4. The lambda function compares the numbers and prints:
   - If `x > y`, then it prints: "`num2` is smaller than `num1`".
   - Otherwise, it prints: "`num1` is smaller than `num2`".
5. Call the lambda function by passing `num1` and `num2` as arguments.  
6. Terminate the program.

---

### PROGRAM
```python
num1 = int(input())
num2 = int(input())
find_smaller = lambda x, y: x if x<y else y
smaller_number = find_smaller(num1,num2)
print(f"{num1} is smaller than {num2}")
```


### OUTPUT

<img width="601" height="187" alt="image" src="https://github.com/user-attachments/assets/0cf130c5-f1b6-4350-939f-5d11479475ac" />




### RESULT


Thus the python program for check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function has been implemented and executed successfully.

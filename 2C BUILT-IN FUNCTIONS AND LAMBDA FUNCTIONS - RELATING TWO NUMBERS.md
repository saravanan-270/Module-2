# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS

---

### AIM  
To write a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.

---

### ALGORITHM

1. Begin the program.  
2. Use `eval()` to get two numbers (`num1` and `num2`) from the user.  
3. Define a lambda function `max` that takes two arguments `x` and `y`.  
4. The lambda function compares the numbers and prints:
   - If `x > y`, then it prints: "`num2` is smaller than `num1`".
   - Otherwise, it prints: "`num1` is smaller than `num2`".
5. Call the lambda function by passing `num1` and `num2` as arguments.  
6. Terminate the program.

---

### PROGRAM

```
x=int(input())
y=int(input())
if(x<y):
    print(x,"is smaller than",y)
else:
    print(y,"is smaller than",x)
```

### OUTPUT

![image](https://github.com/user-attachments/assets/6e67c26d-dc94-4b05-83e5-ecdb0c737c5b)


### RESULT

```
Thus a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.
has been implemented and executed successfully.

```

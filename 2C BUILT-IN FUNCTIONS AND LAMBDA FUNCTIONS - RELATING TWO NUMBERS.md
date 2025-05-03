# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS

---

### AIM  
To Create a Python Program to  find the greatest of two numbers using lambda function.

---

### ALGORITHM

1. Begin the program.  
2. Use `eval()` to get two numbers (`num1` and `num2`) from the user.  
3. Define a lambda function `max` that takes two arguments `x` and `y`.  
4. The lambda function compares the numbers and prints:
   - If `x > y`, then it prints: "`num1` is greater than `num2`".
   - Otherwise, it prints: "`num2` is greater than `num1`".
5. Call the lambda function by passing `num1` and `num2` as arguments.  
6. Terminate the program.

---

### PROGRAM

```
Max = lambda a, b : a if(a > b) else b
 
input1=int(input())
input2=int(input())
print("The greatest number is:",Max(input1,input2))

```

### OUTPUT

```

![image](https://github.com/user-attachments/assets/7ad14f0d-91c0-4fe1-91eb-a41d9baaa7f7)


```

### RESULT

```
Thus, the Python Program for finding the greatest of two numbers using lambda function is executed sucessfully.
```

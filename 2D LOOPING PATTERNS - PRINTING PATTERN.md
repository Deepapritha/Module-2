# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

---

### AIM  
To Write a python program  to print the downward pyramid pattern of stars using looping.


---

### ALGORITHM

1. Begin the program.  
2. Read the integer `n` from the user using `input()`. This will determine the number of rows in the pattern.  
3. Set up a loop from rows + 1 down to 1 (exclusive), decreasing by 1
4. Inside the loop, start a nested loop from 0 to i - 2
   In the nested loop, print a star followed by a space (* ) on the same line
   After the nested loop, print a newline to move to the next row
5. Terminate the program.

---

### PROGRAM
```
rows = int(input())
for i in range(rows + 1, 0, -1):
    for j in range(0, i - 1):
        print("*", end=' ')
    print(" ")


```

### OUTPUT
![image](https://github.com/user-attachments/assets/82f0666b-0404-4e04-89c9-819c0b8b8935)


### RESULT
Thus,the python program for printing the downward pyramid pattern of stars using looping is done successfully.

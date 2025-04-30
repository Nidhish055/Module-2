# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

---

### AIM  
To write a Python program to print inverted pyramid pattern of numbers using loops.

---

### ALGORITHM


1. Start the program.
2. Read the integer n from the user using input(). This determines the number of rows.
3. Loop through each row from 0 to n - 1:
   a. Print spaces to align the stars in a triangular pattern.
   b. Print stars with double spaces between them.
   c. Move to the next line after each row.
4. End the program.


---

### PROGRAM
```python
#Reg.No:212223050032
#Name:Nidhish B

n=int(input())
for i in range(n):
    for j in range(n-i):
        print(i+1,end=" ")
    print()

```

### OUTPUT

![image](https://github.com/user-attachments/assets/9928039b-c0df-46a9-ba93-5f4ac9dd0ea5)

### RESULT

Thus the python program to print inverted pyramid pattern of numbers using loops is successfully executed.

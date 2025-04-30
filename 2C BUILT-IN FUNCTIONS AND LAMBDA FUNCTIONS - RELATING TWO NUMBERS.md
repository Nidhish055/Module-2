# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS

---

### AIM  

To write a Python program to find the greatest of two numbers using lambda function.

---

### ALGORITHM

 1. Start the program.
 2. Get two numbers from the user using input() and convert them to integers.
 3. Define a lambda function that returns the greater of the two numbers.
 4. Call the lambda function with the two input numbers.
 5. Print the greatest number.
 6. End the program.


---

### PROGRAM

```python
#Name: Nidhish B
#Reg No : 212223050032

a=int(input())
b=int(input())

greater=lambda a,b:a if a>b else b
greatest=greater(a,b)

print(f"The greatest number is: {greatest}")
```

### OUTPUT

![image](https://github.com/user-attachments/assets/52c3f879-09ee-4c60-ad2a-40aa7f818c32)


### RESULT

Thus the program to find the greatest of two numbers using lambda function successfully executed.

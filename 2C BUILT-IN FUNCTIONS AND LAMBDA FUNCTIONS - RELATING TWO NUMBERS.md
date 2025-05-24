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
# Reg.No-
# Name-
# Add your code here

# Using eval() to get input from the user
num1, num2 = eval(input("Enter two numbers separated by a comma (e.g., 5, 3): "))

# Define the lambda function to compare the two numbers
check_relation = lambda x, y: print(f"num1 is greater than num2" if x > y else (f"num1 is smaller than num2" if x < y else f"num1 is equal to num2"))

# Call the lambda function
check_relation(num1, num2)

```

### OUTPUT


![image](https://github.com/user-attachments/assets/6d25c13e-9efd-40e4-892a-d03f4d0b34cf)


### RESULT

```
Thus, the Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function was successfully created and executed.

```

# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

---

### AIM  
To write a Python program to print a triangular star pattern using loops.

---

### ALGORITHM

1. Begin the program.  
2. Read the integer `n` from the user using `input()`. This will determine the number of rows in the pattern.  
3. Initialize a variable `i = 0`. This will help adjust the spacing before the stars.  
4. Loop through rows from `0` to `n - 1`:  
   - For each row, calculate the number of spaces to print using the formula: `((n - rows - 1) * 2) + i`.  
   - Print the calculated number of spaces using `print(" ", end="")`.  
   - Increment `i` by 1 after each row.  
   - Print stars using a nested loop: the number of stars in each row is `rows + 1`, printed using `print("*", end="  ")`.  
   - Print a newline after each row using `print("")` to move to the next line.  
5. Terminate the program.

---

### PROGRAM
```
#Reg.No:212222063014
#Name:SARATH KUMAR.K
#Add Your Code Here
rows=int(input())
for i in range(rows,0,-1):
    for j in range(0,i):
        print("*",end=" ")
    print()
```

### OUTPUT
<img width="606" height="557" alt="image" src="https://github.com/user-attachments/assets/09eb83fb-4289-4cac-be11-8e68a39f5d2c" />

### RESULT
Thus the Python program to print a downward pyramid star pattern using loops was executed successfully and the output was verified.

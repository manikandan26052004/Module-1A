# Experiment No: 1e – SEB-Minimum of Three Numbers

## AIM  
To write a Python program to find the minimum between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM  
1. Begin the program.  
2. Read the three numbers: `num1`, `num2`, and `num3` from the user.  
3. Compare `num1`, `num2`, and `num3` to find the smallest number:  
   - If `num1` is less than or equal to both `num2` and `num3`, then `num1` is the minimum.  
   - Else, if `num2` is less than or equal to both `num1` and `num3`, then `num2` is the minimum.  
   - Otherwise, `num3` is the minimum.  
4. Print the minimum value along with the input numbers in the format:  
   `"The minimum of num1, num2, num3 is min_num."`  
5. Terminate the program.

## PROGRAM
```
python
# Reg.No-212222220022
# Name-MANIKANDAN R
# Write your code here

a=eval(input())
b=eval(input())
c=eval(input())
if(a<b and a<c):
    print(f"The Smallest  of the three a= {a} b= {b} c= {c} is",a)
elif(b<c):
    print(f"The Smallest  of the three a= {a} b= {b} c= {c} is",b)
else:
    print(f"The Smallest  of the three a= {a} b= {b} c= {c} is",c)

```

## OUTPUT

![Screenshot 2025-04-25 072743](https://github.com/user-attachments/assets/3bf13bf3-9560-4052-9618-f5c2d0f6ec36)

## RESULT
Thus Python program to find the minimum between three integer numbers using a conditional expression (Ternary operator) is successfully executed.

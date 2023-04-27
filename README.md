# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by:212222240081 
RegisterNumber:RAGUNATH R
def newton_method(n1,n2=100):
    a=float(n1)
    for i in range(n2):
        n1=0.5*(n1+a/n1)
    return n1
a=int(input())
print("Square root of the number:",newton_method(a))
*/
```

## Output:
![image](https://user-images.githubusercontent.com/113915622/234807614-6366c51a-b99d-44de-8fb5-1b207ca6a02d.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.

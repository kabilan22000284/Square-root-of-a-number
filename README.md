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
Developed by: kabilan v
RegisterNumber:  212222100018
*/
def sqroot():
    n1=int(input())
    n2=float(n1)
    for i in range(100):
        n1=0.5*(n1+n2/n1)
    print("Square root of the number:",n1)
sqroot()
```

## Output:
![Screenshot (30)](https://github.com/kabilan22000284/Square-root-of-a-number/assets/123469171/6a5596b2-8b70-441b-8047-3677e32c47c2)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.

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
Developed by: jivankarthec.B.S
RegisterNumber:  22004763
*/
def sq():
    x=int(input())
    b=float(x)
    for i in range(100):
        x=0.5*(x+b/x)
    print("Square root of the number:",x)
sq()

```

## Output:
![c5](https://user-images.githubusercontent.com/121165867/212467369-2c126879-6107-4e5d-88e3-67b7fc3126da.png)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.

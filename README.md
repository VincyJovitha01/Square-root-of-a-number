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
Developed by: Vincy Jovitha V
RegisterNumber:  212223230242
*/
def sqrt(num,num_it=100):
    a=float(num)
    for i in range(num_it):
        num=0.5*(num+a/num)
    return num
a=int(input())
print("Square root of the number:",sqrt(a))
```

## Output:
![Screenshot 2024-03-31 172956](https://github.com/VincyJovitha01/Square-root-of-a-number/assets/147121113/34caf52f-139a-46ce-b26a-be99ab519f2f)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.

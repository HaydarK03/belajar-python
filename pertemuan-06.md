3.1.13 SECTION SUMMARY
1. The comparison (otherwise known as relational) operators are used to compare values. The table below illustrates how the comparison operators work, assuming that x = 0, y = 1, and z = 0:

![screenshot-skillsforall_com-2024_08_07-14_28_37](https://github.com/user-attachments/assets/15e6a35d-3dba-463e-a0fd-caf66dc9fe5d)


2. When you want to execute some code only if a certain condition is met, you can use a conditional statement:

a single if statement, e.g.:
```
x = 10
 
if x == 10: # condition
    print("x is equal to 10")  # Executed if the condition is True.
 ```
a series of if statements, e.g.:
```
x = 10
 
if x > 5: # condition one
    print("x is greater than 5")  # Executed if condition one is True.
 
if x < 10: # condition two
    print("x is less than 10")  # Executed if condition two is True.
 
if x == 10: # condition three
    print("x is equal to 10")  # Executed if condition three is True.
 
    Each if statement is tested separately.
```
an if-else statement, e.g.:
```
x = 10
 
if x < 10: # condition
    print("x is less than 10")  # Executed if the condition is True.
 
else:
    print("x is greater than or equal to 10")  # Executed if the condition is False.
 ```
a series of if statements followed by an else, e.g.:
```
x = 10
 
if x > 5: # condition one
    print("x is greater than 5")  # Executed if condition one is True.
 
if x < 10: # condition two
    print("x is less than 10")  # Executed if condition two is True.
 
if x == 10: # condition three
     print("x is equal to 10")  # Executed if condition three is True.
``` 
Each if is tested separately. The body of else is executed if the last if is False.

The if-elif-else statement, e.g.:
```
x = 10
 
if x == 10: # True
    print("x == 10")
 
if x > 15: # False
    print("x > 15")
 
elif x > 10: # False
    print("x > 10")
 
elif x > 5: # True
    print("x > 5")
 
else:
    print("else will not be executed")
```
If the condition for if is False, the program checks the conditions of the subsequent elif blocks - the first elif block that is True is executed. If all the conditions are False, the else block will be executed.

Nested conditional statements, e.g.:
```
x = 10
 
if x > 5: # True
    if x == 6: # False
        print("nested: x == 6")
    elif x == 10: # True
        print("nested: x == 10")
    else:
        print("nested: else")
else:
    print("else")
 ```

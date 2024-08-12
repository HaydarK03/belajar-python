# 3.2.10   LAB   The continue statement – the Ugly Vowel Eater
## Scenario
The continue statement is used to skip the current block and move ahead to the next iteration, without executing the statements inside the loop.

It can be used with both the while and for loops.

Your task here is very special: you must design a vowel eater! Write a program that uses:

1. a for loop;
2. the concept of conditional execution (if-elif-else)
3. the continue statement.
   
Your program must:

- ask the user to enter a word;
- use user_word = user_word.upper() to convert the word entered by the user to upper case; we'll talk about string methods and the upper() method very soon – don't worry;
- use conditional execution and the continue statement to "eat" the following vowels A, E, I, O, U from the inputted word;
- print the uneaten letters to the screen, each one of them on a separate line.
Test your program with the data we've provided for you.


Test data:
Sample input:
Gregory

Expected output:
```
G
R
G
R
Y
```

Sample input:
abstemious

Expected output:
```
B
S
T
M
S
```

Sample input:
IOUEA

Expected output:
```

 ```

### solution
```

user_word = input("enter your word: ")
user_word = user_word.upper()

for letter in user_word:
    if letter == "A":
        continue
    elif letter == "I":
        continue
    elif letter == "U":
        continue
    elif letter == "E":
        continue
    elif letter == "O":
        continue
    else:
        print(letter)

```

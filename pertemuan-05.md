# interaction with user
2.6.12 SECTION SUMMARY
1. The print() function sends data to the console, while the input() function gets data from the console.

2. The input() function comes with an optional parameter: the prompt string. It allows you to write a message before the user input, e.g.:

```
name = input("Enter your name: ")
print("Hello, " + name + ". Nice to meet you!")
 ```
3. When the input() function is called, the program's flow is stopped, the prompt symbol keeps blinking (it prompts the user to take action when the console is switched to input mode) until the user has entered an input and/or pressed the Enter key.

  Note  
You can test the functionality of the input() function in its full scope locally on your machine. For resource optimization reasons, we have limited the maximum program execution time in Edube to a few seconds. Go to the Sandbox, copy-paste the above snippet, run the program, and do nothing ‒ just wait a few seconds to see what happens. Your program should be stopped automatically after a short moment. Now open IDLE, and run the same program there ‒ can you see the difference?

Tip: the above-mentioned feature of the input() function can be used to prompt the user to end a program. Look at the code below:

```
name = input("Enter your name: ")
print("Hello, " + name + ". Nice to meet you!")
 
print("\nPress Enter to end the program.")
input()
print("THE END.")
 ```
4. The result of the input() function is a string. You can add strings to each other using the concatenation (+) operator. Check out this code:
```

num_1 = input("Enter the first number: ") # Enter 12
num_2 = input("Enter the second number: ") # Enter 21
 ```
print(num_1 + num_2) # the program returns 1221
 
5. You can also multiply (* ‒ replication) strings, e.g.:

```
my_input = input("Enter something: ") # Example input: hello
print(my_input * 3) # Expected output: hellohellohello
 ```

# 2.1.5   LAB   Working with the print() function
## Scenario
The print() command, which is one of the easiest directives in Python, simply prints out a line to the screen.

In your first lab:

Use the print() function to print the line Hello, Python! to the screen. Use double quotes around the string.
Having done that, use the print() function again, but this time print your first name.
Remove the double quotes and run your code. Watch Python's reaction. What kind of error is thrown?
Then, remove the parentheses, put back the double quotes, and run your code again. What kind of error is thrown this time?
Experiment as much as you can. Change double quotes to single quotes, use multiple print() functions on the same line, and then on different lines. See what happens.

### solution
```
# Sample Solution

print("Hello, Python!")
# print("Greg")
# print(Greg)
# print"Greg"
# print('Greg')
# print("Greg") print("Python")
# ...</sampleSolution>
```

# 2.1.12   LAB   The print() function and its arguments
## Scenario
Modify the first line of code in the editor, using the sep and end keywords, to match the expected output. Use the two print() functions in the editor.

Don't change anything in the second print() invocation.

Expected output
`Programming***Essentials***in...Python`

### solution
```
print("Programming","Essentials","in", sep="***", end="...")
print("Python")
```

# 2.1.13   LAB   Formatting the output
## Scenario
We strongly encourage you to play with the code we've written for you, and make some (maybe even destructive) amendments. Feel free to modify any part of the code, but there is one condition ‒ learn from your mistakes and draw your own conclusions.

Try to:

- minimize the number of print() function invocations by inserting the \n sequence into the strings;
- make the arrow twice as large (but keep the proportions)
- duplicate the arrow, placing both arrows side by side; note: a string may be multiplied by using the following trick: "string" * 2 will produce "stringstring" (we'll tell you more about it soon)
- remove any of the quotes, and look carefully at Python's response; pay attention to where Python sees an error ‒ is this the place where the error really exists?
- do the same with some of the parentheses;
- change any of the print words into something else, differing only in case (e.g., Print) ‒ what happens now?
- replace some of the quotes with apostrophes; watch what happens carefully.

### solution
```
###################
print("original version:")
###################
print("    *")
print("   * *")
print("  *   *")
print(" *     *")
print("***   ***")
print("  *   *")
print("  *   *")
print("  *****")
###################
```

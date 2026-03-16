Aim:
To study and implement decision-making and problem-solving techniques in Python using conditional statements and logical operations to perform real-world computations and validations.

Theory:
Conditional statements in Python control the execution of a program based on specific conditions. The if, elif, and else statements allow the program to evaluate logical and relational expressions and execute different blocks of code depending on whether the condition is true or false.

These constructs are widely used in applications such as number classification, grading systems, salary and tax calculations, input validation, searching operations, and manipulation of dates or strings. Python supports relational operators (>, <, >=, <=, ==, !=) and logical operators (and, or, not) to build complex conditions. When combined with loops, conditional statements help in handling repetitive tasks and solving real-world computational problems efficiently and accurately.

Algorithm 1: Display Numbers from 1 to N Using While Loop

Start

Input a number n from the user.

Initialize a variable i = 1.

Check whether i ≤ n.

If true, display the value of i.

Increment i by 1.

Repeat steps 4 to 6 until the condition becomes false.

Stop

Algorithm 2: Find Factorial of a Number Using While Loop

Start

Input a number n from the user.

Initialize fact = 1.

Check whether n > 0.

If true, update fact = fact × n.

Decrease n by 1.

Repeat steps 4 to 6 until n = 0.

Display the factorial value.

Stop

Algorithm 3: Generate Fibonacci Sequence Using While Loop

Start

Input the number of terms n from the user.

Initialize a = 0, b = 1, and terms = 1.

Check whether terms ≤ n.

Display the value of a.

Calculate c = a + b.

Assign a = b and b = c.

Increment terms by 1.

Repeat steps 4 to 8 until the condition becomes false.

Stop

Algorithm 4: Generate Fibonacci Sequence Up to a Given Limit

Start

Input the limit value from the user.

Initialize a = 0 and b = 1.

Check whether a ≤ limit.

Display the value of a.

Update the values of a and b accordingly.

Repeat steps 4 to 6 until a exceeds the limit.

Stop

Algorithm 5: Find the Reverse of a Number Using While Loop

Start

Input a number n from the user.

Initialize rev = 0.

Check whether n > 0.

Find the last digit using digit = n % 10.

Update rev = rev × 10 + digit.

Remove the last digit using n = n // 10.

Repeat steps 4 to 7 until n = 0.

Display the reversed number.

Stop

Algorithm 6: Check Whether a String is a Palindrome (Using Comparison)

Start

Input a string from the user.

Initialize i = 0 and j = length of string − 1.

While i < j, compare characters at positions i and j.

If the characters are not equal, display “Not a Palindrome” and terminate.

Otherwise, increment i and decrement j.

If all characters match, display “Palindrome.”

Stop

Algorithm 7: Check Whether a String is a Palindrome Using Reversal

Start

Input a string from the user.

Create the reversed version of the string.

Compare the original string with the reversed string.

If both are equal, display “Palindrome.”

Otherwise, display “Not a Palindrome.”

Stop

Algorithm 8: Count the Number of Digits in a Number

Start

Input a number from the user.

Initialize count = 0.

While the number is greater than 0:

Divide the number by 10 using integer division.

Increment count by 1.

Display the value of count.

Stop

Algorithm 9: Search an Element in a List Using While Loop

Start

Create a list containing elements.

Input the element to be searched (key).

Initialize i = 0.

Check whether i < length of the list.

Compare the element at index i with the key.

If equal, display the index position and terminate the loop.

Otherwise, increment i by 1.

Repeat steps 5 to 8 until the element is found or the list ends.

If the element is not found, display “Element not found.”

Stop

Algorithm 10: Print Odd Numbers Between 1 and 10 Using While Loop

Start

Initialize i = 0.

Check whether i < 10.

Increment i by 1.

If i is divisible by 2, skip the iteration.

Otherwise, display the value of i.

Repeat steps 3 to 6 until the condition becomes false.

Stop

Conclusion:
Thus, decision-making and problem-solving techniques in Python were successfully studied and implemented using conditional statements and loops. The experiment illustrated how logical conditions and iterative constructs can be applied to solve practical problems such as factorial calculation, Fibonacci series generation, palindrome checking, element searching, and number manipulation. These programs strengthened our understanding of program control flow and emphasized the role of conditional logic in developing efficient Python applications.

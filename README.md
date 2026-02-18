# Experiment 7: Study Of Loops in Python
# Aim

To study and implement looping constructs in Python using while loops and control statements (break, continue) to solve various computational problems.

# Theory

Loops are control structures that allow repeated execution of a block of statements until a specified condition becomes false. They reduce code repetition and make programs efficient.

1. While Loop

     Executes statements as long as condition is true.

     Used when number of iterations is unknown.

2. Break Statement

      Terminates loop immediately.

      Used when a stopping condition is met.

3. Continue Statement

      Skips current iteration.

      Moves execution to next iteration.

# Algorithms:
## 1. Print numbers less than 6: 

    Start

    Initialize i = 1

    While i < 6

    Print i

    Increment i

    Stop

## 2. Print numbers from 1 to n:

    Start

    Input n

    Set i = 1

    While i ≤ n

    Print i

    Increment i

    Stop

## 3. Factorial of a number: 

    Start

    Input n

    Set fact = 1

    While n > 0

    fact = fact × n

    Decrement n

    Print fact

    Stop

## 4. Fibonacci Series (Method 1):

    Start

    Input number of terms n

    Initialize a = 0, b = 1, i = 1

    While i ≤ n

    Print a

    c = a + b

    a = b, b = c

    Increment i

    Stop

##  Fibonacci Series (Method 2):

    Start

    Input limit

    Set a = 0, b = 1

    While a ≤ limit

    Print a

    Swap values: a, b = b, a + b

    Stop

## 5. Reverse a Number:

    Start

    Input number

    Set rev = 0

    While number > 0

    Extract digit = number % 10

    rev = rev × 10 + digit

    Remove last digit (num //= 10)

    Print reversed number

    Stop

## 6. Check Palindrome Number:

    Start

    Input number

    Store original in temp

    Reverse digits using loop

    Compare reversed with original

    If equal : Palindrome

    Else : Not palindrome

    Stop

## 7. String Palindrome (Manual Comparison):

    Start

    Input string s

    Set i = 0, j = len(s) - 1

    Assume palindrome = True

    While i < j

    If s[i] != s[j] : Not palindrome : break

    Increment i, decrement j

    Print result

    Stop

## 8. Palindrome using Slicing:

    Start

    Input string

    Reverse string using slicing [::-1]

    Compare original and reversed

    If equal : Palindrome

    Else : Not palindrome

    Stop

## 9. Count Digits in a Number: 

    Start

    Input number

    Set count = 0

    While number > 0

    Increment count

    Remove last digit (num //= 10)

    Print count

    Stop

## 10. Exit the loop when i is 3:

    Start

    Initialize counter i = 1

    While i ≤ 10

    If i == 5

    Exit loop using break

    Else print i

    Increment i

    Stop

## 11 – Search an Element in List:

    Start

    Initialize list

    Input key value

    Set index i = 0

    While i < length of list

    If element equals key : print position and break

    Else increment i

    If loop finishes without break : print not found

    Stop

## 12 – Print Odd Numbers using Continue:

    Start

    Set i = 0

    While i < 10

    Increment i

    If i is even : continue

    Print i

    Stop

# Conclusion

This experiment demonstrated the practical use of while loops and loop control statements in Python. Through different programs, we learned how loops can be applied to:

Generate sequences

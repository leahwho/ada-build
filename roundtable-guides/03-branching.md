# Lesson 03: Branching

Today's round table will focus on reviewing the [lesson on branching](XXX).

## Relational Operators

1. Describe the difference between `=` and `==`.
1. Why is it important to remember that relational operators are evaluated after mathmatical operators in the precedence hierarchy?


## Conditionals
1. Why is the order of conditional tests in a chained conditional (`if/elif/elif...`) important? 
1. Let's consider the [Black Jack](https://colab.research.google.com/drive/1huE7PyavZSJIou4mh5G2e7yfG08Vb7da#scrollTo=1fttbcPz-XVv) example. Why is the second solution presented in Ada Build the better solution?
1. How are logic errors different from syntax errors?
1. Let's consider truth and falsy values. 
    * What is the output of the following blocks of code?
    * Let's review other ways to write code with the same output.
    
    ```python
    x = None

    if x:
        print("x is Truthy!")
    else:
        print("x is Falsy!")
    ```

    ```python
    x = "hello"

    if x:
        print("x is Truthy!")
    else:
        print("x is Falsy!")
    ```

## Logical Operators
1. Describe the difference between `or` and `and`. 
    * For the [coffee and sleep example](XXX) describe how it would be different if it were an `or` relationship.
1. Let's revisit the example above where `x = 'hello'`. 
    * How would the code change (and still remain logical) if we started with `if not x:`?

## Practice Problems
1. What question do you have about the practice problems?
1. Which problems were the most challenging or suprising?
1. Let's look at problem 3.4. 
    * How could it be refactored without a nested conditional?
    ```python
    if x >= y:
        if x > y:
            print("x is bigger")
        else:
            print("x = y")
    else:
        print("y is bigger")
    ```

## Project: Rock, Paper, Scissors
1. What questions are there about Rock, Paper, Scissors?
1. Let's look at a few different solutions.

### Project Extension Questions (Technical Interview Practice)
1. If you used a nested conditional, why did you choose that logic/syntax?
1. If you used a compound conditional, why did you choose that logic/syntax?
1. How would the program change if we added additional elements, such as lizard and spock as outlined by [these rules](https://roshambo.me/rules/).

## Extra Extra

1. What other questions do you have?

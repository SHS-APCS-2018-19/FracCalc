# Checkpoint 1

## Required Behavior

-   The program should read in fraction equations and print the results in a
    continuous loop until the user types "quit"

-   Input will be either mixed fractions, proper fractions, improper fractions
    or integers

-   Input will be separated by spaces – exactly one space between each fraction
    and operator.

-   The integer and fraction parts of a mixed fraction will be separated by an
    underscore.

-   Negatives are allowed – the negative sign should go immediately before the
    whole part of the number (with no space in between)

-   The operators will be +, -, \*, and /

-   The output needs to be in standard mixed fractions, properly reduced (i.e.
    1/2 instead of 2/4, 1_1/4 instead of 5/4)

## Sample Execution Log 

```
Welcome to the Fraction Calculator!
Enter an expression (or "quit"): 1/2 + 1/3
5/6
Enter an expression (or "quit"): 1_1/2 + 1/4
1_3/4
Enter an expression (or "quit"): 8/4 + 2
4
Enter an expression (or "quit"): -1 * -1/2
1/2
Enter an expression (or "quit"): -11/17 + -1/17
-12/17
Enter an expression (or "quit"): 1/3 * 3
1
Enter an expression (or "quit"): quit
Goodbye!
```

## Additional Comments

No numbers in the fraction will exceed the limits of a Java int (between -2,147,483,648 and 2,147,483,647) after they are multiplied – which means the input will be between -32,768 and 32767.

## Debug Output 

**Input:** 1/4 + 1_1/2

**Output:**

```
Val1 whole number: 0
Val1 numerator: 1
Val1 denominator: 4
Operator: +
Val2 whole number: 1
Val2 numerator: 1
```

**Input:** 8/4 * 2

**Output:**

```
Val1 whole number: 0
Val1 numerator: 8
Val1 denominator:	4
Operator:	*
Val2 whole number: 2
Val2 numerator:	None
Val2 denominator:	None
```

**Input:** -11/17 + -1/17

**Output:**

```
Val1 whole number: 0
Val1 numerator: -11
Val1 denominator:	17
Operator:	+
Val2 whole number: 0
Val2 numerator:	-1
Val2 denominator:	17
```




  

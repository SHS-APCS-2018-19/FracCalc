# FracCalc
Fraction calculator

Students will implement a basic calculator that handles fractions.

## Checkpoints

**Due: 11/20/18** 

[Checkpoint 1](checkpoint-1.md):Input loop that quits correctly and
    echoes the parts of the input. Your program **must** store the fractions
    internally as something other than a string before echoing the fractions.

**Example*:**

```
Input: **1/4 + 1_1/2**  
Fraction 1: 1/4  
Operation: +  
Fraction 2: 1_1/2
Input: **quit**  
Goodbye!
```

**Due 11/28/18(p2), 11/29/18(p1)**

Checkpoint 2: 

See details in the
    checklist for checkpoint \#2. Parsing the fractions: handle mixed and
    improper fractions and operations. Complete test case list in comments – 10
    to 15 equations that test your code paths that can be copied and pasted.

** Due 12/5/18(p2), 12/6/18(p1)**
Checkpoint 3: See details in the checklist
    for checkpoint \#3. Do one operation: fully functional +, -, \*, or /
    including improper, mixed fractions, and reduction of fractions

## Grading Scheme (100 points total)

-   Parses input correctly: 10 points
-   Addition: 5 points

-   Subtraction: 5 points

-   Multiplication: 5 points

-   Division: 5 points

-   Result reduction: 10 points

-   Mixed fraction input: 5 points

-   Mixed fraction output: 5 points

-   Handles negatives: 10 points

-   Checkpoints met: 10 points each

-   Comments/style: 10 points

## Extra Credit:

2.5 points for calculators that can handle more than one operation (e.g. 1 + 1 + 1 - 1/2)
2.5 points for correctly mainlining the order of operations with more than two inputs (e.g. 1 - 2 * 4 returning -7 instead of -4)
2.5 points for handling bad input gracefully (e.g. 1 + + 1/2 does not cause the program to crash)
2.5 points for an infinite precision calculator.  This means your calculator can handle very large numbers and still produce the right results. You will need to use the Java BigInteger class. This involves a lot of extra work, so consider it carefully or do it only after you have finished the required parts.

Additional extra credit for other advanced behavior based on complexity and completeness. See Mr Srock with your specification prior to implementation of extra behavior.

Maximum extra credit available 10 points.

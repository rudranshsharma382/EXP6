# Experiment 6: Study of Conditional Statements in Python
 Student Information

Name: Rudransh Sharma

PRN: 25070123096



Aim:
To study and implement conditional statements in Python using if, elif, and else constructs to solve decision-making problems.

Theory:
Conditional statements in Python are used to perform decision-making operations. They allow a program to execute certain blocks of code based on whether a condition is True or False.

Types of Conditional Statements:
if statement – Executes a block of code if the condition is true.

if-else statement – Executes one block if condition is true, otherwise another block.

if-elif-else ladder – Used when multiple conditions need to be checked.

Nested if statements – One if statement inside another.

Syntax:
if (condition):

  statements

elif (condition):

  statements

else:

  statements
Conditional statements are widely used in:
Decision making

Comparisons

Logical operations

Real-life problem solving (grading, salary calculation, tax calculation, etc.)

Algorithms
1. Check Whether a Number is Positive, Negative or Zero
Start

Input a number n

If n > 0, print "Positive"

Else if n < 0, print "Negative"

Else print "Zero"

Stop
2. Check Whether a Number is Even or Odd
Start

Input number n

If n % 2 == 0, print "Even"

Else print "Odd"

Stop
3. Find Largest of Three Numbers
Start

Input three numbers n1, n2, n3

If n1 > n2 and n1 > n3, print n1 is largest

Else if n2 > n1 and n2 > n3, print n2 is largest

Else print n3 is largest

Stop
4. Calculate Grade for One Subject
Start

Input marks

If marks ≥ 90 → Grade A

Else if marks ≥ 75 → Grade B

Else if marks ≥ 60 → Grade C

Else if marks ≥ 40 → Grade D

Else → Grade F

Stop
5. Calculate Average of 5 Subjects and Grade
Start

Input marks of 5 subjects

Calculate average = sum of marks / 5

If average ≥ 90 → Grade A

Else if average ≥ 75 → Grade B

Else if average ≥ 60 → Grade C

Else if average ≥ 40 → Grade D

Else → Grade F

Display average and grade

Stop
6. Check Whether a Year is a Leap Year
Start

Input year

If year divisible by 400 → Leap year

Else if year divisible by 4 AND not divisible by 100 → Leap year

Else → Not a leap year

Stop
7. Increment a Given Date by One Day
Start

Input date in format (dd/mm/yyyy)

Extract day, month, year

Determine maximum days in month:

31 days → Jan, Mar, May, Jul, Aug, Oct, Dec

30 days → Apr, Jun, Sep, Nov

February → 28 or 29 (if leap year)

If date invalid → Print "Invalid date"

Else if day equals max days:

If month = 12 → Set day=1, month=1, year+1

Else → Set day=1, month+1

Else → Increment day by 1

Print next date

Stop
8. Check Whether Character is Vowel or Consonant
Start

Input character ch

If ch is in (a, e, i, o, u, A, E, I, O, U) → Print "Vowel"

Else → Print "Consonant"

Stop
9. Calculate Gross Salary
Start

Input basic salary

If basic ≤ 10000:

HRA = 20%

DA = 80%

Else if basic ≤ 20000:

HRA = 25%

DA = 90%

Else:

HRA = 30%

DA = 95%

Gross Salary = Basic + HRA + DA

Print gross salary

Stop
10. Calculate Income Tax Based on Annual Income
Start

Input annual income

If income ≤ 2,50,000 → Tax = 0

Else if income ≤ 5,00,000 → Tax = 5% of (income - 2,50,000)

Else if income ≤ 10,00,000 → Tax = (5% of 2,50,000) + 20% of (income - 5,00,000)

Else → Tax = (5% of 2,50,000) + (20% of 5,00,000) + 30% of (income - 10,00,000)

Print tax

Stop
Conclusion:
In this experiment, we successfully studied and implemented various conditional statements in Python. We learned how decision-making structures like if, if-else, and if-elif-else are used to solve real-world problems such as grading systems, salary calculations, tax computation, leap year detection, and date increment operations.

This experiment helped in understanding:

Logical comparisons

Relational and arithmetic operators

Structured programming

Real-life applications of conditional statements

Hence, the objective of studying conditional statements in Python was successfully achieved


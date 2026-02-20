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

ALGORITHMS
1. Check Whether a Number is Positive, Negative or Zero
Start

1.Input a number n

2.If n > 0, print "Positive"

3.Else if n < 0, print "Negative"

4.Else print "Zero"

5.Stop

2. Check Whether a Number is Even or Odd
Start

1.Input number n

2.If n % 2 == 0, print "Even"

3.Else print "Odd"

4.Stop

3. Find Largest of Three Numbers

1.Start

2.Input three numbers n1, n2, n3

3.If n1 > n2 and n1 > n3, print n1 is largest

4.Else if n2 > n1 and n2 > n3, print n2 is largest

5.Else print n3 is largest

6.Stop

4. Calculate Grade for One Subject

1.Start

2.Input marks

3.If marks ≥ 90 → Grade A

4.Else if marks ≥ 75 → Grade B

5.Else if marks ≥ 60 → Grade C

6.Else if marks ≥ 40 → Grade D

7.Else → Grade F

8.Stop

5. Calculate Average of 5 Subjects and Grade
   
Start

1.Input marks of 5 subjects

2.Calculate average = sum of marks / 5

3.If average ≥ 90 → Grade A

4.Else if average ≥ 75 → Grade B

5.Else if average ≥ 60 → Grade C

6.Else if average ≥ 40 → Grade D

7.Else → Grade F

8.Display average and grade

9.Stop

6. Check Whether a Year is a Leap Year
   
1.Start

2.Input year

3.If year divisible by 400 → Leap year

4.Else if year divisible by 4 AND not divisible by 100 → Leap year

5.Else → Not a leap year

6.Stop

7. Increment a Given Date by One Day

1.Start

2.Input date in format (dd/mm/yyyy)

3.Extract day, month, year

4.Determine maximum days in month:

5.31 days → Jan, Mar, May, Jul, Aug, Oct, Dec

6.30 days → Apr, Jun, Sep, Nov

7.February → 28 or 29 (if leap year)

8.If date invalid → Print "Invalid date"

9.Else if day equals max days:

10.If month = 12 → Set day=1, month=1, year+1

11.Else → Set day=1, month+1

12.Else → Increment day by 1

13.Print next date

14.Stop

8. Check Whether Character is Vowel or Consonant

1.Start

2.Input character ch

3.If ch is in (a, e, i, o, u, A, E, I, O, U) → Print "Vowel"

4.Else → Print "Consonant"

5.Stop

9. Calculate Gross Salary
1.Start

2.Input basic salary

3.If basic ≤ 10000:

4.HRA = 20%

5.DA = 80%

6.Else if basic ≤ 20000:

7.HRA = 25%

8.DA = 90%

9.Else:

10.HRA = 30%

11.DA = 95%

12.Gross Salary = Basic + HRA + DA

13.Print gross salary

14.Stop

10. Calculate Income Tax Based on Annual Income

1.Start

2.Input annual income

3.If income ≤ 2,50,000 → Tax = 0

4.Else if income ≤ 5,00,000 → Tax = 5% of (income - 2,50,000)

5.Else if income ≤ 10,00,000 → Tax = (5% of 2,50,000) + 20% of (income - 5,00,000)

6.Else → Tax = (5% of 2,50,000) + (20% of 5,00,000) + 30% of (income - 10,00,000)

7.Print tax

8.Stop

Conclusion:
In this experiment, we successfully studied and implemented various conditional statements in Python. We learned how decision-making structures like if, if-else, and if-elif-else are used to solve real-world problems such as grading systems, salary calculations, tax computation, leap year detection, and date increment operations.

This experiment helped in understanding:

Logical comparisons

Relational and arithmetic operators

Structured programming

Real-life applications of conditional statements

Hence, the objective of studying conditional statements in Python was successfully achieved


## Experiment 6: Study of Conditional Statements in Python

**Aim:** To understand and implement various decision-making structures in Python, such as `if`, `elif`, and `else`, to solve logical and mathematical problems.

---

### Theory

Conditional statements allow a program to execute specific blocks of code based on whether a condition evaluates to **True** or **False**. In Python, the `if` statement evaluates a condition; if it is false, the `elif` (else if) provides additional conditions to check, and finally, the `else` block serves as a "catch-all" for any cases not caught by the previous conditions. These structures are essential for controlling the flow of a program, allowing it to react differently to different inputs.

---

### Algorithms for Each Program

#### 1a. Positive or Negative Check

1. Start.
2. Input an integer `num`.
3. If `num` is greater than or equal to 0, print "positive".
4. Otherwise, print "negative".
5. Stop.

#### 1b. Positive, Negative, or Zero Check

1. Start.
2. Input an integer `num`.
3. If `num > 0`, print "positive".
4. Else if `num < 0`, print "negative".
5. Otherwise, print "The number is zero".
6. Stop.

#### 2. Even or Odd Check

1. Start.
2. Input an integer `num`.
3. Calculate the remainder of `num / 2`.
4. If the remainder is 0, print "even".
5. Otherwise, print "odd".
6. Stop.

#### 3. Find the Largest Number

1. Start.
2. Input three numbers: `a`, `b`, and `c`.
3. If `a` is greater than or equal to `b` and `c`, set `largest = a`.
4. Else if `b` is greater than or equal to `a` and `c`, set `largest = b`.
5. Otherwise, set `largest = c`.
6. Print the `largest` value.
7. Stop.

#### 4. Grade Finder

1. Start.
2. Input the `subject` name and `score`.
3. If `score >= 90`, grade is 'A'.
4. Else if `score >= 80`, grade is 'B'.
5. Else if `score >= 70`, grade is 'C'.
6. Else if `score >= 60`, grade is 'D'.
7. Otherwise, grade is 'F'.
8. Print the subject and its assigned grade.
9. Stop.

#### 5. Leap Year Check

1. Start.
2. Input a `year`.
3. If the year is divisible by 400, OR (divisible by 4 AND not divisible by 100), it is a leap year.
4. Otherwise, it is not a leap year.
5. Stop.

#### 6. Increment a Date

1. Start.
2. Input `d`, `m`, and `y`.
3. Determine if `y` is a leap year to set `max_days` for February (28 or 29).
4. Set `max_days` for other months (30 for months 4, 6, 9, 11; otherwise 31).
5. Increment day `d` by 1.
6. If `d` exceeds `max_days`, set `d = 1` and increment month `m`.
7. If `m` exceeds 12, set `m = 1` and increment year `y`.
8. Print the new date.
9. Else show that the date is inavlid
10. Stop.

#### 7. Vowel or Consonant Check

1. Start.
2. Input a character `char`.
3. Convert `char` to uppercase and check if it exists in the string 'AEIOU'.
4. If yes, print "vowel".
5. Otherwise, print "consonant".
6. Stop.

#### 8. Gross Salary Calculation

1. Start.
2. Input `basic` salary.
3. If `basic <= 10000`, set `hra = 20%` and `da = 80%`.
4. Else if `basic <= 20000`, set `hra = 50%` and `da = 90%`.
5. Otherwise, set `hra = 30%` and `da = 95%`.
6. Calculate `gross = basic + hra + da`.
7. Print the gross salary.
8. Stop.

#### 9. Income Tax Calculation

1. Start.
2. Input annual `income`.
3. If `income <= 250000`, tax is 0.
4. Else if `income <= 500000`, tax is 5% of amount over 250,000.
5. Else if `income <= 1000000`, tax is 12,500 + 20% of amount over 500,000.
6. Otherwise, tax is 112,500 + 30% of amount over 1,000,000.
7. Print the total income tax.
8. Stop.

---

**Conclusion:** Through these experiments, the application of conditional logic was successfully demonstrated to handle varied scenarios ranging from basic mathematical checks to complex real-world calculations like date incrementation and taxation.


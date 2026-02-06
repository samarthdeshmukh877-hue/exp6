# Experiment 6: Implementation of Conditional Statements in Python

## Aim
This laboratory experiment demonstrates the practical application of **Control Flow Statements** in Python. The notebook contains a collection of programs that utilize conditional logic (`if`, `if-else`, `elif` ladders, and nested conditions) to solve mathematical problems and real-world scenarios, ranging from basic number properties to complex date validation.

## Project Contents & Logic Description

### 1. Number Property Checker
* **Objective:** To categorize a user-inputted number.
* **Logic:** Implements a three-way check using an `if-elif-else` structure to determine if the number is **Positive**, **Negative**, or **Zero**.

### 2. Parity Check (Even/Odd)
* **Objective:** To determine the parity of an integer.
* **Logic:** Uses the modulo operator (`%`). If `number % 2 == 0`, it is identified as **Even**; otherwise, it is **Odd**.

### 3. Maximum of Three Numbers
* **Objective:** To identify the largest value among three distinct inputs.
* **Logic:** Utilizes logical `and` operators to compare three variables (`a`, `b`, `c`) simultaneously to print the maximum value.

### 4. Student Grading System
* **Objective:** To assign alphabetic grades based on numerical marks.
* **Logic:** Maps numerical ranges to grades using an `if-elif` ladder:
    * **A:** 90+
    * **B:** 75 - 89
    * **C:** 60 - 74
    * **D:** 40 - 59
    * **Fail:** Below 40

### 5. Leap Year Validator
* **Objective:** To check if a given year is a leap year.
* **Logic:** Implements the Gregorian calendar rules:
    * The year must be divisible by 4 **AND** not divisible by 100, **OR**
    * The year must be divisible by 400.

### 6. Vowel/Consonant Detector
* **Objective:** To analyze a character input.
* **Logic:** Checks membership of the input character in the string `'aeiouAEIOU'` to classify it as a **Vowel** or **Consonant**.

### 7. Gross Salary Calculator
* **Objective:** To compute gross salary based on basic pay tiers.
* **Logic:** Calculates HRA (House Rent Allowance) and DA (Dearness Allowance) as percentages of the Basic Salary, which vary based on salary slabs (<=10k, <=20k, >20k).
    * *Formula:* `Gross = Basic + HRA + DA`

### 8. Income Tax Calculator
* **Objective:** To compute income tax based on progressive tax slabs.
* **Logic:** Applies a tiered tax calculation:
    * **0 - 2.5L:** Exempt
    * **2.5L - 5.0L:** 5%
    * **5.0L - 10.0L:** 20% (+ fixed base)
    * **> 10.0L:** 30% (+ fixed base)

### 9. Date Validator & Incrementer
* **Objective:** To validate a date input (dd/mm/yyyy) and determine the next calendar date.
* **Logic:**
    1.  **Parsing:** Splits input string into Day, Month, Year.
    2.  **Validation:** Ensures months are 1-12 and days match the specific month (including Leap Year checks for February).
    3.  **Incrementing:** Handles roll-over logic (e.g., if Jan 31st -> Feb 1st; if Dec 31st -> Jan 1st of next year).

##Conclusion
This experiment successfully demonstrates the capability of Python's conditional statements to handle decision-making processes, mathematical constraints, and data validation logic.

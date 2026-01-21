# Task 01: Test Cases for Simple Calculator Application

## Project Overview
This document outlines the comprehensive test cases designed to verify the functionality, reliability, and error handling of a Simple Calculator application. The goal is to ensure that all basic arithmetic operations work as expected while handling invalid inputs gracefully.

---

## Test Case Suite

| Test Case ID | Test Description | Preconditions | Test Steps | Expected Results |
| :--- | :--- | :--- | :--- | :--- |
| **TC-01** | Addition of positive integers | App is launched and screen is clear | 1. Enter "10"<br>2. Press "+"<br>3. Enter "5"<br>4. Press "=" | Result displays "15" |
| **TC-02** | Subtraction with negative results | App is launched | 1. Enter "5"<br>2. Press "-"<br>3. Enter "10"<br>4. Press "=" | Result displays "-5" |
| **TC-03** | Multiplication of decimal numbers | App is launched | 1. Enter "2.5"<br>2. Press "*"<br>3. Enter "2"<br>4. Press "=" | Result displays "5.0" |
| **TC-04** | Division by zero (Error Handling) | App is launched | 1. Enter "8"<br>2. Press "/"<br>3. Enter "0"<br>4. Press "=" | Result displays "Error: Cannot divide by zero" |
| **TC-05** | Operator Precedence (BODMAS) | App is launched | 1. Enter "2 + 3 * 4"<br>2. Press "=" | Result displays "14" (Multiplication performed before addition) |
| **TC-06** | Invalid non-numeric input | Input field is focused | 1. Attempt to type "ABC" into the calculator | Input is blocked or "Invalid Input" error is shown |

---

## Tools Used
* **Documentation:** Markdown
* **Version Control:** GitHub
* **Testing Type:** Manual Black Box Testing

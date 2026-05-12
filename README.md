## GPA & CGPA Calculator (C++)

A simple, interactive command-line tool written in C++ to calculate the Grade Point Average (GPA) for individual semesters and the Cumulative Grade Point Average (CGPA) across multiple semesters.
### 🚀 Features
> Semester-wise Calculation: Computes GPA based on course credits and letter grades (A, B, C, D, F).
> Case Insensitivity: Accepts both uppercase and lowercase grade inputs (e.g., 'a' or 'A').
> Weighted GPA: Multiplies credits by grade points to ensure accurate academic reporting.
> CGPA Summary: Provides an overall average of all semesters entered.

### 🛠️ Logic & Structure
1. cal() Function

> This function handles the core logic for a single semester:
    - Asks for the number of courses.
    - For each course, it takes the credits and the letter grade.
    - Grade Mapping:'A' = 4.0 |'B' = 3.0|'C'= 2.0 |'D' = 1.0| 'F' = 0.0

2. cgpa(int s) Function

> Calculates the final cumulative average by dividing the total_gpa (the sum of all semester GPAs) by the total number of semesters (s).

3. main() Function

> The entry point of the program. It loops through the total number of semesters defined by the user, calls the cal() function, and displays the result for each semester before providing the final CGPA.
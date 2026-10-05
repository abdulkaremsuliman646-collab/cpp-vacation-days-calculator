# C++ Vacation Days Calculator

A C++ console application that calculates the actual number of vacation days between two dates while excluding weekends.

This project was built as part of my journey to strengthen my C++ programming fundamentals, problem-solving skills, and understanding of reusable date-based functions.

## Features

- Read vacation start and end dates.
- Determine the day of the week for each date.
- Compare two dates.
- Increase a date by one day.
- Handle month and year transitions.
- Handle leap years.
- Identify weekends.
- Identify business days.
- Calculate actual vacation days while excluding weekends.
- Demonstrate Function Overloading.
- Use structures to organize date information.

## Concepts Practiced

- C++ Structures (`struct`)
- Functions
- Function Overloading
- Conditional Statements
- Loops
- Arrays
- Date Algorithms
- Leap Year Logic
- Boolean Logic
- Function Reusability
- Problem Solving

## Function Overloading

This project demonstrates Function Overloading using `DayOfWeekOrder`.

The program provides two functions with the same name but different parameters:

```cpp
short DayOfWeekOrder(short Day, short Month, short Year)
Vacation Starts:
Day: 23
Month: 9
Year: 2026

Vacation Ends:
Day: 30
Month: 9
Year: 2026
Vacation From: Wed, 23/9/2026
Vacation To: Wed, 30/9/2026

Actual Vacation Days: ...

# CalenderDisplay

This project is a simple Java program that takes a **month and a year** as input and prints the corresponding **calendar** for that month in a clean, formatted layout.
The program mimics the appearance of a traditional wall calendar, starting from Sunday and ending on Saturday. It correctly aligns the days according to the weekday on which the month begins and handles **leap years** for February.


## How It Works

- The user enters a **month and year** (e.g., `10 2005`).
- The program calculates the **day of the week** for the 1st of that month using the **Gregorian calendar algorithm**.
- It determines the number of days in the selected month, accounting for leap years.
- It then displays the calendar with correct indentation and spacing using formatted output.


## Key Concepts Used

- **Arrays** for storing month names and number of days.
- **Leap year logic** to correctly calculate days in February.
- **Gregorian algorithm** to determine the starting weekday.
- **Formatted output** using spacing (`%3d`) for alignment.


## Educational Purpose

This project is great for:

- Beginners learning Java
- Understanding how calendars work programmatically
- Practicing control structures, loops, conditionals, and formatting

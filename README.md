# Smart Student Performance Analyzer

## 1. Project Overview

Smart Student Performance Analyzer is a simple Python program for checking basic student performance.

The program takes the student's name, roll number, Maths marks, Python marks, English marks, attendance percentage, and completed assignments as input. It calculates the total marks and percentage, gives a grade, finds the performance category, and gives a recommendation based on the subject with the lowest marks.

## 2. Features

- Takes student name and roll number.
- Takes Maths, Python, and English marks.
- Calculates total marks and percentage.
- Assigns a grade based on percentage.
- Determines the performance category.
- Finds the subject with the lowest marks.
- Gives a recommendation for improvement.
- Shows a warning when attendance is below 75%.
- Shows a suggestion when fewer than 5 assignments are completed.
- Displays a final student performance report.

## 3. Technologies / Tools Used

- **Programming Language:** Python 3
- **Editor:** VS Code
- **Version Control:** Git and GitHub
- **Libraries:** No external libraries are required.

## 4. Steps to Install & Run the Project

### Step 1: Install Python

Install Python 3 on the computer.

### Step 2: Open the Project

Open the project folder in VS Code or a terminal.

### Step 3: Check the Files

Make sure the project contains:

```text
Smart_Student_Performance_Analyzer/
│
├── main.py
└── README.md
```

### Step 4: Run the Program

Open the terminal in the project folder and run:

```bash
python main.py
```

If `python` does not work, use:

```bash
python3 main.py
```

## 5. Instructions for Testing

The program can be tested by entering different values for marks, attendance, and assignments.

Test the following cases:

- Enter high marks and attendance and check the grade and performance category.
- Enter percentage between 60 and 69 and check that Grade C is displayed.
- Enter attendance below 75% and check that the attendance warning is displayed.
- Enter fewer than 5 assignments and check that the assignment suggestion is displayed.
- Give one subject the lowest marks and check that the program recommends focusing on that subject.

The final report should display:

- Student name
- Roll number
- Total marks
- Percentage
- Grade
- Attendance
- Assignments completed
- Performance category
- Recommendation

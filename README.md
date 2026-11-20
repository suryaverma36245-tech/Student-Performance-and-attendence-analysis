# Student-Performance-and-attendence-analysis
Student Performance and Attendance System
📌 Project Overview

The Student Performance and Attendance System is a Python-based project that allows users to view individual student academic performance and attendance details using a CSV dataset.

The program uses the Pandas library to read student records and retrieve information based on the student number entered by the user.

It calculates total marks, average marks, displays attendance percentage, and evaluates attendance status.

🎯 Objectives
Read student records from a CSV file.
Allow users to search for students using their student number.
Display individual subject marks.
Calculate total marks and average marks.
Display student attendance percentage.
Check attendance eligibility based on a 75% attendance threshold.
Display appropriate messages for valid and invalid student numbers.
🛠️ Technologies Used
Python – Programming language.
Pandas – Reading and accessing student records.
CSV – Storing student performance and attendance data.
📂 Dataset Information

The project uses the following dataset:

mark_sheet_clean_file1 (1).csv

Important Dataset Columns
Column Name	Description
Math_Score	Mathematics marks
English_Score	English marks
Science_Score	Science marks
Attendance	Student attendance percentage
⚙️ Project Features
1. Load Student Dataset

Uses Pandas to read student information from the CSV file.

2. Display Total Students

Displays the total number of student records available in the dataset.

3. Student Search

The user enters a student number between 1 and 1005.

The program retrieves the corresponding student record using Pandas iloc.

4. Calculate Academic Performance

The program calculates:

Total Marks: Sum of Mathematics, English, and Science marks.
Average Marks: Average marks obtained across the three subjects.
5. Attendance Analysis

Displays the student's attendance percentage.

Attendance is classified into two categories:

Good: Attendance is 75% or above.
Low: Attendance is below 75%.
6. Input Validation

Checks whether the entered student number is within the available dataset range.

Valid student number: Displays student details.
Invalid student number: Displays an error message.
▶️ How to Run the Project
Step 1: Install Python

Download Python from:

https://www.python.org/downloads/

Step 2: Install Pandas

Open the terminal or command prompt and run:

bash
pip install pandas

Step 3: Prepare the Dataset

Keep the CSV file in the same folder as your Python program.

Dataset filename:

mark_sheet_clean_file1 (1).csv

Step 4: Run the Python Program

Save the code as:

student_performance.py

Run the following command:

bash
python student_performance.py

Step 5: Enter Student Number

Enter a student number between 1 and 1005 when prompted.

The program will display the selected student's academic and attendance details.

📊 Sample Output
text
STUDENT PERFORMANCE AND ATTENDANCE SYSTEM

Total Students: 1005

Enter Student Number (1-1005): 1

--- Student Details ---
Math Marks: 85.0
English Marks: 78.0
Science Marks: 90.0

Total Marks: 253.0
Average Marks: 84.33
Attendance: 92.0 %

Attendance Status: Good


Note: Sample marks and attendance are illustrative. Actual output depends on the dataset.

📁 Project Structure
text
Student-Performance-and-Attendance-System/
│
├── mark_sheet_clean_file1 (1).csv
│
├── student_performance.py
│
└── README.md

🚀 Future Improvements
Search students using their names or student IDs.
Display student grades based on marks.
Generate individual student performance reports.
Identify students with low attendance.
Add a graphical user interface (GUI).
Create performance charts and dashboards.
Analyze the relationship between attendance and academic performance.
📝 Conclusion

The Student Performance and Attendance System demonstrates how Python and Pandas can be used to manage and analyze student academic records.

It provides a simple way to retrieve student information, calculate academic performance, and evaluate attendance status.

This project helps demonstrate basic concepts of Python programming, conditional statements, user input, CSV file handling, and data manipulation using Pandas.

Project Name: Student Performance and Attendance System

Domain: Python Programming / Data Analysis

Programming Language: Python

Library: Pandas

File Format: CSV
Author Arpit Verma

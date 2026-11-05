Student Management System Report
Introduction

The Student Management System is a simple Python-based application designed to manage student academic records. The program enables users to enter a student's name and marks in three subjects, calculate the average score, determine whether the student has passed or failed, and save the results to a text file for future reference.

Project Objectives
To learn how to collect user input in Python.
To perform mathematical calculations using variables.
To apply conditional statements for decision-making.
To store data permanently using file handling techniques.
To generate and display a student performance report.
System Description

The program starts by displaying a welcome message for the Student Management System. It then requests the user to enter the student's name and marks for three subjects:

Mathematics
Science
English

After receiving the input, the program calculates the student's average score using the following formula:

Python
average = (math + science + english) / 3

The program checks the average score and determines the student's result:

If the average is 50 or above, the student is marked as Pass.
If the average is below 50, the student is marked as Fail.

The student's name, average score, and result are saved in a text file named student's.txt. Finally, a report is displayed on the screen.

Inputs
Student Name
Math Mark
Science Mark
English Mark
Outputs
Average Score
Pass/Fail Result
Saved Student Record in a Text File

# student-analysis
This file, maincode.py, serves as the solution for the GSE301 Data Science: Python Fundamentals Project 1, titled Student Academic Performance Analysis System.  It is a comprehensive Python script that demonstrates the fundamental concepts of Python programming through the creation, processing, analysis, and management of student academic records.
Key Functions and Concepts Demonstrated:The script systematically addresses all core requirements of the project, including:Part 1: Data Collection and StorageVariable Declarations (Task 1.1): Defines fundamental Python data types, including string, int, float, boolean, list, and dictionary, for a single student profile.

Data Structures in Action (Task 1.2): Stores multiple student profiles using a List of Dictionaries and creates a Set for unique course codes and a Tuple for department information.

Part 2: Data Processing and LogicConditional Grading 
(Task 2.1): Implements a function using IF-ELIF-ELSE to assign a letter grade based on a score, and then uses MATCH CASE to provide specific textual feedback for that grade.

Type Conversion and Error Handling 
(Task 2.2): Uses a TRY EXCEPT block to safely handle user input (entered as strings), perform type conversion (int() and float()), and validate that the age and CGPA fall within specified ranges.

Part 3: Analysis and ReportingList Slicing (Task 3.1): Demonstrates list slicing for extracting the top 3 scores (after sorting), the last 5 scores (using negative indexing), and every other score (using step slicing).
Set Operations 
(Task 3.2): Performs essential set operations (intersection, union, difference) to analyze student groups (e.g., finding students who passed and achieved merit).
Part 4: Interactive Menu SystemConsole Menu and Control Flow (Task 4.1): Implements a repeating, interactive console menu using a while True loop and handles user navigation using MATCH CASE.
Eligibility Checker 
(Task 4.2): Defines a function that uses logical operators (and) to determine if a student meets complex graduation criteria (CGPA $\ge 2.5$, no failed courses, and active status).
Part 5: Advanced Challenges (Optional)Nested Data Processing 
(Task 5.1): Processes a nested dictionary to calculate the average score for each student and identifies students who meet a performance threshold (score above 70 in all courses).
Type Pattern Matching (Task 5.2): Utilizes the advanced pattern-matching capabilities of MATCH CASE to dynamically identify the data type of a given input (int, float, list, dict, str) and return a specialized summary.

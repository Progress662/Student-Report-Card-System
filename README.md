1. Overview :-
This project is a Console-Based Student Report Card System implemented in C++ using Object-Oriented Programming and core Data Structures and Algorithms (DSA) concepts.

2. Features
Add Student: Add a student's record including roll number, name, and marks for multiple subjects.

Remove Student: Remove a student by roll number.

Search Student: Search and display a student's details by roll number.

Update Student: Modify an existing student's name and marks.

Print All Students: Display a report of all students.

Sort by Average: Sorts and displays students in descending order of their average marks.

Grade Calculation: Grades are automatically assigned based on average marks.

3. Data Structures Used
Class (Student): Encapsulates each student's data.

Class (StudentDatabase): Manages a vector of Student objects and provides CRUD operations.

Vector: Used to dynamically store an array of students and marks.

Algorithm: The sort algorithm from STL is used for sorting students by average.

4. Object-Oriented Concepts
Encapsulation: Student data/bank is packaged inside classes.

Abstraction: Only relevant operations are exposed for use.

5. DSA Concepts Demonstrated
Linear Search: Used to find students by roll number.

Dynamic Arrays (Vectors): For student and marks storage.

Sorting (STL sort): For ordering students by performance.

6. How to Compile and Run
Save the code to a file, e.g., student_report_card.cpp.

Compile:
g++ student_report_card.cpp -o reportcard

Run:
./reportcard

7. Flow
The main menu loops, offering the user to perform one operation at a time.

Input is collected for each operation (student details, etc.).

Results and status messages are printed accordingly.

8. Grading Criteria
Average	Grade
>= 90	A
>= 80 and <90	B
>= 70 and <80	C
>= 60 and <70	D
< 60	F
9. Extensions or Further Improvements
Persistent file-based storage.

Exception handling.

Authentication and authorization.

Gui and Front End

Unit Testing

GUI frontend.

Unit testing.

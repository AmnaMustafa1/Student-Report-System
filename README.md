# Student-Report-System
This project is a simple C++ program designed to manage student reports using functions and structures. It allows users to add, display, and calculate student details including their total marks.

## Features
- Add a student's details (Name, Roll Number, Marks for 3 subjects).
- Display a student's details, including their total marks.
- Calculate the total marks for a student.

## Structure
The program uses a `Student` structure to store:
- Name (e.g., "Ali Khan")
- Roll Number (e.g., 101)
- Marks (array to store marks for 3 subjects)

## Functions
### 1. `addStudent`
- Prompts the user to input the student's name, roll number, and marks for 3 subjects.
- Stores the details in the `Student` structure.

### 2. `displayStudent`
- Displays the student's name, roll number, marks, and the total marks.

### 3. `calculateTotalMarks`
- Sums up the marks stored in the array and returns the total.

## How to Run
1. Clone the repository or copy the `student_report_system.cpp` file.
2. Compile the code using a C++ compiler. For example:
   ```bash
   g++ student_report_system.cpp -o student_report_system
   ```
3. Run the compiled program:
   ```bash
   ./student_report_system
   ```
4. Follow the prompts to add and display student details.

## Sample Output
```
Enter Name: Ali Khan
Enter Roll Number: 101
Enter Marks for 3 subjects: 85 90 78
Student details added successfully!

Student Details:
Name: Ali Khan
Roll Number: 101
Marks: 85 90 78
Total Marks: 253
```

## Requirements
- A C++ compiler (e.g., Dev C++).
- Basic knowledge of C++ programming.

## Contributing
Feel free to fork this repository and make your improvements. Pull requests are welcome!




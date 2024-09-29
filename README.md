# Student Report Management System

This C++ project provides a command-line interface for managing student records, including creating, viewing, searching, modifying, and deleting student information and their academic performance.

## Features

- **Create Student Records:** Add new students with details like roll number, name, and marks in various subjects.
- **Search Student Records:** Find specific student records using their roll number.
- **Display All Records:** View a list of all stored student records.
- **Delete Student Records:** Remove existing student records based on roll number.
- **Modify Student Records:** Update information for existing students.
- **Automatic Grade Calculation:** Calculates and stores student grades based on their average marks.
- **Persistent Storage:** Utilizes binary file storage to save and retrieve student data.

## How to Use

1. **Compile the Code:** 
   - Make sure you have a C++ compiler installed (e.g., g++).
   - Compile the code using a command like: `g++ main.cpp -o student_report` (assuming your main file is named `main.cpp`)

2. **Run the Program:**
   - Execute the compiled program: `./student_report`

3. **Follow the Menu:**
   - The program will display a menu with options to create, search, display, delete, or modify student records.
   - Choose options by entering the corresponding number and follow the on-screen prompts.

## Code Structure

- **`student` Class:**
    - Stores student data (roll number, name, marks, average, grade).
    - Provides methods for data input, output, calculation, and retrieval.

- **Functions:**
    - `create_student()`: Creates and saves a new student record.
    - `display_sp(int)`: Displays a specific student record based on roll number.
    - `display_all()`: Displays all student records.
    - `delete_student(int)`: Deletes a student record.
    - `change_student(int)`: Modifies an existing student record.

- **`main()` Function:**
    - Presents the main menu and handles user interactions.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License

This project is open-source and available under a permissive, copyright-free approach. You are free to use and modify the code as needed.

## Disclaimer

By using this project, you acknowledge that it is provided as-is without warranty.

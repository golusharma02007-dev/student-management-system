Student Management System (C++)
A robust, console-based application designed to streamline the management of student records. This project provides a digital alternative to manual record-keeping, allowing for efficient data entry, retrieval, and modification.

🚀 Key Features
Batch Data Entry: Input details for multiple students in a single session.

Comprehensive View: Display all saved records in a structured list.

Targeted Search: Instantly find a student's profile using their unique Roll Number.

Record Modification: Update existing student information without deleting the entire entry.

Flexible Deletion: Options to remove a specific student record or wipe the entire database.

🛠️ Technical Implementation & Concepts
The project demonstrates the practical use of several core C++ programming concepts:

Parallel Arrays: Utilizes multiple string arrays (arr1 to arr5) to store different data attributes (Name, Roll No, Course, etc.) in parallel based on a shared index.

Modular Programming (Functions): The code is organized into distinct functions like enter(), show(), search(), and update(), ensuring high readability and easy debugging.

Control Flow Logic: - Infinite While Loop: Keeps the application active for multiple operations until the user chooses to exit.

Switch-Case: Provides an efficient menu-driven interface for user interaction.

Global State Management: Employs a global total variable to track the number of active records across various scopes.

Memory Management & Shifting: The deletion module implements a shifting algorithm to fill the gap left by a deleted record, maintaining the integrity of the array sequence.

Linear Search Algorithm: Implements a search loop to compare user input against stored Roll Numbers to locate specific indices.

📂 Project Architecture
enter(): Handles user input and manages data appending logic.

show(): Iterates through arrays to display stored data.

search(): Uses conditional logic to filter and display a specific record.

update(): Combines search logic with input streams to overwrite existing data.

deleterecord(): Manages record removal and reorganizes array indices to prevent data fragmentation.

💻 How to Execute
Compile: Copy the source code into any C++ IDE (Dev-C++, Visual Studio Code, or Code::Blocks).

Run: Execute the compiled file.

Interact: Use the numeric keypad to navigate the menu and follow the on-screen prompts to manage your data.

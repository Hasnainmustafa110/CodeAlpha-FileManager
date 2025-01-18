# CodeAlpha-FileManager
Name = Hasnain Mustafa Company = CodeAlpha 𝗦𝘁𝘂𝗱𝗲𝗻𝘁 𝗜𝗗: CA/JA1/9530 𝗗𝗼𝗺𝗮𝗶𝗻: C++ Programming 𝗗𝘂𝗿𝗮𝘁𝗶𝗼𝗻: 15th January 2025 to 15th
**Overview of the File Manager Project**
This project is a simple command-line file management tool implemented in C++. It enables users to perform various file and folder operations through an interactive menu-driven interface. It leverages standard C++ libraries like <fstream> for file operations and <filesystem> for file and directory management, offering a practical application of object-oriented programming (OOP) principles.

Features of the Project
**File Management**

Create a File: Users can create a new file by providing its name (with an extension).
Write to a File: Users can write multiple lines of text into a file until they type END, end, or End.
Read a File: Reads and displays the contents of a specified file.
Copy a File: Copies data from a source file to a destination file.
Move a File: Moves data from a source file to a destination file and deletes the source file.
Delete a File: Removes a specified file from the filesystem.
Directory Management

Create a Directory: Creates a new directory.
Delete a Directory: Deletes a specified directory.
Menu-Driven Interface

An interactive menu allows users to choose their desired operation.
The application continues to run until the user explicitly exits.
Classes and Methods
1. Class: file
This class encapsulates all the file and directory operations as member functions.
Methods:
create(string File_name): Creates a file.
write(string File_name): Allows the user to write to a file.
read(string File_name): Reads and displays file contents.
copy(string File_name, string fn): Copies data from one file to another.
move(string File_name, string fn): Moves data between files.
remove(string File_name): Deletes a file.
folder_creat(string File_name): Creates a directory.
folder_del(string Folder_name): Deletes a directory.
2. main Function
Provides a user-friendly menu interface for invoking file operations.
Uses a while loop to keep the program running until the user chooses to exit.
Implements a switch-case structure for user input.
Libraries Used
<iostream>: For input and output operations.
<fstream>: For file handling (reading and writing).
<string>: To handle string manipulations.
<filesystem>: To perform file and directory operations like creation, deletion, and movement.
Key Concepts Demonstrated
Object-Oriented Programming (OOP):

Encapsulation of functionality within a class.
Clear separation of concerns using member functions.
File Handling:

Reading, writing, copying, and moving files using <fstream>.
Directory Management:

Managing directories with <filesystem> for cross-platform compatibility.
Interactive User Interface:

Menu-driven approach with real-time user input for an engaging experience.

📁 File Number Sorter & Search (Java)
A simple, console-based Java application developed as part of an initial professional internship. This program demonstrates core programming concepts including file I/O, array manipulation, sorting algorithms, and basic search functionality.

🎯 Project Overview
This utility performs the following operations in sequence:

Generates a text file (numeros.txt) with 5,000 random integers.

Reads and displays the generated numbers from the file.

Sorts the numbers using Java's built-in Arrays.sort() and saves them to a new file (numerosOrdenados.txt).

Displays the sorted numbers.

Searches for a user-specified number within the sorted list and reports its position.

🛠️ Technical Implementation
Core Class: Metodos.java
The program is contained within a single class Metodos with a main method serving as the entry point and a suite of static methods for each operation.

Key Methods:

generarArchivo(): Creates the initial file with random integers (range: 1 to 10,000).

mostrarArchivo(): Reads and prints the contents of numeros.txt.

ordenar(): Loads the numbers into an array, sorts them, and writes the sorted list to numerosOrdenados.txt.

mostrarNumerosOrdenados(): Reads and prints the sorted numbers.

buscar(int num): Performs a linear search on the sorted array to find a given number and outputs its position (1-based index).

Constants & File Handling
public static int max = 5000: Defines the number of integers to generate and process.

Uses java.util.Scanner for file reading and java.io.FileWriter for file writing, with basic try-catch exception handling.

📁 Generated Files
numeros.txt: Contains the initial 5,000 randomly generated integers, separated by tabs.

numerosOrdenados.txt: Contains the same 5,000 integers sorted in ascending order, separated by spaces.

🚀 How to Run
Ensure you have Java installed (JDK 8 or higher recommended).

Compile the Java file:

bash
javac Metodos.java
Run the compiled class:

bash
java Metodos
Follow the console menu to execute each step in sequence.

🧠 Learning Objectives & Skills Demonstrated
This project served as practical application for foundational software engineering concepts, including:

Control Structures: Loops and conditional logic.

Data Structures: Array creation and manipulation.

Algorithms: Implementation of sorting (via library) and searching.

File I/O Operations: Reading from and writing to text files.

Error Handling: Basic implementation using try-catch blocks.

Code Modularity: Organizing functionality into distinct, reusable methods.

🔍 Future Improvements / Learning Paths
Potential enhancements for further development:

Implement custom sorting algorithms (e.g., QuickSort, MergeSort) for educational comparison.

Add a binary search algorithm to improve search efficiency on the sorted data.

Allow user configuration (e.g., number of integers to generate, file names).

Implement a more robust and user-friendly menu system.

Add input validation and more descriptive error messages.

Separate concerns by creating dedicated classes for file operations, sorting logic, and the user interface.

This project was developed as an introductory exercise to solidify understanding of Java syntax and core programming principles in a professional training context.

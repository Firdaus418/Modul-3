Project Overview

The DocumentationPractice project is a small Java application designed to demonstrate array manipulation and partial sorting using the built-in Arrays utility class. This project serves as an educational tool to help developers understand:

Java array handling

Partial array sorting with Arrays.sort()

How to visualize array changes with Arrays.toString()

Features

Sort a specific portion of an array without affecting the entire array.

Display the original and modified array to observe the effect of partial sorting.

Simple, clean, and easy-to-understand Java code for learning purposes.

Usage Guide Prerequisites

Java Development Kit (JDK) 8 or higher installed on your system.

Basic understanding of Java arrays and loops (helpful but not mandatory).

Running the Project

Clone or download the project to your local machine.

Open a terminal or command prompt and navigate to the project folder.

Compile the Java program:

javac Main.java

Run the compiled program:

java Main

Observe the output:

Modified arr[] : [13, 6, 7, 45, 21, 9, 2, 100]

Explanation

The array {13, 7, 6, 45, 21, 9, 2, 100} is partially sorted between index 1 (inclusive) and index 5 (exclusive).

Only the portion [7, 6, 45, 21] is sorted in ascending order.

The remaining elements of the array stay unchanged.

Customization

You can modify the array and the sort range by editing:

Arrays.sort(arr, startIndex, endIndex);

startIndex – the starting index of the range (inclusive).

endIndex – the ending index of the range (exclusive).

# Collections_Sorting-Employees
# What I Built
I developed a Java program that manages a list of employees and demonstrates how to sort them using the Java Collections framework. The program defines an `Employee` class with attributes like name, age, and salary, and sorts a list of these employees by salary (in descending order) and by name (in ascending order).

# Why I Built It
The purpose of this project is to learn and demonstrate how to work with Java Collections, especially `ArrayList`, and how to implement custom sorting using the `Comparator` interface. Sorting data is a common task in software development, and understanding how to use comparators effectively is an important skill for organizing and manipulating data collections.

# How It Works
- The `Employee` class contains fields for employee details and a `toString()` method for easy display.
- A list of multiple employees is created and stored in an `ArrayList`.
- The list is sorted twice:
  1. By salary in descending order using a custom comparator.
  2. By name in ascending alphabetical order, ignoring case.
- The sorted lists are then printed to the console to show the results.

This approach uses Java’s `Collections.sort()` method combined with `Comparator` to control the sorting behavior flexibly.

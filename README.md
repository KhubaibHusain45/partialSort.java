# Partial Sort - Java

This Java program demonstrates how to partially sort an array based on a specific condition. In this case, it sorts only the elements of the `prices` array that are **less than 100** in ascending order, while keeping the rest of the elements in their original positions.

## 🔍 Problem Statement

Given an array of integers (e.g., product prices), sort only the elements that satisfy a specific condition (price < 100), without altering the relative position of the remaining elements.

### Input:
🧠 Logic
Traverse the array and extract all values < 100 into a list.

Sort that list using Collections.sort().

Replace only the values < 100 in the original array with the sorted values, maintaining their original positions.

Print the final array.

🛠 Technologies Used
Java

ArrayList

Collections Framework

🚀 How to Run

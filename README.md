# Day44-50-days-coding-challenge

## 🔹 Problem 1: Convert Sorted Linked List to Height-Balanced BST

### ✅ Problem Statement:
Given the head of a singly linked list where elements are sorted in ascending order, convert it to a height-balanced binary search tree (BST).

### 💡 Approach:
- Use the slow and fast pointer technique to find the middle of the linked list.
- The middle element becomes the root of the BST.
- Recursively apply the same logic to the left half and right half of the list to build subtrees.

### 🧪 Example:
Input: [-10, -3, 0, 5, 9]  
Output: [0, -3, 9, -10, null, 5]

### 🧠 Key Concepts:
- Linked List Traversal
- Recursion
- Tree Construction
- Divide and Conquer

---

## 🔹 Problem 2: Maximum Number of Vowels in a Substring of Given Length

### ✅ Problem Statement:
Given a string `s` and an integer `k`, return the maximum number of vowel letters in any substring of `s` with length `k`.

### 💡 Approach:
- Use a sliding window of size `k`.
- Count the number of vowels in the window.
- Slide the window across the string and update the maximum count dynamically.

### 🧪 Example:
Input: s = "abciiidef", k = 3  
Output: 3  
Explanation: The substring `"iii"` contains 3 vowels.

### 🧠 Key Concepts:
- Sliding Window
- String Traversal
- Vowel Identification


## 📌 Note:
This repository is a part of the **#DrGViswanathanChallenge** - Day 44 of the 50 Days of Coding Challenge. Each day focuses on solving one or more DSA problems with clean, commented code and explanations.

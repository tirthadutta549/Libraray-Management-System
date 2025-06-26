# 📚 Simple Library Management System in C

## 📌 Overview

This project is a **console-based Library Management System** implemented in the C programming language. It provides basic functionality for managing a collection of books including:

- Adding books
- Borrowing books
- Returning books
- Displaying inventory

This system is ideal for educational purposes, specifically for students learning structured programming in C.

---

## 🧱 Data Structure

### `struct Book`
```c
typedef struct {
    int bookId;
    char title[50];
    char author[50];
    int isAvailable;  // 1 if available, 0 if borrowed
} Book;

# KYAU Library Management System

A simple C++ console-based library management system developed for KYAU by **Team CodeRaiders**.

## Overview

This project provides a menu-driven interface to manage basic library tasks:
- Register members
- Add books (admin only)
- View all books
- View all registered members (admin only)
- Display team/about information

All records are persisted in plain text files for simplicity.

## Features

- **Admin login** with password protection
- **Add new books** with input validation
- **Member registration** with input validation
- **Book listing** from stored records
- **Member listing** from stored records
- **Persistent storage** using:
  - `books.txt`
  - `members.txt`

## Project Structure

```text
KYAU-Library-Management-System/
├── main.cpp
├── README.md
├── books.txt      (auto-created at runtime if missing)
└── members.txt    (auto-created at runtime if missing)
```

## Requirements

- C++ compiler with C++11 support or newer (e.g., `g++`)

## Build and Run

From the project root:

```bash
g++ -std=c++11 -o library_app main.cpp
./library_app
```

## Usage

After running the app, use the main menu:

1. **Login as Admin**
   - Default password: `kyau25`
   - Access to:
     - Add a new book
     - View all books
     - View all members
2. **Be a Member**
   - Register with name and ID
3. **About Us**
   - View team details
4. **Exit**

## Notes

- This is an educational/demo project.
- File paths are relative to the runtime directory.
- Admin password is hardcoded in source code and should be secured for production use.

## Team

Developed by **Team CodeRaiders (KYAU)**:
- Rahat
- Rafi
- Anu
- Sojib
- Shila

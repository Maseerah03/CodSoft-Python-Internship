# To-Do List Application (Console-Based)

## Overview

This project is a command-line based To-Do List application developed in Python. It allows users to manage their daily tasks effectively by providing functionality to **add**, **view**, **update**, **delete**, and **save** tasks persistently to a local file.

## Features

- View all saved tasks
- Add new tasks
- Update existing tasks by index
- Delete tasks by index
- Save tasks to a file for future use

## How It Works

Tasks are stored in a local text file named `todo_list.txt`. When the program starts, it loads all existing tasks from the file (if present). Users interact with a menu-driven interface to manage tasks, and changes can be saved back to the file before exiting.

## File Structure

- `todo_list.txt` – Stores the task list persistently
- `todo_app.py` – Main Python script containing the task management logic

## Technologies Used

- Python 3.x
- Standard Python libraries:
  - `os` (for file existence checking)

## How to Run

1. Make sure you have Python 3 installed.
2. Save the script as `todo_app.py`.
3. Open a terminal and run:

   ```bash
   python todo_app.py

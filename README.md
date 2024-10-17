# Task_Management_System
This repository contains a Task Management System built with Python and SQLite, featuring a GUI developed with Tkinter. It allows users to manage tasks, assignments, habits, and activities, offering tools for course management, to-do lists, habit tracking, and reminders. Designed to boost productivity and keep users organized.
## Description
The **Task Management System** is a Python-based application that helps users manage tasks, assignments, habits, and personal activities in a structured and organized way. It features a graphical user interface (GUI) developed using Tkinter and stores data using SQLite, making it easy to track and retrieve information at any time.

### Key Features:
- **Course Management:** Add courses with schedules for easy tracking.
- **Assignment Tracking:** Manage assignments with due dates and grading criteria.
- **To-Do List:** Organize tasks with categories, priorities, and deadlines.
- **Habit Tracking:** Monitor habits with start dates and frequencies to help users stay consistent.
- **Personal Activities:** Keep track of events and activities with custom dates.
- **Reminders:** View upcoming assignments and tasks to ensure deadlines are met.

## Technologies Used:
- **Python 3.12.4
- **Tkinter:** For building the GUI.
- **SQLite:** As the database to store user data.
- **Datetime Module:** For handling dates and times effectively.

## Installation Instructions:
To run this project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://JingwenDu-creat/Task_Management_System.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd Task_Management_System
    ```

3. **Install Python dependencies:**
    Ensure Python 3.x is installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

4. **Run the application:**
    Open a terminal in the project folder and run the following command:
    ```bash
    python task_management_system.py
    ```

## How to Use the Application:
1. **Adding Tasks:** Users can add new tasks, courses, habits, and activities using the application’s intuitive GUI.
2. **Viewing Tasks and Reminders:** The system offers easy access to your to-do list and upcoming assignments or events via the "View To-Do List" and "View Assignments & Reminders" buttons.
3. **Database:** Data is stored in an SQLite database (`taskmaster.db`), which is automatically created when the application is run.

## Project Structure:
```bash
Task_Management_System
│
├── task_management_system.py  # Main application file
├── taskmaster.db              # SQLite database file (auto-generated)
└── README.md                  # Project readme file

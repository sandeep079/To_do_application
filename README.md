# **Todo List Application in C++**

This is a command-line-based Todo List application written in C++. It allows you to create, manage, and track tasks with features such as priority setting, due dates, and filtering.

## **Features**

 ###   Add Tasks:
    Add a task with a description, due date, and priority level.
###  View Tasks:
    Display all tasks or only completed tasks.
 ###   Update Tasks: 
    Modify the description, due date, and priority of existing tasks.
###    Delete Tasks:
   Remove tasks by ID.
   ### Mark as Completed: 
   Mark tasks as completed by ID.
 ###  Search Tasks:
  Find tasks by ID.
 ###   Filter Tasks:
   Filter tasks by priority or due date.
 ###  Count Tasks:
   Display the total number of tasks, completed tasks, and incomplete tasks.
  ###  Data Persistence:
   Saves tasks to a file (todo.txt) and reloads them when the program is restarted.
   # **How to Run**
   Clone the repository:

git clone https://github.com/yourusername/TodoListApp.git
cd TodoListApp

Compile the program:

g++ -o todo_list_app todo_list_app.cpp

Run the program:

    ./todo_list_app

    Note: The program uses a text file (todo.txt) to store tasks. Ensure that the file exists in the same directory as the executable, or it will be created automatically on first run.

# Requirements

    A C++ compiler (e.g., g++ or clang++)
    Operating System: This program is designed for use on Windows (due to the use of system("cls")), but it can be modified for other systems by handling console clearing differently.

# File Structure

TodoListApp/
│
├── todo_list_app.cpp      # Main source code
├── todo.txt               # File where tasks are stored (auto-generated)
├── README.md              # Project documentation
└── .gitignore             # Git ignore file (optional)

# Future Enhancements

    Add the ability to search for tasks by description or due date.
    Improve date validation to include checks for leap years, month length, etc.
    Provide better cross-platform support for clearing the console.
    Implement a GUI version.

# License

This project is licensed under the MIT License - see the LICENSE file for details.
Contributions

Contributions are welcome! Feel free to open issues or submit pull requests.
# Author

    Your Name - Your GitHub Profile

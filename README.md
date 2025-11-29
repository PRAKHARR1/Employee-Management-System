-Introduction
This project is a simple Employee Management System made using basic Python.
It runs in the terminal and allows you to manage employee records such as adding, updating, deleting, and viewing employee information.
All data is stored in a Python list during runtime.

-Features
Add Employee
Enter ID, name, age, gender, position, and salary.
The system checks if the ID already exists.

-Update Employee
Update name, age, gender, position, or salary of an employee using their ID.

Delete Employee
Remove an employee from the system using their ID.

List Employees
Displays all employees in a tabular format.

Exit Option
Close the program safely.

-How the Program Works
A global list named employees is used to store employee data as dictionaries.
The program runs inside an infinite loop and shows a menu to the user.

-Based on user choice:
Functions like add_employee(), update_employee(), delete_employee(), and list_employees() are called.
Data remains only while the program is running (no file/database storage).

Code Structure
employee_management.py
├── add_employee()      # Add new employee
├── update_employee()   # Update employee details
├── delete_employee()   # Remove employee
├── list_employees()    # Display all employees
└── Main loop           # Menu and user interaction

-How to Run
Install Python on your system.
Save the code in a file named employee_management.py.

-Open terminal and run:
python employee_management.py


Choose options from the menu to operate the system.

Sample Output
----Employee Management System-----
1. Add Employee
2. Update Employee
3. Delete Employee
4. List Employees
5. Exit
Enter your choice:

-Future Enhancements
Add file storage for saving employee data permanently
Implement search function
Add input validation
Create GUI using Tkinter


Use CSV or database (SQLite/MySQL)

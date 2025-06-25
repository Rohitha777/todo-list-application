**To-Do List Application (Console-based)**

This is a simple command-line To-Do List app written in Python. It allows users to manage tasks by viewing, adding, removing, and marking them as completed. Tasks are stored in a plain text file (`tasks.txt`) so they persist between sessions.

---


 1. `load_tasks()`

- Reads `tasks.txt` line-by-line.
- Returns a list of task strings.
- Handles the case when the file doesn’t exist (e.g., first run).

2. `save_tasks(tasks)`

- Saves the current list of tasks to `tasks.txt`.
- Each task is written on a new line.

3. `view_tasks(tasks)`

- Displays all tasks in the list.
- Each task shows its index and status (`[ ]` or `[x]`).

4. `add_task(tasks)`

- Prompts the user to enter a new task.
- Appends it to the list with `[ ]` (incomplete status).

 5. `remove_task(tasks)`

- Shows all tasks.
- Prompts the user to select one by number.
- Removes the selected task from the list.

 6. `mark_task_complete(tasks)`

- Shows all tasks.
- Prompts the user to select one by number.
- Replaces `[ ]` with `[x]` to mark as complete.
- Skips if already marked as `[x]`.

---
**OUTPUT**

--- TO-DO LIST ---
1. View Tasks
2. Add Task
3. Remove Task
4. Mark Task as Completed
5. Exit
Choose an option (1-5): 2
Enter task: Study for math test
Task added.

--- TO-DO LIST ---
1. View Tasks
2. Add Task
3. Remove Task
4. Mark Task as Completed
5. Exit
Choose an option (1-5): 2
Enter task: Buy groceries
Task added.

--- TO-DO LIST ---
1. View Tasks
2. Add Task
3. Remove Task
4. Mark Task as Completed
5. Exit
Choose an option (1-5): 1
Your todo-task list:
0 - [ ] Study for math test
1 - [ ] Buy groceries

--- TO-DO LIST ---
1. View Tasks
2. Add Task
3. Remove Task
4. Mark Task as Completed
5. Exit
Choose an option (1-5): 4
Your todo-task list:
0 - [ ] Study for math test
1 - [ ] Buy groceries
Enter the task number to mark as complete: 0
Task marked as complete.

--- TO-DO LIST ---
1. View Tasks
2. Add Task
3. Remove Task
4. Mark Task as Completed
5. Exit
Choose an option (1-5): 1
Your todo-task list:
0 - [x] Study for math test
1 - [ ] Buy groceries

--- TO-DO LIST ---
1. View Tasks
2. Add Task
3. Remove Task
4. Mark Task as Completed
5. Exit
Choose an option (1-5): 3
Your todo-task list:
0 - [x] Study for math test
1 - [ ] Buy groceries
Enter the task number to remove: 1
Removed Task: [ ] Buy groceries

--- TO-DO LIST ---
1. View Tasks
2. Add Task
3. Remove Task
4. Mark Task as Completed
5. Exit
Choose an option (1-5): 1
Your todo-task list:
0 - [x] Study for math test

--- TO-DO LIST ---
1. View Tasks
2. Add Task
3. Remove Task
4. Mark Task as Completed
5. Exit
Choose an option (1-5): 5
Tasks saved. Goodbye!

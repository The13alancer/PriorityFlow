# PriorityFlow — Intelligent Task Scheduling Tool

PriorityFlow is a lightweight command-line task scheduling application built in Python.  
It allows users to add, prioritize, view, and complete tasks while maintaining efficient retrieval of the most urgent task using a heap-based priority queue.

The project demonstrates core computer science concepts such as priority queues, time-complexity-aware task retrieval, file persistence, and modular software design.

---

## Features

- Add tasks with priority levels
- View the highest-priority pending task
- Complete the highest-priority task
- List all pending tasks
- List all completed tasks
- Persistent storage using JSON files
- Simple command-line interface

---

## Technologies Used

- Python
- Heap-based priority queue (`heapq`)
- File I/O
- JSON data storage
- Modular program structure

---

## Project Structure

```text
PriorityFlow/
├── main.py
├── task_manager.py
├── storage.py
├── tasks.json
└── README.md
```

---

## How It Works

Tasks are stored in a heap-based priority queue for efficient retrieval:

```python
(priority, task_id, task_data)
```

Lower priority values represent more urgent tasks:

```text
1 = highest priority
5 = lowest priority
```

This structure allows efficient insertion and removal while keeping the most urgent task available first.

---

## Running the Project

1. Make sure Python is installed on your system.
2. Download or clone the repository.
3. Navigate to the project folder.
4. Run:

```bash
python main.py
```

If your system uses Python 3 explicitly:

```bash
python3 main.py
```

---

## Example Interface

```text
=== PriorityFlow Task Scheduler ===
1. Add Task
2. View Highest-Priority Task
3. Complete Highest-Priority Task
4. List Pending Tasks
5. List Completed Tasks
6. Exit
```

---

## Example Use Cases

- Managing assignments and deadlines
- Practicing heap and priority queue concepts
- Demonstrating efficient task retrieval
- Learning JSON-based persistence in Python

---

## Future Improvements

- Edit task priority
- Delete task by ID
- Search tasks by keyword
- Due-date sorting and overdue warnings
- GUI version using Tkinter
- Unit testing with pytest

---

## Author

Anirudh Jha  
Computer Science — San Diego State University

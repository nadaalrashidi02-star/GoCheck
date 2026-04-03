# ✅ GoCheck — Task Management System

> A Java-based task and goal management application that utilizes the Stack data structure (LIFO) to help users organize their goals and break them down into manageable daily tasks.

---

## 📖 About the Project

**GoCheck** is a Java-based application developed as part of the *CS310: Data Structures* course at Imam Abdulrahman Bin Faisal University. The system helps users manage personal goals across seven key life aspects — Career, Spirituality, Physical Health, Personal Growth, Relationships, Finances, and Entertainment.

It enables users to organize their goals using a stack structure and convert them into actionable tasks, providing a clear and structured planning experience.

The application implements the **Stack data structure** using a **linked list**, following the Last-In-First-Out (LIFO) principle to ensure efficient task handling and memory usage.

---

## 🚀 Features

### 👤 User Role
- **Account Management** — Register or log in with validated username, email, and phone number  
- **Goal Suggestions** — Select from 35 pre-defined goals (5 per life aspect) with auto-generated tasks and suggested deadlines  
- **Custom Planning** — Create personalized goals and tasks with priority and due date settings  

#### Task Management
- Add tasks (suggested or custom)  
- Update goals and task details (description, priority, aspect, due date)  
- Mark tasks/goals as completed (pop operations)  
- Display goals and tasks in stack format  
- Sort tasks by due date or priority  
- Search tasks by due date  

---

### 🔐 Admin Role
- Pre-defined admin accounts  
- **Template Management** — Create and manage goal templates with associated tasks and deadlines  
- **List Management** — Add, update, and display admin-created task lists  
- **Reporting System** — Generate activity reports tracking system operations (add, delete, update, display)  

---

## 🏗️ System Architecture

The system is built around **10 core classes:**

| Class | Description |
|---|---|
| `GoCheck` | Main entry point and system controller |
| `User` | Handles all user-related operations |
| `Admin` | Handles admin functionalities and reporting |
| `Account` | Manages user/admin accounts using a linked list |
| `Task` | Represents a task with its attributes |
| `Goal` | Represents a goal with its attributes |
| `TaskStack` | Stack implementation for tasks (linked list) |
| `GoalsStack` | Stack implementation for goals (linked list) |
| `AdminTaskStack` | Admin-specific task stack |
| `AdminGoalsStack` | Admin-specific goal stack |

---

## 🎯 Supported Goal Aspects

1. 💼 Career  
2. 🕌 Spirituality  
3. 💪 Physical Health  
4. 🌱 Personal Growth  
5. 🤝 Relationships  
6. 💰 Finances  
7. 🎭 Entertainment  

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **Java** | Core application development |
| **Java Swing (JOptionPane)** | User interaction and GUI dialogs |
| **Custom Linked List** | Stack implementation |
| **LocalDateTime** | Managing task deadlines |
| **File I/O** | Reading suggestion lists and generating reports |
| **NetBeans IDE** | Development environment |

## ⚙️ Setup & Installation

### Prerequisites
- Java JDK 8 or higher  
- NetBeans IDE (recommended) or any Java IDE  

### Steps

1. Clone the repository (download the project to your local machine):
   ```bash
   git clone https://github.com/norahalanziii/GoCheck.git
   cd GoCheck


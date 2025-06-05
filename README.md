
# 👥 Human Resource Management System (HRMS)

## 📌 Project Overview

This project is a Java-based Human Resource Management System (HRMS) developed to centralize and automate HR functions. It implements key modules such as:

- Employee Management
- Attendance Tracking
- Leave Management
- Performance Reviews

The system follows the Model-View-Controller (MVC) architecture and incorporates design patterns (Singleton and State) to ensure robust and scalable software architecture. It was developed as part of the ITECH 7201 coursework.

---

## 🧠 System Features

### ✅ Employee Management
- View details for self, all subordinates, or a specific subordinate
- Access employee contact information and hierarchical structure

### 🕒 Attendance Management
- View attendance for self, all subordinates, or a specific subordinate
- Track clock-in/out times and daily presence

### 🌴 Leave Management
- View leave history for self or subordinates
- Displays leave duration, reason, and approval status

### 📈 Performance Management
- Access performance reviews for self and subordinates
- Includes ratings, feedback, review date, and goals

---

## 🧪 Testing

- JUnit 5 used for robust unit testing
- Covered modules: Employee, Attendance, Leave, and Performance
- Tests validate data retrieval, error handling, and edge cases

---

## ⚙️ Design Patterns

### 🔁 Singleton Pattern
- Ensures a single instance of the `HRMSMain` class
- Centralized control and consistent application state

### 🔄 State Pattern
- Manages login/logout behavior dynamically
- Enables scalable and maintainable user session handling

---

## 🗂️ Folder Structure (Conceptual)

```
├── hrms/
│   ├── HRMSMain.java
│   ├── HardCodedData.java
│
├── hrms.boundary/
│   ├── EmployeeUI.java
│   ├── AttendanceUI.java
│   └── ...
│
├── hrms.control/
│   ├── EmployeeControl.java
│   ├── AttendanceControl.java
│   └── ...
│
├── hrms.entity/
│   ├── Employee.java
│   ├── LeaveRequest.java
│   └── ...
│
├── tests/
│   ├── EmployeeControlTest.java
│   ├── AttendanceControlTest.java
│   └── ...
```

---

## 🛠 Technologies Used

- Java
- MVC Architecture
- JUnit 5
- Git & GitHub
- OOP with Inheritance and Interfaces


---

## 👨‍💻 Contributor
- **Syeda Tamanna Sheme** – 30432670


---

## 📄 License

This academic project is intended for educational and demonstration purposes only.


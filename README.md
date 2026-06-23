# CodeAlpha: Student Grade Tracker

A simple and interactive Command Line Interface (CLI) application in Java that allows teachers or administrators to track student grades, calculate statistical values, and display a summary report.

---

## 🚀 Features

- **Dynamic Student Entry**: Enter names and marks/grades for any number of students.
- **Detailed Report Generation**: Displays a clean summary listing each student alongside their marks.
- **Statistical Analytics**: Automatically computes and displays:
  - **Average Marks**: The class average computed across all students.
  - **Highest Marks**: The top mark achieved in the group.
  - **Lowest Marks**: The lowest mark recorded.

---

## 🛠️ Requirements & Setup

### Prerequisites
- **Java Development Kit (JDK)**: Version 8 or higher must be installed on your system.

### Compilation
Compile the Java source code using `javac`:
```bash
javac StudentGradeTracker.java
```

### Execution
Run the compiled class using the `java` launcher:
```bash
java StudentGradeTracker
```

---

## 📋 Example Workflow

Below is a demonstration of how the program interacts with a user:

```text
Enter number of students: 4
Enter student name: megha
Enter marks: 80
Enter student name: mythri
Enter marks: 85
Enter student name: mahanshi
Enter marks: 75
Enter student name: rachana
Enter marks: 70

--- Student Report ---
megha : 80
mythri : 85
mahanshi : 75
rachana : 70
Average Marks: 77.5
Highest Marks: 85
Lowest Marks: 70
```

---

## 📂 Project Structure

- `StudentGradeTracker.java`: The core Java source file containing the user input logic, calculations, and reporting.
- `StudentGradeTracker.class`: The compiled bytecode execution file.

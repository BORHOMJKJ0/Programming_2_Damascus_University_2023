# Programming 2 — Java OOP Examples ✅

**A small Java console application demonstrating core OOP concepts**: inheritance, abstract classes, polymorphism, encapsulation, collection usage (ArrayList), and basic threading.

---

## 📌 Project Overview

This repository contains a collection of simple Java classes and a console program that models an employee/section management system. The main application provides a text-based menu to add/remove employees, terminate service, manage vacations, and display reports by department.

Key concepts illustrated:
- Abstract classes and inheritance (`Employee`, `FullTimeEmployee`, `PartTimeEmployee`, `LongServingEmployee`) 🔧
- Object composition (`Section` containing `Employee` instances) 🧩
- Polymorphism and method overriding (`report()`, `addVacation()`, `getVacation()`) 🔁
- Basic multi-threading example (`Trying` class) 🧵

---

## 🧾 Features

- Add / Remove employees
- Track employee status (serving / retired)
- Compute and display vacations and pay
- Department (section) reports with heads and employees
- Examples of small utility classes (`Building`, `Hospital`, `School`, `Student`, `Person`)

---

## 🛠️ Technologies

- Java (SE)
- No external dependencies

---

## 🚀 Getting Started (Windows)

Open a command prompt and run the following commands from the project root.

### Compile (from repository root)

```cmd
cd Programming_2\src
javac *.java
```

This compiles all classes into the current directory (you may prefer to use the `-d` option to place class files in an output folder).

### Run

```cmd
java JAVA
```

The program will display an interactive menu where you can manage employees and view reports.

---

## 🔍 Main Files & What They Do

- `JAVA.java` — Application entry point and interactive menu (adds/removes employees, queries vacations, prints reports).
- `Employee.java` — Abstract base class for employees.
- `FullTimeEmployee.java` — Full-time employee implementation (salary, leave calc).
- `LongServingEmployee.java` — Long-serving employee (extended leave logic).
- `PartTimeEmployee.java` — Part-time employee (hourly pay calculation).
- `Section.java` — Department container; keeps an `Employee` head and a list of employees.
- `Trying.java` — Small thread example that generates random doubles and sleeps.
- `Building.java`, `Hospital.java`, `School.java`, `Person.java`, `Student.java`, `Operation.java` — Additional example classes used to demonstrate simple class hierarchies and methods.

---

## 💡 Usage Notes & Examples

- The program uses console input. Follow the on-screen prompts to select menu options and enter data.
- When adding employees you will be prompted for name, address, birthdate, and type-specific info (years of service or worked hours).
- Example menu options shown in `JAVA.java` include adding employees, deleting, ending service, adding vacation days, showing retired employees, and printing sections.

---

## ✅ Contribution

This repository is intended for learning and demonstration. If you want to contribute improvements (better input validation, tests, persistence, or a GUI), feel free to open a pull request or create an issue describing your changes.

---

## 📝 License

This project contains example educational code and does not include a formal license file. Add a license if you plan to publish or share beyond course use.

---

## Author

- Student project — created for Programming 2 (Damascus University)

---

If you want, I can also:
- Add a sample run log or screenshots ✅
- Add unit tests with JUnit ✅
- Improve input validation and error handling ✅

Let me know which of these you'd like next! ✨

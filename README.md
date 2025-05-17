# Functional Expense Tracker

A minimalist, command-line expense tracker built in Java demonstrating **Functional Programming (FP)** principles for backend development.

---

## 🚀 Project Overview

This project showcases how functional programming concepts can be applied in Java backend systems to build clean, maintainable, and scalable applications. It features:

- **Immutable data models** using final classes and fields
- **Pure functions** for business logic, avoiding side effects
- Usage of Java’s **Stream API** for elegant data processing and aggregation
- A focus on **concise and expressive code** reflecting real-world payment and transaction workflows

The Functional Expense Tracker allows users to add, view, and analyze expenses by category and month through a simple CLI interface.

---

## 🎯 Why This Matters

In real-world payment systems (like those Juspay builds), reliability, immutability, and clear data flows are critical. This project simulates these qualities on a small scale by emphasizing:

- Robust and error-resilient input handling  
- Stateless functions for calculations and filtering  
- Immutable collections for safe concurrency  

This foundation prepares developers for designing fault-tolerant, scalable payment backends.

---

## ⚙️ Features

- Add expenses with category, amount, and date (immutable expense objects)  
- Calculate total spend across all entries  
- Generate category-wise spend reports  
- Filter expenses by month  
- Input validation with user-friendly prompts  

---

## 🛠️ Technologies Used

- Java 17+  
- Java Stream API for functional data operations  
- Immutable object patterns  
- Pure function design principles

##Tools

--IntelliJ IDE

---

## 📚 How to Run

1. Clone the repository  
2. Compile the project using `javac` (or your preferred IDE)  
3. Run the `Main` class  

```bash
javac -d out src/model/*.java src/service/*.java src/utils/*.java src/Main.java
java -cp out Main

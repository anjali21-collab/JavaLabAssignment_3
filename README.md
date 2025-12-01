# 🎓 Student Record Management System  
### Java Programming Lab | Semester 3 | KRMU  
### Student Records Management Project

A comprehensive, persistent, and multithreaded command-line application designed to manage student records.  
This project is a consolidation of **Lab Assignments 1 – 5**, showcasing mastery in:

- Object-Oriented Programming  
- Java Collections Framework  
- File I/O  
- Exception Handling  
- Multithreading  

---

## 🚀 Key Features

### 🔐 **PERSISTENT STORAGE**
Automatically saves and loads all student records using a local file (**students.txt**) so that data is never lost between runs.

### 🧵 **MULTITHREADING**
Includes a simulated *“Loading…”* animation using background threads to mimic real-world processing delays.

### 📊 **SMART SORTING**
Sorts all student entries by **Marks (Descending)** using a custom `Comparator`.

### ✔️ **ROBUST VALIDATION**
- Prevents duplicate Roll Numbers  
- Ensures Marks are always within the valid range (0–100)  

### 🛑 **ERROR HANDLING**
Uses a custom exception — **StudentNotFoundException** — to avoid crashes and gracefully handle missing records.

### 🧩 **MODULAR ARCHITECTURE**
Clean separation of components using:

- **model** package → Student class  
- **service** package → StudentService / Manager  
- **util** package → FileHelper, Validation utilities  

Promotes clean, scalable, and maintainable code.

## 👤 Author

**Anjali Tomar (2401010080)**  
*K.R. Mangalam University*  
*School of Engineering & Technology*


---


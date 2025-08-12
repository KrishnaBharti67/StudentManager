# 🎓 StudentManager

A simple **C++ console-based Student Management System** to add, view, sort, search, and analyze student marks.  
Includes a custom merge sort implementation, search functionality, and highest/lowest scorer detection.

---

## ✨ Features
- 📌 **Add Students** — Enter student name and marks.
- 📋 **View Students** — Display all stored student records.
- 📊 **Sort Students** — Sort by marks (ascending/descending).
- 🔍 **Search Students** — Find students by name.
- 🏆 **Find Highest & Lowest Scorer** — Identify top and bottom performers.

---

## 🛠️ How It Works
- **Data Structure**: Uses `std::vector<std::pair<std::string, int>>` to store student names and marks.
- **Sorting**: Implements **Merge Sort** for efficient sorting.
- **Searching**: Linear search for quick name lookup.
- **Analysis**: Finds maximum and minimum scores.

---

## 📷 Example
<img width="422" height="754" alt="Adding Students" src="https://github.com/user-attachments/assets/06c81ff0-0b31-455e-9aa0-c9d6cbc8404d" />
<img width="455" height="791" alt="View and Stats" src="https://github.com/user-attachments/assets/e920d4e1-b41b-4a1b-8ebe-2512154c17cd" />

---

## 🚀 Getting Started

### Prerequisites
- C++ compiler (g++, clang++, MSVC, etc.)
- Basic knowledge of compiling C++ programs

### Compilation
```bash
g++ -std=c++17 main.cpp -o StudentManager
```

📂 Project Structure
StudentManager/
├── main.cpp     # Source code
├── README.md    # Documentation

🤝 Contributing
Contributions are welcome!
Feel free to fork this repo, open issues, or submit pull requests.



# 📌 Student Record System  

### 🔹 Overview  
The **Student Record System** is a simple **GUI-based application** built with **Python, Tkinter, and SQLite** to manage student records efficiently. Users can **add, view, and delete student records** with an easy-to-use interface.  

### 🔹 Features  
✅ **Add Students** – Store student details (Name, Age, Grade).  
✅ **View Student Records** – Displays all students in a table format.  
✅ **Delete Student Records** – Remove selected student records.  
✅ **SQLite Database Integration** – Persistent data storage.  
✅ **Tkinter GUI** – Simple and user-friendly interface.  

### 🔹 Tech Stack  
🛢 **Database:** SQLite  
🖥 **GUI Framework:** Tkinter  
💻 **Language:** Python  

### 🔹 Installation & Setup  
#### 1️⃣ Install Python  
Ensure **Python 3.x** is installed on your system.  

#### 2️⃣ Install Dependencies  
```sh
pip install tk
```

#### 3️⃣ Run the Application  
```sh
python student_record_system.py
```

### 🔹 Usage  
1️⃣ **Enter Student Details** (Name, Age, Grade).  
2️⃣ **Click "Add Student"** to save the record.  
3️⃣ **View Records** in the table below.  
4️⃣ **Select a Student & Click "Delete Student"** to remove the record.  

### 🔹 Database Schema  
The system uses a **single SQLite table**:  
CREATE TABLE students (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    name TEXT NOT NULL,
    age INTEGER NOT NULL,
    grade TEXT NOT NULL
);
```

### 🔹 Future Enhancements  
🔹 **Update Student Records**  
🔹 **Search Functionality**  
🔹 **Export Data to CSV**  
🔹 **Modern UI with Custom Themes**  

### 🔹 Screenshots  
📸 **(Include Screenshots of the GUI Here)**  

### 🔹 Project Demo  
📍 **GitHub Repository:**https://github.com/mosesjohnson0104/Student-Record-System  

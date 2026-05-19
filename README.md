# 📊 Attendance Management System (Python + SQLite + CSV)

A simple yet powerful **Command Line Interface (CLI)** based Attendance Management System built using Python.  
This project helps in managing student/employee attendance records efficiently using both **SQLite database** and **CSV file storage**.

---

## 🚀 Features

- ✅ Mark Attendance (Present / Absent / Late)
- 🔍 View Attendance Records (by Student ID or Date)
- ✏️ Update Attendance Records
- ❌ Delete Attendance Records
- 📊 Generate Attendance Reports
- 💾 Dual Storage System (SQLite + CSV)
- 🧾 Automatic report export in CSV format

---

## 🛠 Technologies Used

- Python 3
- SQLite3 (Database)
- CSV Module
- OS Module (for file handling)

---

## 📂 Project Structure


AttendanceManagementSystem/
│
├── main.py # Main menu system
├── attendance.py # Core attendance functions
├── database.py # Database setup (SQLite)
├── reports.py # Report generation
├── utils.py # CSV setup utilities
│
├── attendance.db # SQLite database (auto-generated)
├── attendance.csv # Attendance CSV file (auto-generated)
├── report.csv # Generated reports
│
├── reports/ # Monthly reports folder
├── backup/ # Database backup folder
│
├── README.md # Project documentation
└── requirements.txt # Dependencies


---

## ▶️ How to Run the Project

### 1. Install Python
Make sure Python 3 is installed on your system.

### 2. Clone the Repository
```bash
git clone https://github.com/your-username/attendance-management-system.git
3. Navigate to Project Folder
cd AttendanceManagementSystem
4. Run the Application
python main.py
📊 Sample Usage
========== Attendance Management System ==========

1. Mark Attendance
2. View Records
3. Update Record
4. Delete Record
5. Generate Report
6. Exit
📈 Sample Report Output
Present: 5
Absent: 2
Late: 1
Attendance Percentage: 83.33%
💡 Future Improvements
🌐 GUI version using Tkinter
📊 Data visualization using Matplotlib
📧 Email report automation
🔐 User authentication system
☁️ Cloud database integration
👨‍💻 Author

Your Name
Computer Science Student
Passionate about Python Development & Data Systems

⭐ Acknowledgements

This project is built for educational purposes to demonstrate:

File handling in Python
Database integration
Real-world attendance system logic
📜 License

This project is open-source and free to use for learning purposes.

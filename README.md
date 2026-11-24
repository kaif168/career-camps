# Career Camps 🎓 (2023)

A **Python + MySQL based project** that helps students explore colleges, check exam details, and personalize their career journey.  
It provides both **Admin** and **User** workflows, along with college info, exam registration tracking, and website redirection.

---

## 🚀 Features
- **Admin Panel**
  - Register/Login as Admin
  - Add or view user details
- **User Panel**
  - Register/Login as User
  - Password validation with security checks
  - Personalized exam tracker (register and view exams)
- **College Information**
  - Explore details like courses, awards, ratings, reviews, location, activities
  - Directly open official websites from the program
- **Exam Information**
  - View top competitive exams (JEE, NEET, GATE, etc.)
  - Get direct links to exam sites

---

## 🛠️ Tech Stack
- **Programming Language:** Python 3
- **Database:** MySQL
- **Modules Used:**  
  - `mysql.connector` (database connection)  
  - `webbrowser` (open official sites)  
  - `os`, `sys` (file handling, exit control)

---

## 📂 Project Structure
```
Career-Camps/
│── colleges/          # .txt files for each college info
│── exams/             # exam details (optional txt files)
│── main.py            # entry point
│── auth.py            # login/register system
│── database.py        # database connection & queries
│── README.md          # project description
```

---

## ⚡ How to Run
1. Install dependencies:
   ```bash
   pip install mysql-connector-python
   ```
2. Set up MySQL database:
   - Create a schema (e.g., `career_camps`)
   - Create `admin_details` and `user_details` tables
3. Run the project:
   ```bash
   python main.py
   ```

---

## ✨ Future Improvements
- Use **hashed passwords** instead of plain text
- Replace per-user tables with a **single exam registration table**
- Add **GUI (Tkinter/Flask)** for better UX

---

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).

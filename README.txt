==================================================
📝 Project Title: Online Smart Learn System
👤 Created by: [MEHEDI HASAN RAKIB]
🎓 Submitted to: [NAYEEMA SULTANA AYEESHA / SE 410]
==================================================

📁 Project Structure:
- All source files are inside the 'onlinequizsystem1' folder.
- This project includes:
  ✔ LoginForm.java
  ✔ Dashboard.java
  ✔ QuizForm.java
  ✔ DBConnection.java
  ✔ SQL file for database (optional if included)

✅ How to Run:
1️⃣ Open NetBeans.
2️⃣ Go to File → Open Project → Select the folder 'onlinequizsystem1'.
3️⃣ Run the file: `LoginForm.java`.
4️⃣ A login window will appear.
5️⃣ Use role: Student or Admin (must exist in DB).
6️⃣ Based on role, Quiz or Dashboard will open.


~~For {LOGIN}

      
          id              password
 
Student: 1145                1234


Admin  : admin1               admin123

🧩 Required Tools:
- NetBeans IDE
- MySQL (XAMPP recommended)
- MySQL Connector/J (already added in project lib)

🛠 Database Info:
- Database Name: `online_quiz`
- Table: `students`
  Columns: student_id, name, address, password, role
- Table: `questions`
  Columns: question_text, option1, option2, option3, option4, correct_option

💡 Note:
If you get database error, make sure MySQL is running and correct credentials are used in `DBConnection.java`.

📦 Submission Format:
- Zip the folder `onlinequizsystem1` with this README.txt inside.
- Submit via Google Classroom or as instructed.

📅 Date: [Insert Date]

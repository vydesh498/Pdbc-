# PDBC-PROJECT
📂 Project Structure
HR-Management-System/
│
├── main.py
├── requirements.txt
├── database_schema.sql
└── README.md
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/hr-management-system.git
cd hr-management-system
2️⃣ Install Required Libraries
pip install -r requirements.txt
3️⃣ Setup MySQL Database

Create a database named: hr_analytics

Create required tables:

Users

Employees

Departments

You can import the provided database_schema.sql file.

4️⃣ Run the Application
python main.py
🗄 Database Schema Overview
📌 Users Table

id (Primary Key)

username

password

📌 Employees Table

emp_id (Primary Key)

first_name

last_name

gender

hire_date

department_id (Foreign Key)

salary

status

📌 Departments Table

department_id (Primary Key)

department_name

📊 Analytics Included

✔ Salary Distribution (Bar Chart)
✔ Department-wise Employee Distribution (Pie Chart)
✔ SQL JOIN Operations
✔ Group By Aggregations

🔐 Security Improvements (Future Scope)

Implement password hashing (bcrypt)

Use environment variables for DB credentials

Role-based access control (Admin / HR)

🚀 Future Enhancements

Export employee reports to Excel

Add search & filter functionality

Implement attendance tracking

Add dashboard view using Flask or Streamlit

Deploy on cloud (AWS / Render)

📈 Skills Demonstrated

SQL (CRUD, JOIN, GROUP BY)

Python Programming

Database Connectivity

Data Visualization

Backend Logic Development

Problem Solving

🏆 Learning Outcomes

Through this project, I strengthened my understanding of:

Real-world HR data management systems

Writing optimized SQL queries

Integrating database systems with Python

Creating visual insights from raw data

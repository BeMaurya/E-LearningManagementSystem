# 🎓 E-Learning Management System  
A web-based E-Learning Management System designed to manage online classes, assignments, announcements, and learning resources.  
The system supports admin and student roles, database-driven content, and structured documentation for academic use.

## 📁 Project Structure
```pgsql
E-LearningManagementSystem/
│
├── Database/
│   └── capstone.sql          # Database schema & initial data
│
├── Documentation/
│   └── Report.pdf            # Project documentation
│
├── Source File/
│   ├── admin/                # Admin modules
│   ├── db/                   # Database connection files
│   ├── tests/                # Test-related files
│   ├── vendor/               # External libraries
│   ├── *.php                 # Core application files
│
└── README.md
```

## ✨ Features
- Admin panel for managing classes, announcements, and assignments
- Student access to learning materials and announcements
- Database-driven content management
- Assignment upload and downloadable resources
- Structured documentation and project report
- SQL-based database initialization

## 🧰 Tech Stack
- 🎨 Frontend: HTML, CSS, JavaScript
- ⚙️ Backend: PHP
- 🗄️ Database: MySQL
- 🌐 Server: Apache (XAMPP / WAMP)
- 📄 Documentation: PDF Report
- 🔧 Version Control: Git & GitHub
  
## 🧠 Architecture Overview  
The system follows a monolithic web architecture, where frontend and backend are tightly integrated.  
- Users interact through a browser-based UI
- PHP handles business logic and request processing
- MySQL stores users, classes, assignments, and resources
- Admin and student roles access different modules
- SQL scripts initialize and manage the database schema

### 🏗️ Architecture Diagram (Logical Flow)
```less
[ User / Admin ]
        |
        v
[ Web Browser ]
        |
        v
[ PHP Application Layer ]
        |
        v
[ MySQL Database ]
```

#### Flow Explanation:
- Browser sends requests to PHP scripts
- PHP processes logic (auth, classes, assignments)
- MySQL stores and retrieves persistent data
- Responses are rendered back to the user

## ⚙️ Installation & Setup
### Prerequisites
- 🖥️ XAMPP / WAMP Server
- 🐘 PHP 7+
- 🛢️ MySQL
- 🌍 Web Browser (Chrome / Firefox recommended)
### Steps  
1️⃣ Clone the repository

```powershell
git clone https://github.com/BeMaurya/E-LearningManagementSystem.git
```
2️⃣ Move Project to Server Directory  
Move the project folder into:
- `htdocs` (XAMPP) or
- `www` (WAMP)

3️⃣ Create Database  
Create a MySQL database with the name:
```text
capstone
```

4️⃣ Import Database Schema  
Import the SQL file located at:
```sql
Database/capstone.sql
```

5️⃣ Configure Database Credentials  
Update database credentials in the PHP configuration files if required:
```text
host, username, password, database name
```

6️⃣ Run the Application  
Open your browser and navigate to:
```url
http://localhost/E-LearningManagementSystem/
```

## 📌 Usage
- Admin can manage classes, announcements, assignments
- Students can view announcements and download resources
- Database ensures persistent and structured storage

## 🚀 Future Enhancements
- Role-based authentication
- Responsive UI redesign
- REST API-based backend
- Cloud deployment
- Student progress tracking

## ❤️ Contributions
Contributions are welcome!
> Fork the repo → Create a branch → Add feature → Submit PR

</br></br>
<div align="center">
<p>📘 This project is created strictly for educational and learning purposes.</p>
<p>⭐ If you find this project helpful, feel free to star the repository!</p>
<p>© 2026 <strong><a href = "https://bemaurya.github.io">BeMaurya</a></strong>. All rights reserved.</p>
</div>

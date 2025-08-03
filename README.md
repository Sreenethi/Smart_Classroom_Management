# 📚 Student Attendance Management System

This is a web-based **Student Attendance Management System** built using PHP and MySQL. It efficiently handles attendance tracking and user data management for schools, colleges, and institutions. The system is divided into three panels: **Admin**, **Teacher**, and **Student**.

## ✨ Key Features

### 🔐 Admin Panel
- Manage teacher and student accounts.
- View and edit all attendance records.
- Generate reports.
- Add/edit/delete users, subjects, and schedules.

### 👨‍🏫 Teacher Panel
- View assigned students and subjects.
- Mark and update student attendance.
- Filter attendance by date, subject, and student.
- Track class performance.

### 👨‍🎓 Student Panel
- View own attendance records.
- Download attendance reports.
- Monitor attendance trends.

## ⚙️ Installation & Setup

1. Clone or download the repository.
2. Place it in your `htdocs` (XAMPP) or equivalent local server folder.
3. Create a MySQL database and import the provided `.sql` file from the `database` folder.
4. Configure your database connection in `/includes/config.php`.

```php
// Example DB config
$host = 'localhost';
$user = 'root';
$pass = '';
$db   = 'attendance_system';
```

5. Start Apache and MySQL via XAMPP.
6. Open your browser and go to `http://localhost/student-attendance-system`.

## 🔑 Default Logins (You Can Change These)

- **Admin**
  - Email: `admin@mail.com`
  - Password: `admin123`
- **Teacher**
  - Email: `teacher@mail.com`
  - Password: `teacher123`
- **Student**
  - Email: `student@mail.com`
  - Password: `student123`

## 🖼️ Screenshots

> 🔧 You can add your own screenshots in this section.
> 
> Example:
> 
> ![Dashboard Screenshot](path/to/your/image1.png)
> 
> ![Attendance Management](path/to/your/image2.png)

## 🚀 Future Enhancements

- Facial recognition for attendance using AI.
- Real-time notification system for absentees.
- Mobile app integration.
- Email and SMS alerts.

## 📄 License

This project is open-source and free to modify for personal or institutional use.
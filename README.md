# Frappe Student App

This is a custom Frappe application created as part of the project assignment.

## 🚀 Features
- Custom DocType: **Student**
- Fields included: Name, Age, Email, Enrollment_date
- Ability to add, edit, and view student records

## 🛠️ Setup Instructions

### Requirements
- Python 3.10+
- Bench CLI
- Frappe Framework v14+
- Redis, MariaDB (installed via Frappe bench setup)

### Installation Steps
```bash
bench init frappe-bench
cd frappe-bench
bench new-site mysite.local
bench get-app my_custom_app https://github.com/yourusername/frappe-student-app.git
bench --site mysite.local install-app my_custom_app
bench start

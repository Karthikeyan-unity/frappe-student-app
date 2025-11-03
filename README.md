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
🚨 Challenges & Solutions
Challenge	Solution
Bench install errors	Installed dependencies & re-ran install
Migration errors	Used bench --site mysite.local migrate
Git push auth issue	Generated GitHub PAT
📸 Screenshots
created DocType named as Student
<img width="1118" height="470" alt="image" src="https://github.com/user-attachments/assets/6275cb4d-ca73-4ce5-a59f-9bf3898f8ba6" />
inserted the data
<img width="1227" height="620" alt="image" src="https://github.com/user-attachments/assets/ef6d5f56-2572-4565-bc8f-b324fcadd2f0" />
📸 Screencast video


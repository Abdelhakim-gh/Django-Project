# Django Project
This is a Simple Student Management System Developed for Practice purpose using Python framework for web `Django`.

**Tools:**
- `Django`
- `Boostrap `
- `Chart.js`
- `SQLite `

### Admin Users Can
- Consult Summary Charts (Dashboard) 
- Manage Staffs C.R.U.D
- Manage Students C.R.U.D
- Manage Fields C.R.U.D
- Manage Subjects C.R.U.D
- Manage Semesters C.R.U.D
- View Student Attendance

### Staff/Teachers Can
- Consult Summary Charts (Dashboard)
- Take & Update Students Attendance

### Students Can
- Consult Summary Charts (Dashboard)
- View Attendance

### Installation & Setup of Project

**Create a Folder where you want to save the project**

> it is better to create venv so we wont effect other project that work with older versions

**Create a Virtual Environment and Activate**
```
pip install virtualenv

python -m venv venv

source venv/bin/activate
```

**Clone project or download it**

Then, Enter the project
```
cd django-student-management-system
```

**Install Requirements from 'requirements.txt'**
```python
pip install -r requirements.txt
```

**Run Server**
```python
python manage.py runserver
```
**Login for:**

*Admin*
- Email: admin@gmail.com
- Password: admin

*Staff*
- Email: staff@gmail.com
- Password: staff

*Student*
- Email: student@gmail.com
- Password: student
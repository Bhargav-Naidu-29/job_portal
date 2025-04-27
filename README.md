# CareerPath - Job Portal 🌐

**CareerPath** is a Django-based job portal that facilitates seamless interaction between job seekers and employers. It allows recruiters to post jobs, candidates to apply, and administrators to manage all user activities and data from a single platform.

🔗 **Live Site**: [https://job-portal-neon-zeta.vercel.app/](https://job-portal-neon-zeta.vercel.app/)

___


## 🚀 Features

### 👤 Applicant
- Register and login securely.
- View available job listings.
- Apply to multiple jobs.
- Track submitted applications.

### 👔 Employer (HR)
- Register as a recruiter.
- Post new job opportunities.
- View candidate applications.
- Manage their job listings.

### 🛡️ Admin
- Monitor all registered users and job listings.
- Approve, reject, or delete jobs.
- Ensure platform integrity and remove spam.

---

## 🛠️ Tech Stack

| Technology | Role                        |
|------------|-----------------------------|
| Django     | Backend web framework       |
| HTML/CSS   | Frontend design             |
| PostgreSql     | Relational database Management |
| Vercel     | Deployment platform         |

---

## 📁 Folder Structure

```
job_portal/
├── authuser/             # Handles user registration and login
│   ├── templates/
│   ├── admin.py
│   ├── models.py
│   └── views.py
├── candidate/            # Candidate-side logic
│   ├── templates/
│   ├── admin.py
│   ├── models.py
│   └── views.py
├── hr/                   # Recruiter-side logic
│   ├── templates/
│   ├── admin.py
│   ├── models.py
│   └── views.py
├── jobs_portal/          # Project settings and configuration
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── db.sqlite3            # SQLite database
├── manage.py             # Django management script
├── Procfile              # For deployment configuration (Heroku compatibility)
├── requirements.txt      # Python dependencies
└── vercel.json           # Configuration for Vercel deployment
```

---

## ⚙️ Setup Instructions

Follow the steps below to run this project locally:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Bhargav-Naidu-29/job_portal.git
   cd job_portal
   ```

2. **Create a Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Required Packages**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply Migrations**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Run the Server**
   ```bash
   python manage.py runserver
   ```

6. **Access Locally**
   Open your browser and go to `http://127.0.0.1:8000/`


---

## 🤝 Contributing

Found a bug or want to contribute a new feature? Fork the repository and open a pull request. All contributions are welcome!

---

---

# CareerPath - Job Portal 🌐

Welcome to **CareerPath**, a Django-powered job portal where employers post job openings, candidates apply for opportunities, and an admin manages all platform activities. This system is designed to streamline the recruitment process, making job hunting and hiring more efficient and user-friendly.

🚀 **Live Demo**: [CareerPath on Vercel](https://job-portal-neon-zeta.vercel.app/)

---

## 🖼️ Preview

### 🔐 Login Page
![Login Screenshot]([https://raw.githubusercontent.com/Bhargav-Naidu-29/job_portal/main/screenshots/login.png](https://media-hosting.imagekit.io/1c023faf957747e5/Screenshot%202025-04-25%20014017.png?Expires=1840139482&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=l8xLW4lr6XX5XXpDOLYHFzhhvkqRWxV4jMCvyoWNylEEvn9Hmm5nVnRmzKHFamCWbi-NBWWDdunil6o8LqIr~TspEOrXsCplIINnV-ZSzQtrRdEubJ5Mrqzq3H-yB3WWCv2Z5qhZVqhB-Rb-EZexZZvJ94NsGHH3sBTmd3mrkX-MntCHUORkXEFaAhH1WHjjchszfHwFkiL9~72gPwKrLwK2eJm9XyP-d5bY1IR68zKbuvPlRs2b2DTAffk6-O3SZPSSbgEySZLcxICV1X5SyJb3lbnKoN2MxhV5LZjsnTjM83IL749n-WLsN-liN-eNX7yBke6wC5JAK2oEguIbyQ__))

### 📝 Registeration Page
![HR Registration Screenshot](https://media-hosting.imagekit.io/861a1b682fb3429c/Screenshot%202025-04-25%20014201.png?Expires=1840139482&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=x9jDNm8mabOVU3GPJhtsY5MNLCfB8v0NEudY~myCd0~dTvYXRvg1Hc2CUXJY5uoNUjFAseQeE63AuuphNY-cuRX6GYixA7gxQ9ixOoXnBmn-TtdFOUD3f9sY9-gPDNZqQckSEg7pq2oykSNzoYhfjkaKrk32q4KLBfDb6PDTYdNjiiv9nMbFDa3rwMtgcSwXxJ8A2BAA3W4r-IiST21NYsZ-t1q1w7MolFqBb-wFcY59BQla7Nj2JsvpKylbLzKHYKpzTd3UBUzF~Rrqt6vfbxP1nXYbanvQ7N4rlGZ6eaopOYAd4kfIQNWRpeQgnyYXRiTfXb7HUnzbq8LkUqTePg__)

---

## 📌 Features

### 👨‍💼 Employer
- Sign up and log in securely.
- Post new job listings.
- View applications for posted jobs.
- Manage job visibility and details.

### 👨‍🎓 Applicant
- Sign up and log in securely.
- View all available job listings.
- Apply for jobs with a single click.
- Manage application history.

### 🛠️ Admin Panel
- Monitor and manage all user accounts.
- Approve or reject job listings.
- View application statistics.
- Handle spam or inappropriate content.

---

## 🛠️ Tech Stack

| Technology | Purpose              |
|------------|----------------------|
| Django     | Backend Framework    |
| SQLite     | Default DB (can be changed) |
| HTML/CSS   | Frontend UI          |
| Vercel     | Deployment Platform  |

---

## 🧑‍💻 How to Run Locally

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Bhargav-Naidu-29/job_portal.git
   cd job_portal
   ```

2. **Create a Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Requirements**
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

6. Visit `http://127.0.0.1:8000/` in your browser.

---
job_portal/
├── authuser/             # Handles user authentication and registration
│   ├── migrations/
│   ├── templates/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── candidate/            # Manages candidate-specific functionalities
│   ├── migrations/
│   ├── templates/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── hr/                   # Manages employer (HR) functionalities
│   ├── migrations/
│   ├── templates/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── jobs_portal/          # Project configuration and settings
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── db.sqlite3            # SQLite database file
├── manage.py             # Django's command-line utility
├── Procfile              # Deployment configuration for platforms like Heroku
├── requirements.txt      # Python dependencies
└── vercel.json           # Vercel deployment configuration


## 🤝 Contributing

Contributions are welcome! If you'd like to improve something, feel free to open an issue or pull request.

---


## 📚 Learning Management System (LMS)  

A Django-based Learning Management System (LMS) that provides a robust and scalable platform for delivering educational content, managing courses, and tracking student progress.  

---

## 🚀 Features  

- **User Authentication**: Secure login and registration system.  
- **Course Management**: Create, update, and delete courses.  
- **Enrollment System**: Students can enroll in courses.  
- **Content Delivery**: Supports videos, PDFs, text, and quizzes.  
- **Assignments & Quizzes**: Interactive assessments for students.  
- **Progress Tracking**: Monitor student activity and performance.  
- **Discussion Forums**: Encourage peer-to-peer learning.  
- **Payment Integration**: Secure transactions using Razorpay.  

---

## 🛠️ Tech Stack  

- **Backend**: Django (Python)  
- **Frontend**: HTML, CSS, JavaScript, jQuery, AJAX  
- **Database**: PostgreSQL / SQLite  
- **Authentication**: Django's built-in user management  
- **Payment Gateway**: Razorpay  

---

## 📂 Installation & Setup  

### 1️⃣ Clone the Repository  

```bash
git clone https://github.com/your-username/LMS-Django.git
cd LMS-Django
```

### 2️⃣ Create a Virtual Environment  

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3️⃣ Install Dependencies  

```bash
pip install -r requirements.txt
```

### 4️⃣ Configure the Database  

Update **settings.py** with your database credentials:  

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',  # Change to 'sqlite3' if using SQLite
        'NAME': 'lms_db',
        'USER': 'your_db_user',
        'PASSWORD': 'your_db_password',
        'HOST': 'localhost',
        'PORT': '5432',
    }
}
```

Run migrations:  

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5️⃣ Create a Superuser  

```bash
python manage.py createsuperuser
```

### 6️⃣ Run the Development Server  

```bash
python manage.py runserver
```

Access the LMS at: [http://127.0.0.1:8000](http://127.0.0.1:8000)  

---

## 🖼️ Screenshots  

| Home Page | Course View | Login Page |
|-----------|------------|------------|
| ![Home](media/Media/output/Pictu1.png) | ![Courses](media/Media/output/Pictu2.png) | ![Login](media/Media/output/Pictu4.png) |

---

## 📌 Future Enhancements  

- ✅ Mobile App Version  
- ✅ AI-based Personalized Learning Paths  
- ✅ Automated Grading System  
- ✅ Multi-language Support  

---


## 🤝 Contributing  

Contributions are welcome! Feel free to submit a pull request.  

---

### 🎯 Developed by  
**Indupriyashirisha** | JNNCE CS&E | IEEE Student Branch  


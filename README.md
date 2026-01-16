# 📝 Flask Blog Website

A production-ready Flask blog application with authentication, rich-text editing, and PostgreSQL support, deployed on Render using Gunicorn and environment-based configuration.

## 🚀 Features
🔐 User Authentication | 📝 Create & Edit Blogs | 🖋️ CKEditor  
👤 Gravatar Avatars | 🗄️ PostgreSQL (Prod) | 🧪 SQLite (Local)  
🌐 Bootstrap UI | 🔑 Environment Variables | ⚙️ Gunicorn Deployment  

## 🛠️ Tech Stack
Backend: Python, Flask  
Database: PostgreSQL / SQLite  
ORM: SQLAlchemy  
Auth: Flask-Login  
Forms: Flask-WTF  
Frontend: Bootstrap, Jinja2  
Deployment: Render | Server: Gunicorn  

## 📁 Structure
main.py | requirements.txt | runtime.txt | Procfile | templates/ | static/ | instance/

## ⚙️ Environment Variables (.env – not committed)
SECRET_KEY=secret-key  
DATABASE_URL=sqlite:///yourdatabase.db  
EMAIL_KEY=email  
PASSWORD_KEY=password  

## 🧪 Local Setup
git clone https://github.com/your-username/your-repo-name.git  
cd your-repo-name  
python -m venv .venv  
.venv\Scripts\activate  
pip install -r requirements.txt  
python main.py  
Visit: http://127.0.0.1:5000  

## 🌍 Render Deployment
Start Command: gunicorn main:app  
Runtime: python-3.11.8  
Add DATABASE_URL from Render PostgreSQL service  

## 🔒 Security
Environment-based secrets | .env in .gitignore | No hardcoded credentials  

## 🧠 Learnings
Flask production setup, PostgreSQL integration, Render deployment, Gunicorn debugging  

## 📌 Future
Admin panel | Comments | Image uploads | Pagination | Docker  

## 👨‍💻 Author
Fedrick Samuel W — Software Developer | Flask | Backend  

⭐ Star the repo if you like it!

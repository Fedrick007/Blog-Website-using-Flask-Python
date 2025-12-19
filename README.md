📝 Flask Blog Website

A full-featured Flask-based blog web application built with authentication, rich-text editing, and PostgreSQL support, deployed using Render.
This project follows production-ready practices such as virtual environments, environment variables, and Gunicorn.


🚀 Features

🔐 User Authentication (Login / Register)
📝 Blog Post Creation & Editing
🖋️ Rich Text Editor (CKEditor)
👤 User Avatars (Gravatar)
🗄️ PostgreSQL Database (Production)
🧪 SQLite Support (Local Development)
🌐 Responsive UI with Bootstrap
🔑 Secure Environment Variable Handling
⚙️ Gunicorn for Production Deployment



🛠️ Tech Stack

  Backend: Python, Flask
  Database: PostgreSQL (Render) / SQLite (Local)
  ORM: SQLAlchemy
  Authentication: Flask-Login
  Forms: Flask-WTF, WTForms
  Frontend: Bootstrap, Jinja2
  Deployment: Render
  Server: Gunicorn



📁 Project Structure
 
  .
  ├── main.py
  ├── requirements.txt
  ├── runtime.txt
  ├── Procfile
  ├── .gitignore
  ├── templates/
  ├── static/
  ├── instance/



⚙️ Environment Variables

  This project uses environment variables for security.

  Local Development (.env)

  .env
  SECRET_KEY=secret-key
  DATABASE_URL=sqlite:///yourdatabase.db
  EMAIL_KEY=email
  PASSWORD_KEY=password


 ⚠️ .env is ignored by Git and should never be committed.


🧪 Local Setup Instructions

 1️⃣ Clone the repository

  bash
  git clone https://github.com/your-username/your-repo-name.git
  cd your-repo-name


 2️⃣ Create & activate virtual environment

  bash
  python -m venv .venv
  .venv\Scripts\activate    Windows


 3️⃣ Install dependencies

  bash
  pip install -r requirements.txt


 4️⃣ Run the app

 bash
 python main.py


Visit:

http://127.0.0.1:5000


🌍 Deployment on Render

 ✔ Requirements for Render

 GitHub repository connected
 PostgreSQL service created
 Environment variables added via Render dashboard

 🔹 Start Command

   bash
   gunicorn main:app
   

 🔹 Runtime
    
   python-3.11.8
   

🐘 PostgreSQL Setup (Render)

  1. Create a PostgreSQL service on Render
  2. Copy the Internal Database URL
  3. Add it to Web Service → Environment Variables:

   
DATABASE_URL=postgresql://...
   

🔒 Security Practices

   Secrets managed using environment variables
   .env  excluded using  .gitignore 
   No credentials hardcoded in source code


🧠 Key Learnings from This Project

   Virtual environment management
   Flask production deployment
   PostgreSQL integration
   Render cloud deployment
   Environment-based configuration
   Debugging Gunicorn & Python version issues


📌 Future Improvements

   Admin dashboard
   Comments system
   Image uploads
   Pagination
   Docker support
  

👨‍💻 Author

   oxyeyes
   Software Developer | Flask | Backend | Deployment Enthusiast


⭐ If you like this project

  Give it a ⭐ on GitHub — it motivates learning and improvement!



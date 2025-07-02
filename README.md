# 📝 MyTodo – Flask Web App

**MyTodo** is a sleek and minimal to-do list manager built with **Flask** and **Bootstrap 5**. It provides essential task management features with user authentication, making it perfect for personal productivity.

## 🚀 Live Demo

👉 Try it out: [https://todo-web-app-1.onrender.com](https://todo-web-app-1.onrender.com)

---

## ✅ Features

* 🔐 **User Authentication** – Sign up, log in, and manage your own todos securely
* ➕ **CRUD Operations** – Add, edit, and delete your tasks
* 🔍 **Search Functionality** – Find todos by title
* 🕒 **Timestamps** – Todos are time-tracked for better organization
* 📱 **Responsive UI** – Clean interface built with Bootstrap 5
* 💾 **SQLite with SQLAlchemy** – Lightweight database using ORM

---

## 📦 Requirements

* Python 3.7+
* Flask 3.x
* Virtual environment (recommended)

---

## 🛠️ Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/h8815/Flask-Todo-Webapp.git
   cd Flask-Todo-Webapp
   ```

2. **Set up a virtual environment**

   ```bash
   python -m venv venv
   # On macOS/Linux
   source venv/bin/activate
   # On Windows
   venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Usage (Local Development)

Run the development server:

```bash
flask run
```

Or, run directly using Python:

```bash
python app.py
```

Then open your browser and navigate to:
[http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 🚀 Deployment

This app is deployed on [Render](https://render.com) using [`render.yaml`](render.yaml).
To deploy your own version:

1. Push this repo to your GitHub account
2. Connect it to Render
3. Follow their [Python deployment guide](https://render.com/docs/deploy-flask)

---

## 📁 Project Structure

```
Flask-Todo-Webapp/
│
├── app.py                # Main application
├── requirements.txt      # Dependencies
├── render.yaml           # Deployment config (Render)
│
├── templates/            # HTML templates (Jinja2)
├── static/               # CSS & static assets
└── instance/
    └── todo.db           # SQLite database (auto-generated)
```
---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
Feel free to use, modify, and distribute it for your own projects.

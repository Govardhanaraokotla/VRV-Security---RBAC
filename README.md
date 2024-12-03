# 🌟 Django Authentication System with RBAC

Welcome to the **Django Authentication System** with Role-Based Access Control (RBAC)! This project implements user authentication, registration, and a personalized dashboard using Django.

---

## 🚀 Features

- 🛡️ **User Authentication**: Secure login and logout functionality.
- ✍️ **User Registration**: Allow new users to sign up.
- 🎨 **Responsive UI**: Bootstrap-styled pages for a clean, modern look.
- 🗄️ **Role-Based Access Control (RBAC)**: Redirect users based on authentication status.
- 🔒 **Secure Sessions**: Built-in CSRF protection and session management.

---

## 📁 Project Structure

```plaintext
├── auth_rbac
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
├── users
│   ├── migrations
│   ├── templates
│   │   ├── index.html
│   │   ├── register.html
│   │   ├── login.html
│   │   └── dashboard.html
│   ├── views.py
│   ├── models.py
│   └── urls.py
└── manage.py
```

---

## 🛠️ Setup Instructions

### 1️⃣ Install Dependencies
Ensure you have Python and Django installed.

```bash
pip install django
```

### 2️⃣ Run Migrations
Apply the initial migrations to set up the database.

```bash
python manage.py migrate
```

### 3️⃣ Start the Server
Run the development server to launch the application.

```bash
python manage.py runserver
```

### 4️⃣ Access the Application
Open your browser and navigate to:

- 🌐 Home: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
- 🔐 Login: [http://127.0.0.1:8000/login/](http://127.0.0.1:8000/login/)
- 📝 Register: [http://127.0.0.1:8000/register/](http://127.0.0.1:8000/register/)

---

## 📜 Routes

- `/` - Home Page
- `/login/` - User Login
- `/register/` - User Registration
- `/dashboard/` - User Dashboard
- `/logout/` - User Logout

---

## 🎨 Screenshots

### 🏠 Home Page
![Home Page](https://via.placeholder.com/800x400.png?text=Home+Page)

### 🔐 Login Page
![Login Page](https://via.placeholder.com/800x400.png?text=Login+Page)

### 📝 Registration Page
![Registration Page](https://via.placeholder.com/800x400.png?text=Registration+Page)

### 📊 Dashboard
![Dashboard](https://via.placeholder.com/800x400.png?text=Dashboard)

---

## 🤝 Contributing

We welcome contributions to improve this project! Follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

---

## 📝 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## ❤️ Acknowledgments

- Django for providing a robust framework.
- Bootstrap for the responsive and modern UI components.
- The open-source community for inspiration and tools.

---

Enjoy building with Django! 🎉


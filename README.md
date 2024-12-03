# 🌟 Flask Authentication System with RBAC

Welcome to the **Flask Authentication System** with Role-Based Access Control (RBAC)! This project implements user authentication, registration, and a personalized dashboard using Flask.

---

## 🚀 Features

- 🛡️ **User Authentication**: Secure login and logout functionality.
- ✍️ **User Registration**: Allow new users to sign up.
- 🎨 **Responsive UI**: Bootstrap-styled pages for a clean, modern look.
- 🗄️ **Role-Based Access Control (RBAC)**: Redirect users based on authentication status.
- 🔒 **Secure Sessions**: Built-in session management with Flask.

---

## 📁 Project Structure

```plaintext
├── app.py
├── static
│   └── styles.css
├── templates
│   ├── index.html
│   ├── register.html
│   ├── login.html
│   └── dashboard.html
└── requirements.txt
```

---

## 🛠️ Setup Instructions

### 1️⃣ Install Dependencies
Ensure you have Python and Flask installed.

```bash
pip install flask flask-bcrypt flask-sqlalchemy flask-wtf
```

### 2️⃣ Run the Application
Start the Flask development server.

```bash
python app.py
```

### 3️⃣ Access the Application
Open your browser and navigate to:

- 🌐 Home: [http://127.0.0.1:5000/](http://127.0.0.1:5000/)
- 🔐 Login: [http://127.0.0.1:5000/login](http://127.0.0.1:5000/login)
- 📝 Register: [http://127.0.0.1:5000/register](http://127.0.0.1:5000/register)

---

## 📜 Routes

- `/` - Home Page
- `/login` - User Login
- `/register` - User Registration
- `/dashboard` - User Dashboard
- `/logout` - User Logout

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

- Flask for providing a lightweight and flexible framework.
- Bootstrap for the responsive and modern UI components.
- The open-source community for inspiration and tools.

---

Enjoy building with Flask! 🎉


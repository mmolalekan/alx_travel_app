# alx_travel_app# ALX Travel App Project: Milestone 1

## 📌 About the Project

This project is the foundational milestone for a real-world Django-based travel application. The primary objective is to establish a robust and scalable backend by setting up the project structure, configuring the database, and integrating key developer tools. This milestone focuses on applying industry-standard best practices to ensure the application is production-ready from day one.

---

## 🎯 Learning Objectives

By completing this project, you will:

- **Master Advanced Project Initialization**: Learn to create and configure a Django project with modular settings and environment variable management for a secure and scalable setup.
- **Integrate Key Developer Tools**: Gain practical experience integrating **Swagger** for automated API documentation and setting up **CORS headers** for seamless API interactions.
- **Configure a Database**: Set up and connect to a **MySQL database**, handling credentials securely through environment variables.
- **Collaborate Effectively**: Practice project structuring and version control with Git, adopting a workflow that facilitates team collaboration.

---

## ⚙️ Requirements

To successfully complete this milestone, ensure you have the following prerequisites:

- Familiarity with **Django** and **Django REST Framework**.
- Knowledge of **MySQL** and database management.
- Understanding of **Git** for version control.
- A basic grasp of environment variable management using the `django-environ` package.

---

## 🚀 Key Highlights

### **Project Initialization**

- A new Django project named `alx_travel_app` has been created.
- A core application, `listings`, has been added to the project.

### **Dependency Management**

- Essential packages such as `djangorestframework`, `django-cors-headers`, `celery`, `rabbitmq`, and `drf-yasg` have been installed.

### **Settings Configuration**

- The project uses `django-environ` to manage sensitive data via a `.env` file.
- **MySQL** has been configured as the primary database.

### **Swagger Integration**

- `drf-yasg` has been set up to automatically generate API documentation, which is accessible at the `/swagger/` endpoint.

### **Version Control**

- The project is initialized as a Git repository, ready for collaboration and submission.

---

## 📂 Project Structure

├── alx_travel_app/
│ ├── listings/
│ ├── init.py
│ ├── settings.py
│ └── urls.py
└── .env
└── requirements.txt

---

## 🧑‍💻 How to Run

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/alx-travel-app/alx-travel-app.git](https://github.com/alx-travel-app/alx-travel-app.git)
    cd alx_travel_app
    ```
2.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3.  **Set up the database**:
    Create a `.env` file in the root directory and add your MySQL database credentials.
4.  **Run migrations and start the server**:
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    python manage.py runserver
    ```
5.  **View API documentation**:
    Navigate to `http://127.0.0.1:8000/swagger/` in your browser to view the interactive API documentation.

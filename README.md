# Third Django Project

A Django project created to practice creating a Django project, creating an application, handling web pages, and working with basic templates and static files.

## 📌 Project Overview

This is my third Django project created while learning Django web development.

The project was created using **Django 2.1.7**.

## 🛠️ Technologies Used

* Python
* Django 2.1.7
* SQLite
* HTML
* CSS
* GitHub

## 🚀 Step 1: Create the Django Project

Open Command Prompt and navigate to the Django directory:

```text
C:\Users\Administrator\Desktop\Django>
```

Create the project:

```bash
django-admin startproject thirdproject
```

Output:

```text
C:\Users\Administrator\Desktop\Django>django-admin startproject thirdproject
```

## 📂 Step 2: Open the Project

Move into the project directory:

```bash
cd thirdproject
```

Output:

```text
C:\Users\Administrator\Desktop\Django>cd thirdproject

C:\Users\Administrator\Desktop\Django\thirdproject>
```

## 🧩 Step 3: Create the Django Application

Create an application named `thirdapp`:

```bash
django-admin startapp thirdapp
```

Output:

```text
C:\Users\Administrator\Desktop\Django\thirdproject>django-admin startapp thirdapp
```

The application was created successfully.

## 📁 Project Structure

```text
thirdproject/
│
├── manage.py
│
├── thirdproject/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── ...
│
└── thirdapp/
    ├── __init__.py
    ├── admin.py
    ├── apps.py
    ├── models.py
    ├── tests.py
    ├── views.py
    └── migrations/
```

## ▶️ Step 4: Run the Development Server

Start the Django development server:

```bash
python manage.py runserver
```

### Server Output

```text
Performing system checks...

System check identified no issues (0 silenced).

You have 15 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
Run 'python manage.py migrate' to apply them.

August 15, 2026 - 23:20:13
Django version 2.1.7, using settings 'thirdproject.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
```

## 🌐 Step 5: Test the Website

Open the following URL in a web browser:

```text
http://127.0.0.1:8000/
```

The main page successfully returned:

```text
[15/Aug/2026 23:23:20] "GET / HTTP/1.1" 200 2529
```

Later, the page was successfully loaded again:

```text
[15/Aug/2026 23:25:14] "GET / HTTP/1.1" 200 2599
[15/Aug/2026 23:25:20] "GET / HTTP/1.1" 200 2599
```

HTTP status code **200** indicates that the request was successful.

## 🗄️ Database Migrations

Django reported:

```text
You have 15 unapplied migration(s).
```

These are Django's default migrations for:

* Admin
* Authentication
* Content Types
* Sessions

They can be applied using:

```bash
python manage.py migrate
```

## 📚 What I Learned

Through this project, I practiced:

* Creating a Django project
* Creating a Django application
* Understanding Django project structure
* Running the Django development server
* Working with web pages
* Testing URLs
* Understanding HTTP status codes
* Identifying `404 Not Found` errors
* Working with images and HTML pages
* Preparing a Django project for GitHub

## 🔮 Future Improvements

Future improvements for this project include:

* Fixing the missing `image.jpg`
* Creating a proper About page
* Adding URL routing
* Adding HTML templates
* Adding CSS styling
* Connecting the `thirdapp` application
* Creating Django models
* Adding database functionality
* Implementing CRUD operations

## 👨‍💻 Author

**Kammineni Venkata Manasa**

B.Tech – Computer Science and Engineering

## ⭐ Project Status

**Development / Learning Project**

This project is part of my journey to learn Django and Python web development.

![header](https://capsule-render.vercel.app/api?type=cylinder&color=0:16213e,100:0f3460&height=180&text=Python%20Web%20Programming&fontSize=20&fontColor=ffffff&desc=Django%20|%20Python%20|%20Digital%20Library%20|%20CRUD&descSize=15&descAlignY=75)

<p align="center">

<img src="https://img.shields.io/badge/Python-Backend-3776AB?style=for-the-badge&logo=python&logoColor=white"/>

<img src="https://img.shields.io/badge/Django-Web%20Framework-092E20?style=for-the-badge&logo=django&logoColor=white"/>

<img src="https://img.shields.io/badge/HTML/CSS-Frontend-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>

<img src="https://img.shields.io/badge/Domain-Library%20Management-blue?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"/>

</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

<p align="center">
  <a href="README.md">
    <img src="https://img.shields.io/badge/🇫🇷%20Français-2d6a4f?style=for-the-badge" alt="Version Française"/>
  </a>

  <a href="#">
    <img src="https://img.shields.io/badge/🇬🇧%20English-1d3557?style=for-the-badge" alt="English Version"/>
  </a>
</p>

# Executive Summary

*This project involved developing a digital library management web application using the Django framework in Python. The primary objective was to create a secure platform allowing users (managers and visitors) to interact with a book catalog. Key features include the creation, reading, updating, and deletion (CRUD) of books, as well as user and access management.*

### 🚀 Key Features

✔ Development of a secure web application with Django

✔ Comprehensive book management (add, edit, delete, view)

✔ User authentication and authorization system

✔ Distinction between manager and visitor roles

✔ Administration interface for data management

✔ Responsive user interface design

**Applied Skills:** Web Development, Python, Django, ORM, Databases, User Management, CRUD, HTML, CSS, Web Security.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 📌 Background

Developing robust and secure web applications is a critical skill in the fields of data analysis and data science, particularly for creating internal tools or showcasing projects. This project was conducted as part of a Professional License in Statistical Analysis, aiming to explore the capabilities of the Django web framework for implementing a digital library management system.

> 💡 **Problem Statement:**
>
> How to design and implement a functional and secure library management web application, capable of handling CRUD operations on books and distinguishing user roles (managers and visitors) using the Django framework?

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 🎯 Objectives

### General Objective

Develop a complete and secure digital library management web application with Django.

### Specific Objectives

- Set up a Django development environment.
- Design and implement data models for books and users.
- Develop CRUD functionalities for book management.
- Integrate an authentication and authorization system for different user types.
- Create an intuitive and responsive frontend user interface.
- Ensure application security and access management.
- Demonstrate the ability to use a web framework for development projects.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 🗂️ Data

<table>

<tr>

<td width="35%" valign="top">

<h3 align="center">Sources</h3>

| Element | Description |
|----------|------------|
| Data Type | Book information, User data |
| Database | SQLite (Django default), scalable to other RDBMS |
| Files | Book cover images |
| Environment | Local development |

</td>

<td width="65%" valign="top">

<h3 align="center">Selected Variables (`Book` Model)</h3>

| Variable | Description |
|-----------|------------|
| `title` | Title of the book |
| `author` | Author of the book |
| `pub_date` | Publication date |
| `image` | Cover image |
| `description` | Summary or description of the book |

</td>

</tr>

</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 🔬 Methodology

```text
Django Project Initialization
        │
        ▼
Model Design (ORM)
        │
        ▼
Backend Implementation (Views, URLs)
        │
        ▼
Frontend Development (HTML/CSS Templates)
        │
        ▼
Authentication & Authorization Management
        │
        ▼
CRUD Operations Integration
        │
        ▼
Testing & Local Deployment
```

### Steps Completed

#### 1. Project and Application Initialization

Setting up the virtual environment, installing Django, creating the `bibliotheque` project and the `booksApp` application.

#### 2. Data Model Design

Defining the `Book` model with its attributes (`title`, `author`, `pub_date`, `image`, `description`) and configuring the Django admin for these models.

#### 3. Backend Development

Implementing views (Python functions) and URLs to handle CRUD (Create, Read, Update, Delete) operations on books, as well as user authentication.

#### 4. Frontend Development

Creating HTML templates and CSS styles for various application pages: login page, home page, book display, and forms for adding, editing, and deleting.

#### 5. User and Access Management

Implementing an authentication system for managers and visitors, with distinct authorization levels for book management operations.

#### 6. Testing and Validation

Testing various functionalities to ensure proper operation and application security.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 🛠️ Technical Stack

<p align="center">

<img src="https://img.shields.io/badge/Python-Language-3776AB?style=flat-square&logo=python&logoColor=white"/>

<img src="https://img.shields.io/badge/Django-Web%20Framework-092E20?style=flat-square&logo=django&logoColor=white"/>

<img src="https://img.shields.io/badge/SQLite-Database-003B57?style=flat-square&logo=sqlite&logoColor=white"/>

<img src="https://img.shields.io/badge/HTML5-Web%20Structure-E34F26?style=flat-square&logo=html5&logoColor=white"/>

<img src="https://img.shields.io/badge/CSS3-Web%20Style-1572B6?style=flat-square&logo=css3&logoColor=white"/>

</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 📊 Results

The developed web application is functional and allows for complete management of a digital library. The main interfaces and features are presented below.

## Visualizations

### Login Page

![alt text](media/image-1.png)

### Home Page (Visitor)

![alt text](media/image-2.png)

### Book Catalog Exploration

![alt text](media/image-3.png)

### Add Book Form

![alt text](media/image-5.png)

### Edit Book Form

![alt text](media/image-4.png)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 💡 Interpretation

The project successfully demonstrates the ability to build a complete web application using the Django framework. The distinction between user roles (managers and visitors) is well-implemented, providing access levels and features tailored to each profile. CRUD operations on books are functional, allowing for efficient catalog management. The user interface, while simple, is intuitive and allows for smooth navigation.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 🌍 Potential Impact

This project strengthened skills in web development with Python and Django, which are essential for creating custom tools or participating in larger-scale projects. It illustrates the capacity to:

- Design and implement secure web architectures.
- Manage databases via an ORM.
- Develop functional user interfaces.
- Apply iterative development principles.
- Contribute to projects requiring full-stack development skills.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# ⚠️ Limitations

> [!WARNING]
>
> The application is a functional prototype and could be improved in terms of UI/UX design, advanced features (search, filters, pagination), and robustness (error handling, unit testing).

> [!WARNING]
>
> Application deployment is currently limited to a local environment. Production deployment would require additional configurations (web server, production database, enhanced security).

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 🧠 Skills Developed

| Domain | Skills |
|----------|------------|
| Web Development | Django, Python, HTML, CSS |
| Databases | Data Modeling, Django ORM, SQLite |
| Project Management | Design, Implementation, Testing |
| Web Security | Authentication, Authorization |
| Programming | Python (Advanced) |
| Frontend | Template Integration, Responsive Design |

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 👥 Team & Supervision

## Developed by

<table align="center">

<tr>

<td align="center">

<b>SAWADOGO Oriane-Aurele</b><br/>
<sub>Professional License in Statistical Analysis</sub>
<br/>

<a href="[YOUR_GITHUB_LINK_SAWADOGO]">

<img src="https://img.shields.io/badge/GitHub-profile-181717?style=flat-square&logo=github"/>

</a>
</td>

<td align="center">

<b>YAMEOGO Saïdou</b><br/>
<sub>Professional License in Statistical Analysis</sub><br/>

<a href="[YOUR_GITHUB_LINK_YAMEOGO]">

<img src="https://img.shields.io/badge/GitHub-profile-181717?style=flat-square&logo=github"/>

</a>

</td>

</tr>

</table>

## Supervision

<table align="center">

<tr>

<td align="center">

<b>Dr. Ousmane BARA</b><br/>
<sub>Professor</sub><br/>
<sub>Higher Institute of Population Sciences (ISSP)</sub><br/>
<sub>Joseph Ki-Zerbo University · Burkina Faso 🇧🇫</sub>

</td>

</tr>

</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 📁 Project Structure

```text
📦 my_library_project/
├── README.md
├── README_EN.md
├── Rapport.pdf
├── manage.py
├── bibliotheque/           # Main Django project
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── booksApp/               # Django application for books
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── templates/              # Frontend HTML files
│   ├── base.html
│   ├── login.html
│   ├── home.html
│   └── about.html
├── static/                 # Static files (CSS, JS, images)
│   ├── css/
│   ├── js/
│   └── images/
└── media/                  # Uploaded files (book images)
```

## 🔧 Installation

### Prérequis
```bash
Python 3.8+
pip
```

### Installation
```bash
# Cloner le repository
git clone [url-du-repo]

# Créer un environnement virtuel
python -m venv venv
source venv/bin/activate  # Linux/Mac
# ou
venv\Scripts\activate     # Windows

# Installer les dépendances
pip install -r requirements.txt

# Appliquer les migrations
python manage.py migrate

# Créer un superutilisateur
python manage.py createsuperuser

# Lancer le serveur
python manage.py runserver
```

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 📄 Read the Report

<p align="center">

![Report Cover](media/image.png)

</p>

<p align="center">

<a href="documents/rapport.pdf">

<img src="https://img.shields.io/badge/Read%20the%20Report-PDF-red?style=for-the-badge&logo=adobeacrobatreader&logoColor=white"/>

</a>

</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 📚 References

- Django Official Documentation. *The Web framework for perfectionists with deadlines.* [YOUR_LINK_DJANGO_DOC]
- Python Software Foundation. *Python Documentation.* [YOUR_LINK_PYTHON_DOC]
- W3C. *HTML and CSS Standards.* [YOUR_LINK_HTML_CSS_DOC]

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

<p align="center">
  <sub>Project completed as part of the Professional License in Statistical Analysis at the Higher Institute of Population Sciences (ISSP), Joseph Ki-Zerbo University, Burkina Faso.</sub>
</p>

![footer](https://capsule-render.vercel.app/api?type=waving\&color=0:16213e,100:0f3460\&height=100\&section=footer)

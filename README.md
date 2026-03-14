# 📝 Flask Blog Application

A simple blog web application built using Flask where users can create, edit, view, and delete blog posts. The application uses a SQLite database with SQLAlchemy ORM and provides a rich text editor using CKEditor.

---

## 🚀 Features

* Create new blog posts
* View all blog posts on the homepage
* Read individual blog posts
* Edit existing blog posts
* Delete blog posts
* Rich text editor for writing blog content
* SQLite database integration
* Responsive UI using Bootstrap

---

## 🛠 Tech Stack

* **Python**
* **Flask**
* **Flask-Bootstrap**
* **Flask-WTF**
* **Flask-SQLAlchemy**
* **Flask-CKEditor**
* **SQLite**
* **Jinja2 Templates**

---

## 📂 Project Structure

```
flask-blog/
│
├── main.py
├── posts.db
│
├── templates/
│   ├── index.html
│   ├── post.html
│   ├── make-post.html
│   ├── about.html
│   └── contact.html
│
├── static/
│   ├── css/
│   ├── js/
│   └── assets/
│
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```
git clone [https://github.com/your-username/flask-blog.git](https://github.com/ap-00007/Blog-capstone.git)
cd flask-blog
```

### 2. Create a virtual environment

```
python -m venv venv
```

Activate it:

Mac/Linux

```
source venv/bin/activate
```

Windows

```
venv\Scripts\activate
```

### 3. Install dependencies

```
pip install flask flask-bootstrap flask-wtf flask-sqlalchemy flask-ckeditor
```

---

## ▶️ Running the Application

Run the Flask server:

```
python main.py
```

The application will start on:

```
http://localhost:5003
```

---

## 📊 Database

The application uses **SQLite** as the database.

Table: `BlogPost`

Fields:

* `id`
* `title`
* `subtitle`
* `date`
* `body`
* `author`
* `img_url`

The database is automatically created when the app starts.

---

## ✍️ Blog Functionalities

### Create Post

Navigate to:

```
/new-post
```

### View Post

```
/post/<post_id>
```

### Edit Post

```
/edit-post/<post_id>
```

### Delete Post

```
/delete/<post_id>
```

---

## 📸 Screens

* Home page displaying all blog posts
* Individual blog post page
* Post creation page with rich text editor
* Edit post page

---

## 🔒 Environment Configuration

Make sure to set a secure secret key in production:

```
app.config['SECRET_KEY'] = 'your-secret-key'
```

---

## 📚 Learning Purpose

This project demonstrates:

* Flask routing
* Template rendering with Jinja2
* Database integration using SQLAlchemy
* Form handling with Flask-WTF
* Rich text editing with CKEditor
* CRUD operations

---

## 👨‍💻 Author

Ashish Panda

---

## ⭐ Future Improvements

* User authentication (login/register)
* Comment system
* Tags and categories
* Image uploads
* Pagination
* Admin dashboard

---

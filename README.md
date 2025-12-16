# 🎬 MoviesNow

**Course:** ISM6225 – Distributed Information Systems
**Semester:** Spring 2023
**Project Type:** Team Academic Project
**Framework:** Flask (Python)

---

## 📌 Project Overview

**MoviesNow** is a team-developed web-based movie and TV show streaming platform created as part of the **Distributed Information Systems (ISM6225)** course. The project applies distributed system principles such as **client–server architecture, centralized data storage, and scalable web application design**.

The application enables users to register, log in, browse movies and TV shows, explore genres, view detailed content information, and interact with visual analytics. The platform is designed to be responsive and accessible across multiple devices.

---

## 🎯 Project Objectives

* Design and implement a distributed web application using Flask
* Apply client–server communication and centralized data management
* Build a responsive, user-friendly interface
* Demonstrate separation of concerns between frontend, backend, and database layers

---

## ✨ Features

* 🔐 User authentication (Login & Registration)
* 🎥 Browse movies and TV shows
* 📄 Detailed movie and show information pages
* 🎭 Genre-based navigation
* 📊 Data visualization using charts
* 📱 Responsive UI using HTML, CSS, and JavaScript
* 🗄️ SQLite database for persistent storage

---

## 🏗️ System Architecture

* **Frontend:** HTML, CSS, JavaScript (Jinja Templates)
* **Backend:** Python Flask
* **Database:** SQLite (`database.db`)
* **Architecture Pattern:** Client–Server Model

The Flask backend manages routing, authentication, and database interactions, while the frontend dynamically renders content using Jinja templates.

---

## 📁 Project Structure

```
MoviesNow-main/
│
├── app.py                  # Main Flask application
├── database.db             # SQLite database
├── instance/
│   └── database.db         # Application instance database
│
├── templates/              # HTML templates
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── about.html
│   ├── moviesPage.html
│   ├── Product.html
│   └── Chart.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   ├── script.js
│   │   ├── script-product.js
│   │   └── Chart.js
│   └── images/
│       └── icons/
│
└── Readme.txt
```

---

## 🚀 How to Run the Application

### 1️⃣ Prerequisites

* Python 3.x
* Flask

### 2️⃣ Install Flask

```bash
pip install flask
```

### 3️⃣ Run the Application

```bash
python app.py
```

### 4️⃣ Access the Application

Open your browser and navigate to:

```
http://127.0.0.1:5000/
```

---

## 📊 Distributed Systems Concepts Demonstrated

* Client–Server communication
* Centralized database access
* Stateless HTTP request handling
* Separation of frontend and backend responsibilities
* Scalability-ready web architecture

---

## 🎓 Learning Outcomes

* Collaboratively built a distributed web application using Flask
* Implemented authentication and session handling
* Designed dynamic, data-driven web pages using Jinja templates
* Applied distributed information system concepts to a real-world use case
* Integrated frontend, backend, and database layers as a unified system

---

## 👥 Team Members

* **Dhanunjan Reddy Raghuram**
* *Other team members (add names here if applicable)*

**Program:** Business Analytics & Information Systems
**University:** University of South Florida

📧 Email: [raghuramdhanunjanreddy@gmail.com](mailto:raghuramdhanunjanreddy@gmail.com)
🔗 LinkedIn: [linkedin.com/in/dhanunjan-reddy-raghuram](https://www.linkedin.com/in/dhanunjan-reddy-raghuram)

---

## 📜 License

This project was developed for academic purposes as part of
**ISM6225 – Distributed Information Systems (Team Project)**.



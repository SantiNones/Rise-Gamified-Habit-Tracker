# 🚀 RISE: Gamified Habit Tracker & Personal Development Plan

> **Transform your daily routine into an RPG game. Build habits, track tasks, and grow alongside a community.**

![Project Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-blue)

## 📖 About the Project

**RISE** is a full-stack web application designed to bridge the gap between productivity and motivation. Leveraging principles of **behavioral psychology**, RISE turns the mundane task of habit tracking into an engaging, gamified experience.

Users can create tasks, track daily habits, and earn "experience points" (XP) to level up their profile. The platform also includes a social component, allowing users to share achievements and foster a sense of accountability.

### 💡 Why we built this?
With a background in **Psychology**, I have always been fascinated by human behavior and motivation. We built RISE to apply technical skills in **React and Python** to solve a real-world problem: consistency. This project represents our transition into Full-Stack Development, combining user-centric design with robust backend logic.

---

## ✨ Key Features

* **🎮 Gamification Engine:** Earn XP for completing tasks and maintaining streaks. Level up your profile as you improve your real life.
* **✅ Habit & Task Management:** Create, edit, and delete daily habits and one-time tasks.
* **📊 Progress Tracking:** Visual indicators of your consistency and growth.
* **🤝 Social Feed:** A community space to share milestones and encourage peer accountability.
* **🔐 Secure Authentication:** User registration and login system with encrypted passwords.

---

## 🛠️ Tech Stack

This project was built using the **PERN/MERN** stack philosophy, utilizing Python for the backend.

### Frontend
* ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) **React.js**: Context API for state management.
* ![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=flat&logo=bootstrap&logoColor=white) **Bootstrap 5**: For responsive and modern styling.
* **HTML5 & CSS3**

### Backend
* ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) **Python 3**: Core logic.
* ![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white) **Flask**: RESTful API development.
* ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-black?style=flat&logo=python&logoColor=white) **SQLAlchemy**: ORM for database management.
* **PostgreSQL**: Relational database (Production).
* **JWT**: For secure authentication.

---

## 📸 Screenshots

*(Add screenshots of your app here to make it visual!)*

| Dashboard View | Mobile Responsiveness |
|:---:|:---:|
| ![Dashboard Placeholder](https://via.placeholder.com/400x200?text=Dashboard+View) | ![Mobile Placeholder](https://via.placeholder.com/200x400?text=Mobile+View) |

---

## 💻 Installation & Local Setup

If you want to run this project locally, follow these steps:

**1. Clone the repository**
```bash
# Enter the backend directory (adjust name if different, e.g., src/api)
cd src
pipenv install
pipenv shell

# Create the database and run migrations
pipenv run migrate
pipenv run upgrade

# Start the server
pipenv run start

# Enter the frontend directory (adjust name if different)
cd src/front
npm install
npm run start

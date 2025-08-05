# 📝 Digital Diary Web App

A simple and secure personal diary web application built with PHP and MySQL.  
Allows users to register, log in, and write, view, or update their private diary entries online.

---

## 🌐 Overview

The **Digital Diary Web App** is designed for individuals who want a minimal yet functional platform to jot down personal thoughts and reflections securely. The system includes authentication, session handling, and CRUD features for diary entries, all implemented with native PHP and MySQL.

> Built with simplicity in mind – no heavy frameworks, just clean and functional code.

---

## 🚀 Features

- 🛡️ User Registration & Login (with session-based authentication)
- 📖 Create, Read, Update diary entries
- 🔒 Private and user-specific access control
- 🎨 Clean interface using HTML, CSS, and Bootstrap
- 🗃️ Data persistence with MySQL
- 🧰 XAMPP-compatible for local deployment

---

## 🛠️ Tech Stack

| Layer         | Technology      |
|---------------|-----------------|
| Frontend      | HTML, CSS, Bootstrap |
| Backend       | PHP (Vanilla)   |
| Database      | MySQL           |
| Local Server  | XAMPP / Apache  |

---

## 💻 How to Run Locally

### 🔧 Prerequisites
- [XAMPP](https://www.apachefriends.org/index.html) installed on your system
- PHP 7.x or later

### 🛠️ Setup Instructions

1. **Import the Database**
   - Open `phpMyAdmin`
   - Create a database: `digital_diary`
   - Import the SQL file `digital_diary.sql` (provided in the repo)

2. **Start the Server**
   - Launch **Apache** and **MySQL** from the XAMPP Control Panel
   - Navigate to [http://localhost/digital_diary/login.php](http://localhost/digital_diary/login.php)

3. **Log in / Register**
   - Use the registration page to create a new user
   - You can now log in and start writing your diary!

---

## 🧠 What I Learned

- Building secure authentication systems in PHP
- Connecting and querying MySQL databases with `mysqli`
- Structuring a basic CRUD-based web application
- Styling clean interfaces with vanilla HTML/CSS
- Setting up and managing local servers with XAMPP

---

## 🔐 License

This project is for educational and demonstration purposes only.  
No data encryption or advanced security mechanisms are implemented.

---

## 🙏 Acknowledgements

- Bootstrap CSS framework for styling
- XAMPP for local development environment


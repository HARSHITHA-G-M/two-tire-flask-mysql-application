# 🌟 Two-Tier Flask + MySQL Application  

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python&logoColor=white)  
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black?logo=flask)  
![MySQL](https://img.shields.io/badge/MySQL-Database-orange?logo=mysql)  
![Docker](https://img.shields.io/badge/Docker-Containerization-blue?logo=docker)  
![License](https://img.shields.io/badge/License-MIT-green)  

---

## 🎯 **Overview**

This is a simple **Two-Tier Web Application** built using:  
✅ **Flask** (Python) → Application Layer  
✅ **MySQL** → Database Layer  

It’s containerized using **Docker** for easy deployment.  
The app allows users to **submit messages** and **view all stored messages**.

---

## 📂 **Project Structure**

```bash
two-tire-flask-mysql-application/
├── Dockerfile             # Flask app container image
├── docker-compose.yml     # Orchestrates Flask + MySQL containers
├── app.py                 # Main Flask app
├── message.sql            # DB initialization script
├── requirements.txt       # Python dependencies
└── templates/
    └── index.html         # Frontend template


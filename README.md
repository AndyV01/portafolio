# 🌐 Personal Portfolio – Andrés Vallarino

![CI](https://github.com/AndyV01/portafolio/actions/workflows/ci.yml/badge.svg)

Personal portfolio website built with **HTML, CSS and JavaScript**, showcasing my profile, skills and projects.  
The project includes a **CI/CD pipeline implemented with GitHub Actions**, simulating a real-world development workflow.

🔗 **Live Demo**: https://andyv01.github.io/portafolio/

---

## 📌 About the Project

This portfolio was created as a lightweight static web application to present my professional profile as a **Frontend / Full-Stack Developer (React-focused)**.

Although the project does not rely on frameworks or package managers, it follows **modern development practices**, including automated validation, continuous integration and continuous deployment.

---

## 🚀 Features

- Responsive layout
- Clean and semantic HTML structure
- Custom CSS styling
- Vanilla JavaScript interactions
- Automated CI/CD pipeline
- Automatic deployment to GitHub Pages

---

## 🛠️ Tech Stack

**Frontend**
- HTML5
- CSS3
- JavaScript (ES6+)

**DevOps / CI-CD**
- GitHub Actions
- GitHub Pages

**Tools**
- Git
- GitHub

---

## 🔄 CI/CD Pipeline

This repository includes a **CI/CD pipeline** configured with **GitHub Actions**.

### Pipeline Overview

The pipeline runs automatically on:
- Push to `main`
- Pull Requests to `main`

### Pipeline Stages

1. **Build & Validation**
   - Repository checkout
   - Project structure validation
   - Basic HTML integrity checks

2. **Automated Tests (Simulated)**
   - File existence checks
   - HTML tag validation

3. **Deployment**
   - Automatic deployment to **GitHub Pages**
   - Deployment only occurs if all previous steps pass

This setup simulates a real CI/CD workflow used in production environments, even for a static project.

---

## 📂 Project Structure

/
├── index.html
├── style.css
├── script.js
├── assets/
├── .github/
│ └── workflows/
│ └── ci.yml
└── README.md
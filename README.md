# Portfolio – Andrés Vallarino

Personal frontend portfolio showcasing projects and skills using HTML, CSS and JavaScript.

## 🚀 Live Demo
https://andyv01.github.io/portafolio/

## 🛠️ Tech Stack
- HTML5
- CSS3
- JavaScript (Vanilla)
- Git & GitHub
- GitHub Actions (CI/CD)

---

## ⚙️ CI/CD Pipeline

This project includes a Continuous Integration and Deployment (CI/CD) pipeline implemented with **GitHub Actions**.

### 🔍 Continuous Integration (CI)

On every push or pull request to the `main` branch, the pipeline automatically:

- Validates all HTML files using **html-validate**
- Lints CSS files using **Stylelint**
- Performs basic JavaScript linting using **ESLint**
- Checks required project structure and files

This ensures code quality and prevents broken changes from being merged.

### 🚀 Continuous Deployment (CD)

After successful validation:
- The site is automatically deployed to **GitHub Pages**
- Deployment runs only if all CI checks pass

---

## 📂 Project Structure

```text
/
├── index.html
├── css/
│   └── style.css
├── images/
├── js/
└── .github/
    └── workflows/
        └── ci-cd.yml
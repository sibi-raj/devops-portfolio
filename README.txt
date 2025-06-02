# 🚀 DevOps Portfolio - Static Site CI/CD

This repository hosts a personal **static portfolio website** built with HTML, CSS, and JavaScript. It demonstrates a basic **CI/CD pipeline** using **GitHub Actions** to automatically deploy the site to **GitHub Pages** on every push to the `main` branch.

---

## 📦 Project Structure

- `index.html` – Main HTML file (home page)
- `assets/` – CSS, JavaScript, fonts, etc.
- `.github/workflows/deploy.yml` – GitHub Actions workflow for CI/CD

---

## 🔁 CI/CD Pipeline (GitHub Actions)

On every push to the `main` branch, the following steps are executed automatically:

1. **Checkout Code**  
   Retrieves the latest code from the repository.

2. **Setup Node.js**  
   Uses Node.js to run HTML linting.

3. **HTML Linting** *(Optional but good practice)*  
   Lints HTML files using [`htmlhint`](https://github.com/htmlhint/HTMLHint) to catch syntax or formatting issues.

4. **Deploy to GitHub Pages**  
   Uses [`peaceiris/actions-gh-pages`](https://github.com/peaceiris/actions-gh-pages) to deploy the site from the repo root (`./`) to GitHub Pages.

---

## ✅ Deployment Status

🌐 **Live Website**:  
[https://sibi-raj.github.io/devops-portfolio/](https://sibi-raj.github.io/devops-portfolio/)

---

## ⚙️ Requirements

- GitHub repository with GitHub Pages enabled (main branch / root).
- `deploy.yml` CI/CD workflow in `.github/workflows/`.
- Basic knowledge of Git and version control.

---

## 📄 License

Template by [HTML5 UP](https://html5up.net/) – Free for personal and commercial use under the CCA 3.0 license.  
Demo images are from [Unsplash](https://unsplash.com/).

---

## 🙌 Acknowledgments

- [GitHub Actions](https://github.com/features/actions)
- [HTMLHint](https://htmlhint.com/)
- [Peaceiris GitHub Pages Action](https://github.com/peaceiris/actions-gh-pages)
- [HTML5 UP – Story Template](https://html5up.net/story)

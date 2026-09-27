# My Portfolio Website

A personal portfolio website built with HTML/CSS, deployed automatically to GitHub Pages using a CI/CD pipeline built with GitHub Actions.

🔗 **Live site:** https://rmmonish.github.io/my-portfolio/

## What this project demonstrates

- **Frontend:** Static website built with HTML and CSS
- **Version Control:** Git for tracking all code changes
- **CI/CD:** A GitHub Actions workflow (`.github/workflows/deploy.yml`) that automatically builds and deploys the site to GitHub Pages on every push to `main`
- **Hosting:** Free static hosting via GitHub Pages

## How the pipeline works

1. Code is pushed to the `main` branch
2. GitHub Actions automatically triggers
3. The workflow checks out the code, packages it, and deploys it to GitHub Pages
4. Site is live within ~1 minute — no manual deployment steps required

## Tech Stack

| Layer | Tool |
|---|---|
| Frontend | HTML, CSS |
| Version Control | Git & GitHub |
| CI/CD | GitHub Actions |
| Hosting | GitHub Pages |

## Run locally

Clone the repo and open `index.html` in any browser:

​```
git clone https://github.com/rmmonish/my-portfolio.git 
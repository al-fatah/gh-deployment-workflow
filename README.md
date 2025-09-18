# GitHub Pages Deployment with GitHub Actions

This repository demonstrates how to deploy a simple static website to **GitHub Pages** using **GitHub Actions**.

## Project Goal
The goal is to understand the basics of **CI/CD** by writing a workflow that deploys changes to `index.html` automatically.

## Features
- Deploys to GitHub Pages.
- Only triggers when `index.html` changes.
- Uses GitHub Actions for automation.

## Repository Structure
- `index.html` → Static site content.
- `.github/workflows/deploy.yml` → GitHub Actions workflow file.
- `README.md` → Project explanation.

## GitHub Pages URL
Once deployed, the site will be available at:
https://al-fatah.github.io/gh-deployment-workflow/

## Stretch Goal
You can extend this by using a static site generator (Hugo, Jekyll, Astro, etc.) to build a more complex website.

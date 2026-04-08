# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.



# CI/CD Pipeline for React Application using GitHub Actions

## Project Overview
This project demonstrates how to set up a CI/CD pipeline for a React application built with Vite using GitHub Actions. The pipeline automates the process of installing dependencies, building the application, and validating the code whenever changes are pushed to the repository.

## Features
- React application setup using Vite
- Automated CI pipeline with GitHub Actions
- Trigger on push / pull request
- Dependency installation using npm
- Build validation for deployment readiness
- Structured project for frontend CI/CD learning

## Tech Stack
- React
- Vite
- GitHub Actions
- YAML
- Node.js
- npm

## CI/CD Workflow
The GitHub Actions workflow performs the following steps:
1. Checks out the repository
2. Sets up Node.js environment
3. Installs project dependencies
4. Runs build command
5. Validates successful build execution

## Project Structure
```bash
react-cicd-pipeline/
│
├── .github/
│   └── workflows/
│       └── main.yml
├── public/
├── src/
├── package.json
├── vite.config.js
└── README.md

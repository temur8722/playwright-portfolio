# Playwright Automation Framework 🚀

[![Playwright](https://img.shields.io/badge/tested%20with-Playwright-45ba4b?logo=microsoft-playwright&logoColor=white)](https://playwright.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)](https://nodejs.org/)
[![GitHub Actions](https://img.shields.io/github/actions/workflow/status/temur8722/playwright-portfolio/playwright.yml?branch=main&logo=github-actions&logoColor=white)](https://github.com/temur8722/playwright-automation-framework/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Repo Size](https://img.shields.io/github/repo-size/temur8722/playwright-automation-framework)](https://github.com/temur8722/playwright-automation-framework)
[![Stars](https://img.shields.io/github/stars/temur8722/playwright-automation-framework?style=social)](https://github.com/temur8722/playwright-automation-framework/stargazers)

---

## 📖 Overview
This repository contains a scalable end-to-end automation framework built with [Playwright](https://playwright.dev/) and TypeScript.  

It is designed as a **portfolio project** to demonstrate industry best practices in **test automation architecture**, including Page Object Model, fixtures, API + UI testing, reporting, and CI/CD integration.

---

## 📌 Features
- ✅ Page Object Model (POM) and reusable component objects  
- ✅ UI and API testing with Playwright  
- ✅ Data-driven test design (JSON/CSV)  
- ✅ Parallel execution & sharding for faster suites  
- ✅ Custom reporting (HTML + Allure)  
- ✅ CI/CD integration with GitHub Actions  
- ✅ Dockerized test runs for portability  

---

## 🛠️ Tech Stack
- **Language:** TypeScript (Node.js)  
- **Test Runner:** Playwright Test  
- **CI/CD:** GitHub Actions  
- **Reporting:** Playwright HTML + Allure Reports  
- **Containerization:** Docker (optional)  

---

## 📂 Project Structure
playwright-automation-framework/
```├── tests/ # Test specs (smoke, regression, api)
├── pages/ # Page Object Model classes
├── fixtures/ # Custom fixtures (auth, data, etc.)
├── config/ # Configurations (environments, reporters)
├── reports/ # Generated test reports
├── package.json
├── playwright.config.ts
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/<your-username>/playwright-automation-framework.git
cd playwright-automation-framework
```
### 2. Install dependencies
```bash
npm install
```
### 3. Run tests
Run all tests:
```bash
npx playwright test
```
Run smoke tests only:
```bash
npx playwright test --grep @smoke
```

## 📊 Reporting
After a test run, open the HTML report:
```bash
npx playwright show-report
```
Example CI/CD run artifacts include:

HTML reports

Screenshots

Videos

Traces

⚙️ CI/CD (GitHub Actions)

GitHub Actions workflow runs:

✅ Smoke tests on every push/PR

✅ Full regression suite nightly

✅ Stores reports and traces as artifacts

# playwright-portfolio
“End-to-end test automation framework built with Playwright + TypeScript, showcasing framework design, fixtures, CI/CD, and reporting.”

# Playwright Automation Framework 🚀

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
├── tests/ # Test specs (smoke, regression, api)
├── pages/ # Page Object Model classes
├── fixtures/ # Custom fixtures (auth, data, etc.)
├── config/ # Configurations (environments, reporters)
├── reports/ # Generated test reports
├── package.json
├── playwright.config.ts
└── README.md


---

## 🚀 Getting Started

1. Clone the repo
```bash
git clone https://github.com/<your-username>/playwright-automation-framework.git
cd playwright-automation-framework

2. Install dependencies
npm install

3. Run tests:
npx playwright test
Run smoke tests only:
npx playwright test --grep @smoke

📊 Reporting

After a test run, open the HTML report:

npx playwright show-report


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
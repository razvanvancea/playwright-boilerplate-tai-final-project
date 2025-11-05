# Playwright Boilerplate - Final Project  

This is the final project for the **Test Automation Incubator** program:  
👉 [https://tai.razvanvancea.ro/](https://tai.razvanvancea.ro/)

The project is built using **Playwright** and includes several types of automated tests, covering different aspects of a web application.

---

## 🧪 Test Types

The following test types are included in this project:

- **E2E tests** – full end-to-end flows  
- **Visual tests** – screenshot comparison inside a Docker container  
- **API tests** – automated checks for backend endpoints  
- **Accessibility tests** – verify accessibility compliance (a11y)

---

## ⚙️ Prerequisites

Before running the tests, make sure you have the following installed:

- [Node.js](https://nodejs.org/) **v20** or above  
- **npm** (comes with Node.js)  
- **git**  
- **Google Chrome** browser  

---

## 📦 Installation

Clone the repository and install dependencies:

```bash
npm install


## 🧪 Running tests

# Run E2E tests in headless mode
npm run test

# Run E2E tests in headed mode (browser UI visible)
npm run test:headed

# Run visual regression tests (inside Docker)
npm run test:visual

# Run accessibility (a11y) tests
npm run test:a11y

# Run API tests
npm run test:api


# Cypress TypeScript E2E Tests with CI pipeline

*Created for educational use as part of 'Automated tests in CI' (CanTest IT) training.*

## Overview

This repository showcases end-to-end (E2E) automated testing using [Cypress](https://www.cypress.io/) with TypeScript.  
It was created as a playground for UI/integration testing and to learn CI pipeline integration.

## Features

- Sample E2E tests with Cypress and TypeScript
- Publishing Allure report on GH Pages after CI tests run

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Setup Instructions

1. **Clone the repository:**
    ```
    git clone https://github.com/gomczak/cypress-ts.git
    cd cypress-ts
    ```

2. **Install dependencies:**
    ```
    npm install
    ```

3. **(Recommended: For isolated Node environments, use [nvm](https://github.com/nvm-sh/nvm) to manage node versions.)**

### Running Tests

- **Run tests in interactive (GUI) mode:**
    ```
    npx cypress open
    ```
- **Run tests in headless (CLI) mode:**
    ```
    npx cypress run
    ```

Test results will be displayed in the terminal (for CLI runs) or in the Cypress GUI.

## Continuous Integration

> *Note: there is **no CI/CD integration** (e.g. GitHub Actions or Jenkins) configured on master branch!*

To check out CI support:
- Switch branch to `workflow-keeping-test-results` or `erg02`

All workflow runs and their details **[here](https://github.com/gomczak/cypress-ts/actions)**.

The last published test report with history is available on **[GitHub Pages](https://gomczak.github.io/cypress-ts/27/)**.

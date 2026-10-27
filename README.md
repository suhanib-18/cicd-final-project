# ci-cd-final-project

[![CI Workflow](https://github.com/suhanib-18/cicd-final-project/actions/workflows/workflow.yml/badge.svg)](https://github.com/suhanib-18/cicd-final-project/actions)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python 3.9](https://img.shields.io/badge/Python-3.9-green.svg)](https://shields.io/)

## Project Name

**ci-cd-final-project**

This repository is the **ci-cd-final-project** for the IBM Continuous Integration and Continuous Delivery (CI/CD) Final Project. It implements a Customer Accounts Microservice with GitHub Actions CI and Tekton / OpenShift CD.

### Project name details
- **Project name:** `ci-cd-final-project`
- **Repository:** `cicd-final-project`
- **Author:** suhanib-18
- **Microservice:** Customer Accounts Service
- **Stack:** Python 3.9, Flask, Flake8, Nose, Tekton, OpenShift

### CI/CD
- GitHub Actions workflow: `.github/workflows/workflow.yml` (Lint with flake8, Run unit tests with nose)
- Tekton tasks: `.tekton/tasks.yml` (cleanup task, Run unit tests with nose)

### API endpoints
- `GET /health`
- `GET /accounts`
- `POST /accounts`
- `GET /accounts/{id}`
- `PUT /accounts/{id}`
- `DELETE /accounts/{id}`

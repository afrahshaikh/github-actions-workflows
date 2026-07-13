# 🚀 GitHub Actions Workflows Collection

![GitHub](https://img.shields.io/github/license/afrahshaikh/github-actions-workflows)
![GitHub last commit](https://img.shields.io/github/last-commit/afrahshaikh/github-actions-workflows)
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/afrahshaikh/github-actions-workflows/python-ci.yml)
![GitHub stars](https://img.shields.io/github/stars/afrahshaikh/github-actions-workflows?style=social)

A curated collection of **production-ready GitHub Actions workflows** for CI/CD, security scanning, deployment, and repository automation.

These workflows are designed to be easy to understand, reusable across projects, and follow GitHub Actions best practices.

---

## ✨ Features

* ✅ Multi-language CI pipelines
* ✅ Docker build automation
* ✅ Security scanning
* ✅ Dependency review
* ✅ GitHub Pages deployment
* ✅ Firebase deployment
* ✅ Release automation
* ✅ Pull request automation
* ✅ Reusable workflows
* ✅ Community templates

---

# Repository Structure

```text
.github/
│
├── workflows/
│   ├── python-ci.yml
│   ├── node-ci.yml
│   ├── flutter.yml
│   ├── java-maven.yml
│   ├── gradle.yml
│   ├── go.yml
│   ├── rust.yml
│   ├── php.yml
│   ├── dotnet.yml
│   ├── docker.yml
│   ├── docker-publish.yml
│   ├── codeql.yml
│   ├── dependency-review.yml
│   ├── trivy.yml
│   ├── release.yml
│   ├── pages.yml
│   ├── firebase.yml
│   ├── labeler.yml
│   ├── stale.yml
│   ├── auto-merge.yml
│   ├── welcome.yml
│   └── reusable-build.yml
│
├── ISSUE_TEMPLATE/
├── pull_request_template.md
└── labeler.yml
```

---

# Included Workflows

## CI/CD

| Workflow   | Description                                         |
| ---------- | --------------------------------------------------- |
| Python CI  | Lint, test, and validate Python projects            |
| Node.js CI | Install, test, lint, and build Node.js applications |
| Flutter CI | Analyze, test, and build Flutter applications       |
| Java Maven | Build and test Maven projects                       |
| Gradle     | Build Gradle-based applications                     |
| .NET       | Restore, build, and test .NET projects              |
| Go         | Format, vet, and test Go projects                   |
| Rust       | Run fmt, clippy, tests, and build                   |
| PHP        | Composer install and PHPUnit                        |

---

## Docker

| Workflow       | Description                              |
| -------------- | ---------------------------------------- |
| Docker Build   | Build Docker images using Buildx         |
| Docker Publish | Push images to GitHub Container Registry |

---

## Security

| Workflow          | Description                                          |
| ----------------- | ---------------------------------------------------- |
| CodeQL            | Static code analysis                                 |
| Dependency Review | Detect vulnerable dependencies                       |
| Trivy             | Scan repositories and containers for vulnerabilities |

---

## Deployment

| Workflow     | Description                          |
| ------------ | ------------------------------------ |
| GitHub Pages | Deploy static sites                  |
| Firebase     | Deploy Firebase Hosting projects     |
| Release      | Automatically create GitHub Releases |

---

## Repository Automation

| Workflow   | Description                             |
| ---------- | --------------------------------------- |
| Labeler    | Automatically label pull requests       |
| Welcome    | Welcome first-time contributors         |
| Auto Merge | Merge approved Dependabot PRs           |
| Stale      | Close inactive issues and pull requests |

---

# Quick Start

Copy any workflow into your own repository:

```
.github/workflows/
```

Then customize it to match your project requirements.

---

# Example

```yaml
name: Python CI

on:
  push:
    branches:
      - main

jobs:
  test:
    runs-on: ubuntu-latest
```

---

# Best Practices

* Use official GitHub Actions whenever possible.
* Cache dependencies to speed up builds.
* Keep workflows modular.
* Store secrets in GitHub Secrets.
* Pin action versions to stable major releases.
* Run security scans regularly.
* Use reusable workflows to reduce duplication.

---

# Repository Automation

This repository includes automation for:

* Automatic releases
* Dependency review
* Security scanning
* Docker builds
* GitHub Pages
* Firebase deployment
* Pull request labels
* Welcome messages
* Stale issue cleanup

---

# Requirements

* GitHub Actions enabled
* GitHub-hosted or self-hosted runners
* Repository secrets (when required)
* Docker (for Docker workflows)
* Firebase CLI (for Firebase deployment)

---

# Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a Pull Request.

Please read **CONTRIBUTING.md** before contributing.

---

# License

This project is licensed under the MIT License.

See the **LICENSE** file for details.

---

# Author

**Afrah Shaikh**

If you found this repository helpful, consider giving it a ⭐ on GitHub.

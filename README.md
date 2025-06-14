# jentz.co

[![Hugo](https://img.shields.io/badge/built%20with-hugo-ff4088?logo=hugo)](https://gohugo.io/)
[![AWS Amplify](https://img.shields.io/badge/deployed%20on-aws%20amplify-ff9900?logo=amazon-aws)](https://aws.amazon.com/amplify/)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Welcome to **jentz.co** — my personal website and blog

---

## 🚀 About

- **Static site** built with [Hugo](https://gohugo.io/) for blazing-fast performance and easy content management.
- **Deployed with [AWS Amplify](https://aws.amazon.com/amplify/)** for seamless CI/CD and global delivery.
- **Infrastructure as Code**: All [infrastructure](https://github.com/jentz/aws-infrastructure/tree/main/terraform/jentz.co) is managed with [Terraform](https://www.terraform.io/).

---

## 🛠️ Tech Stack

- **Hugo** — Static site generator (Go-based)
- **AWS Amplify** — Hosting & CI/CD
- **Terraform** — Infrastructure management https://github.com/jentz/aws-infrastructure/tree/main/terraform/jentz.co
- **Markdown** — Content authoring

---

## 📦 Local Development

Start the Hugo server:

```sh
hugo server --buildDrafts --disableFastRender
```

Visit http://localhost:1313/ to see the site.

## 🌍 Production Deployment

Production is deployed automatically via AWS Amplify on every push to main.
Infrastructure is defined in [aws-infrastructure](https://github.com/jentz/aws-infrastructure).



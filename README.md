# Cow wisdom web server

## Prerequisites

```
sudo apt install fortune-mod cowsay -y
```

## How to use?

1. Run `./wisecow.sh`
2. Point the browser to server port (default 4499)

## What to expect?
![wisecow](https://github.com/nyrahul/wisecow/assets/9133227/8d6bfde3-4a5a-480e-8d55-3fef60300d98)

# Problem Statement
Deploy the wisecow application as a k8s app

## Requirement
1. Create Dockerfile for the image and corresponding k8s manifest to deploy in k8s env. The wisecow service should be exposed as k8s service.
2. Github action for creating new image when changes are made to this repo
3. [Challenge goal]: Enable secure TLS communication for the wisecow app.

## Expected Artifacts
1. Github repo containing the app with corresponding dockerfile, k8s manifest, any other artifacts needed.
2. Github repo with corresponding github action.
3. Github repo should be kept private and the access should be enabled for following github IDs: nyrahul
## Wisecow - DevOps Practical Assessment

This repository contains the **Wisecow application** containerized with Docker, deployed on **Kubernetes (EKS)**, and integrated with a **CI/CD pipeline using GitHub Actions**.

---

## 🚀 Project Overview
- **Application:** [Wisecow](https://github.com/nyrahul/wisecow) – generates random quotes with `fortune` and `cowsay`.
- **Objective:** Containerize, deploy on Kubernetes, and automate build/push with CI/CD.
- **Final Output:** Accessible over AWS EKS via LoadBalancer.

---

## 🐳 Dockerization
The app is containerized using a custom `Dockerfile`:

### Build Image
```bash
docker build -t chiranjeevi001/wisecow:latest .

CI/CD test run Thu Sep 18 04:25:01 UTC 2025
retry Thu Sep 18 04:55:35 UTC 2025
retry Thu Sep 18 05:12:37 UTC 2025
retry Thu Sep 18 05:13:19 UTC 2025
retry Thu Sep 18 05:25:24 UTC 2025

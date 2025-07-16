# 🔐 AutoForge Security Orchestration

> **Checkov-inspired. Terraform-rooted. Cloud-compliant.**  
> AutoForge is a modular DevSecOps framework designed to scan, orchestrate, and visualize infrastructure trust — with pre-scan controls, live dashboards, and graph intelligence.

---

## 🧭 Table of Contents

- [📌 Overview](#📌-overview)
- [✨ Features](#✨-features)
- [🖼 Live Demo (Optional)](#🖼-live-demo-optional)
- [⚙️ Setup & Usage](#⚙️-setup--usage)
- [🗂 Folder Structure](#🗂-folder-structure)
- [🧪 Example Rule](#🧪-example-rule)
- [👤 Author & Vision](#👤-author--vision)
- [📄 License](#📄-license)

---

## 📌 Overview

AutoForge builds on ideas from **Checkov**, but pushes further:

✅ Terraform-first infrastructure scanning  
✅ Pre-scan dashboards for rule targeting  
✅ Profile manager for severity overrides  
🚧 Security graph engine (in progress)

AutoForge helps configure trust boundaries and visualize compliance behavior across environments — dev, staging, or prod.

---

## ✨ Features

| Feature              | Status        |
|----------------------|---------------|
| 🔍 Pre-Scan Setup     | ✅ Implemented |
| 📊 Live Dashboard     | ✅ Live UI     |
| 🗂 Profile Manager     | ✅ Dev/Prod Profiles |
| 📦 YAML Rule Engine   | ✅ Modular     |
| 🧠 Security Graphs     | 🚧 In Progress |

<details>
<summary>🔎 Click to preview planned graph functionality</summary>

Graphs will show:

- IAM access relationships  
- Over-permissive links  
- Trust paths across accounts  
- Graph annotations + violation overlays

</details>

---

## 🖼 Live Demo (Optional)

> _Embed screenshots or link to a preview once hosted._  
> 🚀 Live Preview: `http://127.0.0.1:8001`

---

## ⚙️ Setup & Usage

```bash
pip install -r requirements.txt
uvicorn main:app --reload --port 8001
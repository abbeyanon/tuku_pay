# tuku_pay — ERPNext Site

This repository contains the Frappe/ERPNext site files for `tuku_pay`, a custom ERPNext deployment.

---

## 🚀 Quick Overview

This repo includes:

- `apps.txt`, `apps.json`: ERP apps installed
- `.gitignore`: runtime files excluded
- CFMS+ APP 
- Site files like public/ and private/
- Source only — **does not include DB or media files**

---

## 📦 Requirements

To use this site, you'll need:

- Ubuntu 22.04 (recommended)
- Python 3.10+
- Node.js 16+
- Redis, MariaDB
- wkhtmltopdf
- Frappe Bench (version 14+)
- ERPNext installed (from `bench get-app`)

---

## 🧰 Setup Instructions

### 1. Clone the Repo

```bash
git clone https://github.com/abbeyanon/tuku_pay.git
cd tuku_pay

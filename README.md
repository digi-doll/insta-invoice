# Insta-Invoice API 🚀

A fast and easy-to-use API for generating professional invoices — instantly.

## 🔧 What is Insta-Invoice?

Insta-Invoice is a REST API built using FastAPI that lets users generate, manage, and (soon) send invoices programmatically. Whether you're a freelancer, small business owner, or gig worker, this API helps you automate your billing workflow with ease.

---

## 💡 Features

- 📬 Create and retrieve invoices via JSON
- 📄 Export invoices to PDF (coming soon)
- 📧 Email invoices to clients (coming soon)
- 🔐 Built with security and simplicity in mind

---

## 📦 Tech Stack

- Python 3
- FastAPI
- Uvicorn (for running the server)
- Git & GitHub
- Deployed on AWS (coming soon)

---

## 🚀 Getting Started

```bash
# Clone this repo
git clone https://github.com/digi-doll/insta-invoice.git
cd insta-invoice

# Create and activate virtual environment
python -m venv venv
.\venv\Scripts\activate      # Windows
# or
source venv/bin/activate     # Mac/Linux

# Install dependencies
pip install fastapi uvicorn

# Run the API
uvicorn main:app --reload

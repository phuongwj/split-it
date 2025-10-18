# split-it

## Table of Contents

- [About](#-about)
- [Project Structure](#-project-structure)
- [Tech Stack](#-tech-stack)

## 🤔 About

Split-it is a tool for splitting receipts and managing expenses among groups. It makes it easy to upload a receipt, assign items to people, and quickly see who owes what. **AI-based image scanning support is planned**, so you'll eventually be able to upload a photo of a receipt and have it parsed automatically.

## 🧱 Project Structure

```
split-it/
├── backend/
│   ├── app/
│   │   ├── main.py
│   │   ├── models/
│   │   │   ├── bill.py
│   │   ├── routers/
│   │   │   ├── split.py
│   │   ├── services/
│   │   │   ├── split_service.py
│   │   ├── requirements.txt
│   │   ├── Dockerfile
│   │   ├── .dockerignore
├── frontend/
```

## 🛠️ Tech Stack

- **Backend:** FastAPI (Python)
- **Frontend:** React (Javascript) - coming soon
- **Dev Environment:** Docker & Docker Compose
- **AI-based image scanning:** - coming soon
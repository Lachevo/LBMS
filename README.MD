# 📚 Library Book Management System

A full-stack web application for managing books in a library.

This project is built with:

- Backend: Django + Django REST Framework
- Frontend: Next.js
- Database: SQLite (development)

---

## Features

- View all books
- Add new books
- View book details
- REST API backend
- Responsive frontend
- Clean project structure

Planned Features:

- Update books
- Delete books
- Search books
- User authentication
- Book borrowing system
- Admin dashboard

---

## Tech Stack

### Backend
- Django
- Django REST Framework
- SQLite

### Frontend
- Next.js
- React
- Tailwind CSS

### Tools
- Git
- GitHub

---

## Project Structure

```text
library-management-system/
│
├── backend/
│   ├── books/
│   ├── config/
│   ├── manage.py
│   └── requirements.txt
│
├── frontend/
│   ├── app/
│   ├── components/
│   ├── public/
│   └── package.json
│
└── README.md
```

---

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/yourusername/library-management-system.git
cd library-management-system
```

---

## Backend Setup (Django)

Create a virtual environment:

```bash
python -m venv venv
```

Activate it:

### Linux / macOS

```bash
source venv/bin/activate
```

### Windows

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run migrations:

```bash
python manage.py migrate
```

Start the server:

```bash
python manage.py runserver
```

Backend runs on:

```text
http://127.0.0.1:8000
```

---

## Frontend Setup (Next.js)

Navigate to frontend:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start development server:

```bash
npm run dev
```

Frontend runs on:

```text
http://localhost:3000
```

---

## API Endpoints

### Books

| Method | Endpoint | Description |
|----------|----------|----------|
| GET | /api/books/ | Retrieve all books |
| POST | /api/books/ | Add a new book |
| GET | /api/books/<id>/ | Retrieve a single book |

---

## Learning Goals

This project is being developed to practice:

- Django fundamentals
- Models and migrations
- REST API development
- Next.js frontend development
- Full-stack application architecture
- Git and GitHub workflow

---

## Future Improvements

- Authentication and authorization
- JWT authentication
- Book borrowing system
- Search and filtering
- Pagination
- PostgreSQL
- Deployment

---

## Author

Developed by Leul Neway as a learning project to improve full-stack web development skills.
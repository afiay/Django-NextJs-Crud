# Django-Next.js CRUD Application

This project is a full-stack application utilizing Django with Django REST Framework for the backend and Next.js for the frontend. It provides CRUD operations for managing a restaurant's menu.

## Technologies

- **Backend**: Django 5.0.4, Django REST Framework 3.15.1
- **Frontend**: Next.js
- **Database**: SQLite (Default for Django)
- **Languages**: Python 3.12.2, JavaScript

## Setup and Installation

Ensure you have Python 3.12.2 and Node.js installed on your machine.

### Clone the repository

```bash
git clone https://github.com/afiay/Django-NextJs-Crud.git
cd Django-NextJs-Crud
```

### Backend Setup

```bash
# Create a virtual environment
python -m venv venv
# Activate the virtual environment
# Windows
venv\Scripts\activate
# macOS and Linux:
source venv/bin/activate
# Install dependencies
pip install -r requirements.txt
# Run migrations
python manage.py migrate
# Start the backend server
python manage.py runserver
```

### Frontend Setup

```bash
# Navigate to the frontend directory
cd frontend
# Install dependencies
npm install
# Start the frontend application
npm run dev
```

Now you can access the backend API at http://localhost:8000/ and the frontend at http://localhost:3000/.


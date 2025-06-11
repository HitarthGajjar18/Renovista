# Renovista 🏡

Renovista is a Django-based web application designed for showcasing interior design projects and renovations. It allows users to view stylish room designs and media files, providing an elegant and interactive UI for a portfolio or service showcase.

## 🌟 Features

- Home page with photo galleries
- Organized media handling for interior design images
- Easy-to-customize Django backend
- SQLite-based lightweight database setup

## 🛠️ Technologies Used

- Python 3.x
- Django
- SQLite
- HTML/CSS (likely Bootstrap or similar for frontend)
- Pillow (for image handling)

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or above
- Virtualenv (recommended)

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/renovista.git
cd renovista

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Run the server
python manage.py runserver


Renovista/
│
├── myapp/                 # Django app with views and templates
├── renovista/             # Django project settings
├── media/                 # Uploaded photos
├── manage.py              # Django project runner
├── db.sqlite3             # SQLite database
├── requirements.txt       # Dependencies (generate with pip freeze)
└── venv/                  # Virtual environment

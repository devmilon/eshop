# E-Shop (Django E-Commerce Project)

A full-featured E-Commerce web application built with Python and Django framework.

---

## 📌 Features

- **Product Catalog & Details:** Browse products with dynamically rendered categories and details.
- **Cart & Order Management:** Add products to the cart and process orders seamlessly.
- **User Authentication:** Sign up, log in, and manage user sessions.
- **Admin Dashboard:** Manage products, orders, static files, and media files via Django Admin.

---

## 🛠️ Tech Stack

- **Backend:** Python, Django
- **Database:** SQLite (`db.sqlite3`)
- **Frontend:** HTML, CSS, JavaScript (Templates)
- **Deployment Assets:** `requirements.txt`, `runtime.txt`

---

## 🚀 Getting Started

Follow these steps to set up and run the project locally on your machine.

### Prerequisites

Make sure you have the following installed:
- Python 3.x
- `pip` (Python package installer)
- `git`

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/devmilon/eshop.git](https://github.com/devmilon/eshop.git)
   cd eshop

Repository Structure
eshop/
│── ashop/            # Django project settings & main configuration
│── home/             # App for main views, home page, and core logic
│── media/            # User-uploaded media files (product images, etc.)
│── public/static/    # Static assets (CSS, JS, images)
│── template/         # HTML template files
│── db.sqlite3        # Local SQLite database
│── manage.py         # Django management script
│── requirements.txt  # Python dependency list
└── runtime.txt       # Python runtime version for deployment (e.g., Heroku)

Create and activate a virtual environment
# On macOS/Linux
python3 -m venv venv
source venv/bin/activate

# On Windows
python -m venv venv
venv\Scripts\activate

Install dependencies
pip install -r requirements.txt

Run database migrations:
Run database migrations

Create a superuser
python manage.py createsuperuser

Start the development server
python manage.py runserver



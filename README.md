# 🛍️ Django E-Commerce Project

A fully functional e-commerce web application built with Django.  
Includes user authentication, shopping cart, checkout, order management, and more.

---

## 🚀 Features

- User registration & login with email verification
- Product catalog with dynamic filtering
- Cart management (add/update/remove items)
- Order history & refund request system
- Stripe integration for secure payments
- Admin dashboard for managing orders & users

---

## 🛠️ Tech Stack

- **Backend**: Django, PostgreSQL (or SQLite by default)
- **Frontend**: HTML, CSS (Bootstrap)
- **Authentication**: `django-allauth` with social login
- **Payments**: Stripe API
- **Templating**: Django Templating Language (DTL)
- **Forms**: `django-crispy-forms`

---

## ⚙️ Getting Started

### 🔧 Prerequisites

- Python 3.8+
- pip (Python package manager)
- Git (to clone the project)

### 🧪 Setup Instructions

```bash
# 1. Clone the repo
git clone https://github.com/your-username/django-ecommerce.git
cd django-ecommerce

# 2. Create and activate virtual environment
python -m venv venv
venv\Scripts\activate   # On Windows
# source venv/bin/activate  # On macOS/Linux

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run migrations
python manage.py migrate

# 5. Create superuser
python manage.py createsuperuser

# 6. Start the development server
python manage.py runserver

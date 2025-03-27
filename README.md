# Gas Utility Service Management System 🚀

This is a Django-based web application that allows customers to submit and track gas service requests online. It also provides customer support representatives with a tool to manage requests efficiently.

## Features

- **Service Requests** – Customers can submit service requests online, select the type of request, provide details, and attach files.
- **Request Tracking** – Users can track the status of their service requests, including submission and resolution timestamps.
- **User Account Management** – Customers can view their account details.
- **Admin Panel** – Customer support representatives can manage service requests and provide assistance.

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/AdityaNik/gas-utility.git
cd gas-utility
```

### 2. Set up a virtual environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Apply database migrations

```bash
python manage.py migrate
```

### 5. Create a superuser for the admin panel

```bash
python manage.py createsuperuser
```

### 6. Run the development server

```bash
python manage.py runserver
```

Access the application at **http://127.0.0.1:8000/admin

## Usage

- **Customers**: Register, submit service requests, and track their status.
- **Admins**: Log in to the Django admin panel at **/admin/** to manage requests.

## Project Structure

```
📂 gas-utility-service
 ┣ 📂 myapp (Main Django app)
 ┣ 📂 templates (HTML templates)
 ┣ 📂 static (CSS, JS, Images)
 ┣ 📜 manage.py (Django entry point)
 ┣ 📜 requirements.txt (Dependencies)
 ┣ 📜 .env (Environment variables - not committed)
 ┗ 📜 README.md (This file)
```

## API Endpoints (if applicable)

| Method | Endpoint              | Description                   |
|--------|----------------------|------------------------------|
| POST   | `/service/request/`  | Submit a new service request |
| GET    | `/service/status/`   | Track request status         |
| GET    | `/account/`          | View user account info       |

## Technologies Used

- **Backend**: Django, Django REST Framework
- **Database**: SQLite
- **Authentication**: Django Auth


---

📧 **Contact**: aadityanikam2004@gmail.com

# AP Monitor Dashboard

**Status**: Work in Progress

---

## 📝 Overview
The **Accounts Payable Monitor Dashboard** is a Django-based web application for monitoring, detecting, and managing accounts payable transactions. Its goal is to:
- Help AP teams manage vendor and invoice data.
- Highlight suspicious transactions, duplicate invoices, and potential anomalies.
- Provide a simple web interface and REST API for querying data.

This project is in its early stages, with a working view, models, and some mock data. Future updates will focus on making the system feature-complete for real-world usage.

---

## Core Features (planned)
- Vendor and invoice management
- REST API for transactions, invoices, vendors
- Duplicate transaction detection
- CSV file uploads for invoices
- Basic reporting dashboard
- Unit and integration tests

---

## Tech Stack
- **Backend**: Python 3.x, Django, Django REST Framework
- **Frontend**: HTML/CSS/JS (responsive)
- **Database**: PostgreSQL
- **Testing**: pytest, Django TestCase
- **CI/CD**: GitHub Actions (planned)

---

## Running the Project
### Clone the repository:
git clone https://github.com/yourusername/AP_Monitor_Dashboard.git  
cd AP_Monitor_Dashboard
### Set up a virtual environment:
python -m venv venv  
source venv/bin/activate  # On Windows: venv\Scripts\activate
### Run the development server
python manage.py runserver

---
The app will be accessible at: http://127.0.0.1:8000/

---
## Screenshots

<img width="1463" alt="Screenshot 2025-06-20 at 9 24 05 PM" src="https://github.com/user-attachments/assets/581ca3c7-5cbf-45de-ada5-295a96501f7d" />
<img width="1453" alt="Screenshot 2025-06-20 at 9 24 23 PM" src="https://github.com/user-attachments/assets/d2495c43-0205-4191-bdad-634b6dfa082a" />
<img width="1395" alt="Screenshot 2025-06-20 at 9 24 42 PM" src="https://github.com/user-attachments/assets/59bcac1e-2a2c-4265-8b71-c713ce4af30e" />

---
## Future Updates
- Improve duplicate detection algorithm
- Implement CSV upload interface
- Build vendor master data management interface
- Implement real-time alerting and notifications
- Expand tests and integrate GitHub Actions for continuous testing

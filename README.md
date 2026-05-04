# CertifyMe Admin Portal Backend

## Overview
This project is a backend system built using Flask for managing admin operations and opportunities.

## Tech Stack
- Python
- Flask
- SQLAlchemy
- SQLite

## Features
- Admin Signup & Login
- Secure Authentication (Password Hashing)
- CRUD Operations on Opportunities
- Session Management

## How to Run

1. Clone the repository
git clone https://github.com/Suhailkhan-coder2/CertifyMe-Admin-Portal.git

2. Install dependencies
pip install -r requirements.txt

3. Run the app
python app.py

## API Endpoints

POST /signup  
POST /login  
POST /logout  
POST /add-opportunity  
GET /get-opportunities  
PUT /update-opportunity/<id>  
DELETE /delete-opportunity/<id>

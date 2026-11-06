
# CampusConnect

## Project Information

- **Developer:** Junwel E. Conson
- **Section:** CSIT327-G5
- **Project:** First Django Lab Challenge

## Overview

CampusConnect is a Django-based web application that provides user registration, authentication, profile management, and an administrator dashboard.

## Features

- User registration and login
- Profile viewing and editing using Django UpdateView
- Signup success notifications using Django Messages Framework
- User authentication and role-based access
- Bootstrap 5 responsive interface
- Administrator dashboard

## Technologies Used

- Python
- Django
- HTML
- Bootstrap 5
- SQLite

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/JunwelConson/CSIT327-G5-Conson-Junwel-FirstDjango.git
   ```

2. Navigate into the project:

   ```bash
   cd CSIT327-G5-Conson-Junwel-FirstDjango
   ```

3. Create a virtual environment:

   ```bash
   py -m venv .venv
   ```

4. Activate the virtual environment (Windows PowerShell):

   ```powershell
   .\.venv\Scripts\Activate.ps1
   ```

5. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

6. Apply migrations:

   ```bash
   python manage.py migrate
   ```

7. Run the development server:

   ```bash
   python manage.py runserver
   ```

8. Open http://127.0.0.1:8000/ in your browser.

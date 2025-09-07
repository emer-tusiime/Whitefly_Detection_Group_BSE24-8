"# CI/CD Capstone" 
Whitefly Detection Project
 Purpose

This project is built to detect whiteflies on crops using image analysis. By providing a web-based interface for uploading and processing crop images, the system supports farmers and researchers in early pest detection, reduced crop losses, and sustainable farming practices.

The platform consists of:

A React frontend for visualization and user interaction.

A Django backend (with Django REST Framework) for API endpoints, detection logic, and data management.

Tech Stack

Frontend: React

Backend: Django + Django REST Framework (DRF)

API Style: RESTful

Other: Image processing & ML model integration yolov.pt13 model (planned/ongoing)
Running the Project
clone the repo  https://github.com/emer-tusiime/Whitefly_Detection.git
cd whitefly-detection

run the client (React)
cd client
npm install
npm start

create a virtual environment
cd server
python -m venve venve
venv\Scripts\activate.bat

install dependencies
pip install -r requirements.txt

run the server (Django)
python manage.py runserver

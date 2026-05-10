# Property Renting Web Application

> A property listing and contact platform for prospective renters.

Built for **INFO3180 — Web Programming II** at the University of the West Indies, Mona.

## Tech Stack
- **Frontend:** HTML5, CSS3, JavaScript / jQuery
- **Backend:** Python (Flask), Flask-WTF, server-side rendering
- **Database:** PostgreSQL · SQLAlchemy ORM

## Features
- Browse property listings with images and details
- Add new properties with file upload (image)
- View property details with full descriptions
- Contact landlord form for inquiries
- Form validation (Flask-WTF) and CSRF protection

## Run Locally
```bash
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
flask db upgrade
flask run
```

Built by [Josiah-John Green](https://github.com/j0hnc0d3s) — Software Engineering, UWI Mona '26.

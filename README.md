🇷🇺 [Читать на русском](README_RU.md)

A full-stack e-commerce web platform engineered with Django for inventory administration, structured catalog indexing, and digital fulfillment of surveillance and security hardware.

### Key Architectural Highlights:
* **Relational Domain Modeling:** Strongly typed catalog schemas mapping surveillance units, technical specifications, and inventory availability via Django ORM.
* **Administrative Operations Console:** Customized Django admin dashboards enabling real-time product ingestion, pricing updates, and catalog categorization.
* **User Authentication Framework:** Secure credential hashing, session management, and role segregation for customer accounts.
* **Modular MVC Architecture:** Decoupled separation of concerns across data persistence models, routing endpoints, controller views, and presentation layers.

### Tech Stack:
* Python 3.12
* Django 5.x (Enterprise web framework and ORM)
* SQLite / PostgreSQL (Relational persistence)
* HTML5 / CSS3 / JavaScript (Responsive frontend integration)

### Quick Start:
```bash
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

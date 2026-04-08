Lost and Found Management System

A Database Management System (DBMS) project built as a web application to report, track, and match lost and found items using fuzzy string matching.

-Features
Report lost and found items with images
Automatic matching of items based on similarity
View and manage lost/found listings
Claim items with status updates
Image upload with preview

-Tech Stack
Backend: Python, Flask
Database: MySQL
Frontend: HTML, CSS, Jinja2
Libraries: fuzzywuzzy, mysql-connector, werkzeug

-Matching Logic

Uses fuzzy string matching with weighted scoring:
Name (40%), Description (30%), Location (20%), Date (10%)

-Setup

pip install flask mysql-connector-python fuzzywuzzy python-Levenshtein
python app.py

-Highlights
Modular backend (app.py, models.py, db.py)
Image handling with secure uploads
Dynamic match suggestions after reporting items
LOST AND FOUND MANAGEMENT SYSTEM

A Database Management System (DBMS) project built as a web application to report, track, and match lost and found items using fuzzy string matching.

-FEATURES-

Report lost and found items with images

Automatic matching of items based on similarity

View and manage lost/found listings

Claim items with status updates
Image upload with preview

-TECH STACK-

Backend: Python, Flask

Database: MySQL

Frontend: HTML, CSS, Jinja2

Libraries: fuzzywuzzy, mysql-connector, werkzeug

-MATCHING LOGIC-

Uses fuzzy string matching with weighted scoring:
Name (40%), Description (30%), Location (20%), Date (10%)

-SETUP-

pip install flask mysql-connector-python fuzzywuzzy python-Levenshtein
python app.py

-HIGHLIGHTS-

Modular backend (app.py, models.py, db.py)
Image handling with secure uploads
Dynamic match suggestions after reporting items
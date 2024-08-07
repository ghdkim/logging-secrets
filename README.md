# logging-secrets
Using O-Auth, creating a secret logging website where users can write their secrets within their own accounts linked to Google or creating their own account on the website. Their account details will be saved in their local PostgreSQL server.

# Installation
1. npm i
2. Create your own database on PostgreSQL with the columns: id (Primary Key, Serial), email (VARCHAR 100), password (VARCHAR 100), secret (TEXT)

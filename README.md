Asset Management System
Overview
This is a simple Laravel Asset Management System used to manage company assets and track which users they are assigned to. It helps keep asset records organized and easy to manage.
________________________________________
Tech Stack
•	Laravel (PHP)
•	MySQL Database
________________________________________
Main Features
•	User Management – Create and manage users
•	Asset Management – Add, update, and view assets
•	Transactions – Assign/return assets and track history
•	Web + API routes available
________________________________________
Project Structure
•	Models → Asset, User, Transaction
•	Controllers → Handle system logic
•	Migrations → Database tables
•	routes/web.php → Web routes
•	routes/api.php → API routes
•	views/ → Frontend pages
________________________________________
Installation
•	cd asset-mgmt
•	composer install
•	npm install
•	cp .env.example .env
•	php artisan key:generate
•	php artisan migrate
•	php artisan serve
•	npm run dev
•	Open: http://127.0.0.1:8000
________________________________________
Notes
•	Configure .env database first
•	Make sure MySQL is running


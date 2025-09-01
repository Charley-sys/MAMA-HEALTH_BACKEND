📘 Mama Health – Backend (Laravel)
🌸 Overview

This is the backend API for the Mama Health platform, built with Laravel.
It handles authentication, health records, clinic schedules, payments, and SMS integrations.
It also powers the Mama Health Web Platform for healthcare providers and administrators which has just but a few features for now but will be fully featured with time.

🏗️ Tech Stack

Laravel (PHP 9.x)

MySQL (database)

REST API (for mobile & web clients)

Twilio  (SMS)

M-Pesa API (payments)

🌐 Web Deployment

The Mama Health web platform is live here:
👉 https://mama-health.donscustomclothiers.co.ke/



🚀 Getting Started
1. Clone the Repo
git clone https://github.com/yourusername/mama-health-backend.git
cd mama-health-backend

2. Install Dependencies
composer install

3. Setup Environment

Copy .env file and configure:

cp .env.example .env
php artisan key:generate


Update with your database credentials:

DB_DATABASE=mama_health
DB_USERNAME=root
DB_PASSWORD=

4. Run Database Migrations
php artisan migrate

5. Run the Backend Server
php artisan serve


API will be available at:
👉 http://127.0.0.1:8000/api

📡 API Endpoints (Sample)

POST /api/register – Register a new user

POST /api/login – User authentication

GET /api/clinics – List prenatal clinics

POST /api/appointments – Book appointment

POST /api/payments – Make a payment

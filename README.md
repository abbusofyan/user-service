# User Service

A **token-based authentication** microservice built with **Laravel Sanctum** and **MySQL**. This service handles user registration, login, authentication, and token management for secure communication between clients and other services.

---

## 🚀 Features

- 🔐 Token-based authentication using **Laravel Sanctum**
- 👥 User registration and login
- 🔄 Token issuing and revocation
- 🧾 Secure API access with bearer tokens
- 📦 Clean, modular Laravel structure for scalability

---

## 🛠 Tech Stack

- **Framework:** Laravel 12+
- **Authentication:** Laravel Sanctum
- **Database:** MySQL
- **API Format:** JSON

---

## 📦 Installation

```bash
git clone https://github.com/your-username/user-service.git
cd user-service
composer install
cp .env.example .env
php artisan key:generate

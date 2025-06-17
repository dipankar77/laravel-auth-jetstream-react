# 🧾 Laravel + Jetstream + React Authentication Demo

This repository showcases a **fully-featured authentication system** using Laravel Jetstream with Inertia.js + React + Tailwind CSS.

It includes user management, session security, 2FA, API tokens, and optional team functionality.

---

## 🚀 Tech Stack

- **Laravel 12**
- **Laravel Jetstream**
- **Inertia.js + React**
- **Tailwind CSS**
- **SQLite**
- **Laravel Sanctum** (for API support)

---

## ✨ Features

- ✅ Registration, login, password reset
- ✅ Email verification
- ✅ User profile update
- ✅ Session & browser management
- ✅ Two-Factor Authentication (2FA)
- ✅ API token generation
- ✅ Optional team features (create/join/switch)
- ✅ Clean SPA experience via Inertia.js

---

## ⚙️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/dipankar77/laravel-auth-jetstream-react.git
cd laravel-auth-jetstream-react
2. Install Dependencies
composer install
npm install && npm run dev
3. Setup Environment
cp .env.example .env
touch database/database.sqlite
php artisan migrate
4. Run Locally
php artisan serve
👤 Sample User
Create one using tinker:
php artisan tinker
User::factory()->create(['email' => 'test@example.com', 'password' => bcrypt('password')]);

📸 Screenshots
Include:
•	Login screen
•	Profile management
•	2FA setup
•	Browser sessions view
📄 License
MIT — use and adapt freely.
This is part of my professional Laravel portfolio. Full collection: github.com/dipankar77

## ✅ Add to Your Profile README

Update your main profile readme under:

```md
### 2. ⚛️ Laravel + Inertia.js + React Projects

| Repository | Description |
|------------|-------------|
| [laravel-auth-jetstream-react](https://github.com/dipankar77/laravel-auth-jetstream-react) | Laravel Jetstream demo with React, Inertia.js & Tailwind showing 2FA, profile, session, team features |

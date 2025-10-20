# 2001225034_PhamThaiThuan_Lab08

Laravel demo project for exercises:
- Bài tập 05: One-to-One Users-Profile
- Bài tập 06: Nâng cấp Products (stock)
- Bài tập 07: CRUD Products with validation and <x-input>
- Bài tập 08: Eloquent Reports

Requirements
- PHP 8+, Composer, MySQL (Laragon defaults)

Quick start
- Copy .env.example to .env and configure DB
- composer install
- php artisan migrate:fresh --seed
- php artisan serve

Routes
- /           Users & Profiles
- /products   Products CRUD
- /reports    Eloquent queries report

# Laravel Ninja Network

Simple Laravel CRUD application for managing ninjas and dojos.

## Features

- View ninjas
- Create ninjas
- View ninja details
- Delete ninjas
- Pagination
- Route model binding

## Setup Instructions

Clone the repository:

```bash
git clone https://github.com/jacksontann/laravel-project.git
```

Go into the project folder:

```bash
cd laravel-project
```

Install PHP dependencies:

```bash
composer install
```

Install Node.js dependencies:

```bash
npm install
```

Create environment file:

```bash
cp .env.example .env
```

Generate app key:

```bash
php artisan key:generate
```

Run migrations and seed database:

```bash
php artisan migrate --seed
```

Start Laravel server:

```bash
php artisan serve
```

Start Vite:

```bash
npm run dev
```

## Tech Stack

- Laravel 11
- Blade
- SQLite
- Tailwind CSS

# Pet Care Laravel Application

A comprehensive pet care management system built with Laravel 13.

## About Pet Care

Pet Care is a web application designed to help pet owners manage their pets' health, appointments, and care routines. Built using the Laravel framework, it provides a robust and scalable solution for pet management.

## Features

- Pet registration and profile management
- Health records tracking
- Appointment scheduling
- Vaccination reminders
- Medical history management
- User authentication and authorization

## Requirements

- PHP >= 8.2
- Composer
- Node.js >= 18
- NPM or Yarn
- MySQL/PostgreSQL/SQLite

## Installation

1. Clone the repository:
```bash
git clone https://github.com/jQsafi/pet-care.git
cd pet-care
```

2. Install PHP dependencies:
```bash
composer install
```

3. Install Node.js dependencies:
```bash
npm install
```

4. Copy the environment file:
```bash
cp .env.example .env
```

5. Generate application key:
```bash
php artisan key:generate
```

6. Configure your database in the `.env` file

7. Run database migrations:
```bash
php artisan migrate
```

8. Seed the database (optional):
```bash
php artisan db:seed
```

9. Build assets:
```bash
npm run build
```

10. Start the development server:
```bash
php artisan serve
```

## Usage

Visit `http://localhost:8000` in your browser to access the application.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests.

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

## Support

For support, please open an issue on GitHub or contact the development team.

---

Built with ❤️ using Laravel 13

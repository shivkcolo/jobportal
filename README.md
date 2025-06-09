# Job Portal

A modern job portal built with Laravel.

## Features

- User authentication and registration
- Profile management
- Job listings and search
- Application tracking
- Responsive design with Tailwind CSS

## Getting Started

### Prerequisites

- PHP >= 8.0
- Composer
- Node.js & npm
- MySQL or compatible database

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/jobportal.git
   cd jobportal
   ```

2. **Install PHP dependencies:**
   ```sh
   composer install
   ```

3. **Install JavaScript dependencies:**
   ```sh
   npm install
   ```

4. **Copy the example environment file and set your variables:**
   ```sh
   cp .env.example .env
   ```

5. **Generate application key:**
   ```sh
   php artisan key:generate
   ```

6. **Run migrations:**
   ```sh
   php artisan migrate
   ```

7. **Build frontend assets:**
   ```sh
   npm run build
   ```

8. **Start the development server:**
   ```sh
   php artisan serve
   ```

## Usage

- Visit `http://localhost:8000` in your browser.
- Register a new account or log in.
- Browse and apply for jobs.

## Testing

Run the test suite with:
```sh
php artisan test
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](LICENSE)
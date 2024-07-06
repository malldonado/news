# News Platform

A dynamic and responsive news platform developed with HTML, CSS, JavaScript, jQuery, and Ajax, using Bootstrap for a modern and intuitive design. The robust infrastructure is built with PHP using the Laravel framework and a MySQL database, ensuring a secure and efficient backend for real-time content management.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [License](#license)

## Features

- Dynamic and responsive design
- Real-time content management
- Secure backend with Laravel and MySQL
- Modern and intuitive user interface with Bootstrap
- Interactive features with jQuery and Ajax

## Technologies

- **Frontend:**
  - HTML
  - CSS
  - JavaScript
  - jQuery
  - Ajax
  - Bootstrap

- **Backend:**
  - PHP
  - Laravel

- **Database:**
  - MySQL

## Installation

### Prerequisites

- PHP 8.2.12 or higher
- Composer
- MySQL

### Steps

1. Clone the repository:
    ```sh
    git clone https://github.com/malldonado/news.git
    cd news/admin_panel_laravel
    ```

2. Install PHP dependencies:
    ```sh
    composer install
    ```

3. Set up the environment file:
    ```sh
    cp .env.example .env
    ```

4. Generate application key:
    ```sh
    php artisan key:generate
    ```

5. Configure the `.env` file with your database settings:
    ```env
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=news
    DB_USERNAME=root
    DB_PASSWORD=
    ```

6. Run the database migrations:
    ```sh
    php artisan migrate
    ```

7. Serve the application:
    ```sh
    php artisan serve
    ```

## License

This project is licensed under the MIT License.

# User Admin

## Description

This is a technical test created with Laravel and Vue.

## Prerequisites

If you want to try this project, you need:
- PHP +8.3
- Composer +2.7
- node +20.12
- Docker +26
- Docker Compose +2.24

This project was build with Laravel 11, so I encourage you to review It's [Server Requirements](https://laravel.com/docs/11.x/deployment#server-requirements) to check if your PHP installation it's right.

## Installation
1. Clone this repository.

1. Copy the ```.env.example``` file and create a new ```.env``` file.

1. Change database configuration, set this values:
    ```properties
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=app
    DB_USERNAME=root
    DB_PASSWORD=password
    ```

1. Change mail configuration, set this values:
    ```properties
    MAIL_MAILER=smtp
    MAIL_HOST=localhost
    MAIL_PORT=1025
    ```

1. Set up the services using docker compose:

    ```bash
    docker compose up -d
    ```

1. Install all dependencies:
    ```bash
    composer install
    npm install
    ```

1. Set up the project:
    ```bash
    php artisan serve
    npm run dev
    ```

1. Execute the database migrations:
    ```bash
    php artisan migrate
    ```

1. Open your browser in:
    - ```localhost:8000``` to use the app, and
    - ```localhost:8025``` to view the emails sended.

## Contributing

Thank you for considering contributing to this project, feel free to open a pull request.

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

## Author
If you have any questions, suggestions, or need assistance, please feel free to contact us:

Author: Hector Rubi
Portfolio: [hector-rubi.vercel.app](https://hector-rubi.vercel.app/)
LinkedIn: [in/hector-rubi-garcia](https://www.linkedin.com/in/hector-rubi-garcia/)

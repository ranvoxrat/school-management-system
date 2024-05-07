<h1 align="center">School Management System</h1>

<p align = "center">This open-source portfolio project is one of my main focuses during the On the Job Training for the Second Semester. I'm dedicated to developing a comprehensive school management system that could potentially serve various educational agencies. By creating this application, I aim to streamline administrative tasks and improve communication within schools. Through open-source collaboration, I hope to build a solution that meets the diverse needs of educational institutions, making processes more efficient and accessible. I'm excited about the opportunity to contribute to the educational sector and make a meaningful impact with this project. </p>

## Notes


## Current Tech Stack

-   HTML 5
-   CSS
-   SCSS
-   PHP
-   Javascript
-   JQuery
-   Laravel
-   Jetstream
-   Livewire

## Road Map


## Installation

-   Give me a star or follow my GitHub
-   Clone this repository

```bash
git clone <githublink>
```

-   Go to the folder application using `cd` command on your cmd or terminal
-   Run composer install on your cmd or terminal

```bash
composer install
```

-   Copy `.env.example` file to `.env` on the root folder.

```bash
copy .env.example .env
```

-   If you using terminal on Ubuntu run it to copy

```bash
cp .env.example .env
```

-   Open your `.env` file and change the database name (`DB_DATABASE`) to whatever you have, username (`DB_USERNAME`) and password (`DB_PASSWORD`) field correspond to your configuration.
-   Generate the App Key

```bash
php artisan key:generate
```

-   Migrate your database

```bash
php artisan migrate
```

-   Run the laravel server

```bash
php artisan serve
```

-   Open http://localhost:8000

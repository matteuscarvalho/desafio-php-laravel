# Desafio PHP - LARAVEL

## Laravel 9 e Sanctum.

prequisitos: php: ^8.0.2 e composer ^2.2.6

```Bash
composer install
```

```bash
cp .env.example .env
```

```bash
php artisan migrate
```

## Features

-   [x] Cadastro de usuário
-   [x] Login de usuário

## Register

-   name
-   email
-   password
-   password_confirmation

```bash
Method: Post
Accept: application/json
http://localhost:8000/api/register
```

## Login

-   email
-   password

```bash
Method: Post
Accept: application/json
http://localhost:8000/api/login
```

## Logout

```bash
Method: Post
Accept: application/json
Header: Bearer Token
http://localhost:8000/api/logout
```

## User

```bash
Method: Get
Accept: application/json
Header: Bearer Token
http://localhost:8000/api/user
```

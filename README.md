# Desafio PHP - LARAVEL

## Laravel 9 e Sanctum.

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
http://localhost:8000/api/register
```

## Login

-   email
-   password

```bash
Method: Post
http://localhost:8000/api/login
```

## Logout

```bash
Method: Post
Header: Bearer Token
http://localhost:8000/api/logout
```

## User

```bash
Method: Get
Header: Bearer Token
http://localhost:8000/api/user
```

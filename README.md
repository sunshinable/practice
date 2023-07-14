# Летняя практика

## Локальная установка

Клонируйте или скачайте репозиторий

```bash
  git clone https://github.com/sunshinable/practice.git project-name
```

Перейдите в проект с репозиторием

```bash
  cd project-name
```

-   Переминуйте файл .env.example в .env и настройте базу данных (я использовал xampp)

```bash
    composer install
```

```bash
    php artisan key:generate
```

```bash
    php artisan migrate:fresh --seed
```

#### Админ аккаунт

-   email = admin@example.com
-   password = 123

# Gody frontend use Laravel Framework

## Requirement

-   Docker
-   Docker compose

## How to development

1. Clone project from github.com

```sh
git clone https://github.com/godyvn/gody-frontend-laravel.git
```

2. Create environment variables

```sh
cp .env.example .env
```

3. Run docker compose

```sh
cd gody-frontend-laravel
docker-compose up
```

4. Install dependencies

```sh
docker exec -it [container_id] composer install
```

5. Server running on [http://localhost:8001](http://localhost:8001)

## Learning Laravel

-   [Official documentation](https://laravel.com/docs)

-   [Laravel Bootcamp](https://bootcamp.laravel.com)

-   [Laracasts](https://laracasts.com)

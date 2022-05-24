# Laravel Vue Sanctum SPA

Laravel and vue spa using tailwind (laravel/ui looks) for styling and sanctum for authentification

## Novedades

-   Laravel 8
-   Vue + VueRouter + Vuex
-   Login, register, update profile
-   password reset
-   Authentication with Sanctum
-   Tailwind + Heroicons

## Instalacion

-   `git clone git@github.com:montovele/sanctum_vue_laravel.git`  set verion and app name 
-   `cd my-spa`
-   Edit `.env` and set your database connection details and **your APP_URL** 
-   `php artisan key:generate`
-   `php artisan migrate`
-   `npm install`
-   `npm run dev`

### mailer 
-   set up mailer details
-   put **QUEUE_CONNECTION=database** 
## Notes
- make sure your domain is included in the statefull allowed domains (app/config/sanctum.php) to avoid [Unauthorised domains issue #3](/../../issues/3).

## Usage

#### Development

```bash
npm run watch

```

#### Production

```bash
npm run production
```
- turn off debug mode **.env**
##

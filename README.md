# Docs
https://inertiajs.com/server-side-setup

# Config
- Install server-side
```sh
composer require inertiajs/inertia-laravel
```

- Criar um app.blade.php (default inertia procura ele)
- Seguir resto na docs

# Config cliente side
```sh
php artisan inertia:middleware
```

- Criar uma vue
```sh
art ui vue
# art ui react
```

# [Install ziggy](https://github.com/tighten/ziggy)
- Para ter acesso as rotas laravel no js
    - composer require tightenco/ziggy
    - @routes
    - app.js
        .mixin({ methods: { route: window.route } })

# Laravel Artisan Commands

Welcome to the list of **Laravel Artisan Commands**! Artisan is Laravel's powerful command-line interface, offering helpful tools to speed up your development process.

This guide provides:
- Clear command descriptions
- Organized categories
- Copy-paste-ready commands

---

## 🚀 **Getting Started with Artisan**

To use Artisan, run:
```bash
php artisan
```

Below is a categorized list of Artisan commands to help you manage your Laravel project efficiently.

---

## 📂 **Application Management**

| Command                     | Description                                    |
|-----------------------------|------------------------------------------------|
| `php artisan serve`         | Start the development server                  |
| `php artisan down`          | Put the application into maintenance mode     |
| `php artisan up`            | Bring the application out of maintenance mode |
| `php artisan env`           | Display the current environment               |

---

## 🎨 **Make Commands** (Generate Classes)

| Command                               | Description                                        |
|---------------------------------------|----------------------------------------------------|
| `php artisan make:controller {name}` | Create a new controller                           |
| `php artisan make:model {name}`      | Create a new Eloquent model                       |
| `php artisan make:migration {name}`  | Create a new database migration                   |
| `php artisan make:seeder {name}`     | Create a new database seeder                      |
| `php artisan make:middleware {name}` | Create a new middleware                           |
| `php artisan make:job {name}`        | Create a new job class                            |
| `php artisan make:listener {name}`   | Create a new event listener                       |

💡 **Tip:** Use `--help` after any command for detailed usage:
```bash
php artisan make:controller --help
```

---

## 🗄️ **Database Management**

| Command                       | Description                                     |
|-------------------------------|-------------------------------------------------|
| `php artisan migrate`         | Run database migrations                        |
| `php artisan migrate:rollback`| Rollback the last database migration           |
| `php artisan db:seed`         | Run database seeders                           |
| `php artisan db:wipe`         | Drop all tables and re-run migrations          |

---

## 🛠️ **Debugging & Optimization**

| Command                         | Description                                       |
|---------------------------------|---------------------------------------------------|
| `php artisan config:cache`      | Cache the configuration                          |
| `php artisan route:cache`       | Cache the routes                                 |
| `php artisan view:clear`        | Clear compiled view files                        |
| `php artisan cache:clear`       | Clear the application cache                      |
| `php artisan config:clear`      | Remove the configuration cache                   |
| `php artisan optimize`          | Optimize the framework for better performance    |

---

## 🔍 **Help Commands**

| Command                 | Description                           |
|-------------------------|---------------------------------------|
| `php artisan list`      | List all available Artisan commands   |
| `php artisan help {cmd}`| Display help for a specific command   |

---

## 🎯 **Custom Commands**

Laravel lets you create your own Artisan commands! To create one, use:
```bash
php artisan make:command {CommandName}
```
Customize it in the `app/Console/Commands` directory.

---

## 🎉 **Happy Coding!**

Use these commands to supercharge your Laravel development workflow. Have questions or need help? Join the [Laravel Community](https://laravel.io)!

> Feel free to contribute and enhance this guide with more commands or tips!

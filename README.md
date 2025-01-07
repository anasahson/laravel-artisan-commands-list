# Laravel Artisan Commands & Error Solutions Cheat Sheet 🚀

**Welcome to the ultimate Laravel Cheat Sheet!**
Your go-to resource for mastering Laravel Artisan commands and resolving Laravel errors from A to Z.

---

## 🕋 Table of Contents

1. [Laravel Artisan Commands](#laravel-artisan-commands)
2. [Laravel Errors (A-Z) with Solutions](#laravel-errors-a-z-with-solutions)
3. [Contribution Guidelines](#contribution-guidelines)
4. [License](#license)

---

## 🔧 Laravel Artisan Commands

### Frequently Used Commands

| **Command**                   | **Description**               |
| ----------------------------- | ----------------------------- |
| `php artisan serve`           | Start the development server. |
| `php artisan migrate`         | Run database migrations.      |
| `php artisan make:controller` | Create a new controller.      |
| `php artisan make:model`      | Create a new model.           |
| `php artisan route:list`      | List all registered routes.   |

### Advanced Commands

| **Command**                   | **Description**                         |
| ----------------------------- | --------------------------------------- |
| `php artisan optimize`        | Optimize the framework for performance. |
| `php artisan config:cache`    | Cache the configuration files.          |
| `php artisan make:middleware` | Create a new middleware.                |
| `php artisan tinker`          | Interact with the application in CLI.   |
| `php artisan queue:work`      | Process jobs from the queue.            |

> **Pro Tip**: To view all available Artisan commands, run:
>
> ```bash
> php artisan list
> ```

---

## 🔍 Laravel Errors (A-Z) with Solutions

### A: **`Access denied for user 'root'@'localhost'`**

**Cause**: Database credentials are incorrect.
**Solution**:

1. Open `.env` file and verify:
   ```env
   DB_USERNAME=root
   DB_PASSWORD=your_password
   ```
2. Clear and cache configuration:
   ```bash
   php artisan config:clear
   php artisan config:cache
   ```

---

### B: **`Base table or view not found`**

**Cause**: Migrations not run or database missing.
**Solution**:

1. Run migrations:
   ```bash
   php artisan migrate
   ```
2. Verify database settings in `.env` file.

---

### C: **`Class not found`**

**Cause**: Incorrect namespace or autoload issues.
**Solution**:

1. Ensure proper namespace usage in the file.
2. Regenerate Composer autoload files:
   ```bash
   composer dump-autoload
   ```

---

## 🤝 Contribution Guidelines

1. **Fork the repository** and clone it to your machine.
2. Create a new feature branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes with detailed messages.
4. Open a pull request for review!

---

## 📞 License

This project is licensed under the **MIT License**. Feel free to use and share!

---

**Happy Coding!** 🚀


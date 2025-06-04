## Laravel Inventory Project

### Requirements
- PHP 8.1+
- Composer
- MySQL

### Installation
```bash
git clone https://github.com/yourusername/inventory-app.git
cd inventory-app
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve

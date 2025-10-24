# 🚀 Laravel API Boilerplate with MySQL

A **robust and scalable boilerplate** for building powerful RESTful APIs using the **Laravel PHP framework** and **MySQL** as the database.
This project provides a **clean, secure, and well-structured foundation** to kickstart your backend development.

---

## ✨ Key Features

* **Laravel Framework** – Uses the latest stable version for rapid development and clean architecture.
* **MySQL Integration** – Pre-configured for high-performance and reliable data storage.
* **RESTful Design** – Follows standard REST conventions for predictable CRUD endpoints.
* **Authentication Ready** – Basic setup for API Token Authentication (Laravel Sanctum or Passport).
* **Clean Code** – Adheres to Laravel best practices for Controllers, Models, Routes, and Migrations.
* **Environment Configuration** – Simple `.env` setup for development, staging, and production.

---

## ⚙️ Prerequisites

Before you begin, make sure you have the following installed:

* PHP ≥ 8.0
* Composer
* MySQL Server
* Git

---

## 🛠️ Installation and Setup

Follow these steps to set up your development environment:

### 1. Clone the Repository

```bash
git clone https://github.com/siammahfuz/Laravel-api-using-mysql Laravel-API
cd Laravel-API
```

### 2. Install PHP Dependencies

```bash
composer install
```

### 3. Environment Configuration

```bash
cp .env.example .env
php artisan key:generate
```

### 4. Database Setup

Open `.env` and configure your MySQL credentials:

```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_db_name     # <-- CHANGE THIS
DB_USERNAME=your_db_user     # <-- CHANGE THIS
DB_PASSWORD=your_db_password # <-- CHANGE THIS
```

### 5. Run Migrations

```bash
php artisan migrate
# (Optional) Seed database with dummy data
php artisan db:seed
```

### 6. Start the Local Server

```bash
php artisan serve
```

Your API will now be available at:
👉 [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 💡 Usage and Structure

This boilerplate follows the standard **Laravel MVC structure**:

| Directory              | Purpose                                  |
| ---------------------- | ---------------------------------------- |
| `app/Models`           | Eloquent models for database interaction |
| `app/Http/Controllers` | Logic for processing API requests        |
| `database/migrations`  | Database schema definitions              |
| `routes/api.php`       | API endpoints and routing                |

**Example Endpoint:**

```bash
GET /api/user
```

---

## 🤝 Contributing

Contributions are welcome!
Here’s how you can help:

1. Fork the project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the **MIT License**.
See `LICENSE` for more details.

---

## 📧 Contact

**Md Mahfuzur Rahman Siam**
Software Engineer, Flexbit Solutions
📩 Email: [ksiam3409@gmail.com](mailto:ksiam3409@gmail.com)

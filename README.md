# 🌐 Top Outsourcing Partners (TOP)

[![Laravel](https://img.shields.io/badge/Laravel-11.x-red?style=flat&logo=laravel)](https://laravel.com/)
[![MySQL](https://img.shields.io/badge/Database-MySQL-blue?style=flat&logo=mysql)](https://www.mysql.com/)
[![Vite](https://img.shields.io/badge/Frontend-Vite-purple?style=flat&logo=vite)](https://vitejs.dev/)
[![Deployed on Railway](https://img.shields.io/badge/Hosting-Railway-black?style=flat&logo=railway)](https://railway.app/)

**Top Outsourcing Partners (TOP)** is a full-stack web platform built with **Laravel** and **MySQL**, designed to showcase outsourcing services, blog content, and team profiles.  
This project powers the official website of **[Top Outsourcing Partners](https://topoutsourcingpartners.com/)**, a global outsourcing solutions provider.  

---

## 🏢 About the Company
At **Top Outsourcing Partners (TOP)**, we help businesses achieve operational excellence through **innovative, cost-effective, and scalable outsourcing solutions**.  
Since inception, TOP has empowered organizations across the globe to **streamline operations, reduce costs, and focus on their core strengths** while we handle the rest.

---

## 🚀 Features
- ✅ **Dynamic Content Management** – Blogs, newsletters, and SEO-friendly pages.  
- ✅ **Newsletter System** – Subscription & automated welcome emails.  
- ✅ **SEO & Sitemap Generator** – Optimized metadata + automated sitemap.  
- ✅ **Team Management** – Showcase team members dynamically.  
- ✅ **Cloudinary Integration** – Image management for blogs & media.  
- ✅ **Authentication System** – Secure login and registration.  
- ✅ **Responsive Design** – Mobile-first, optimized with Tailwind & Vite.  
- ✅ **Deployment Ready** – Configured for **Railway + MySQL**.  

---

## 🛠️ Tech Stack
- **Backend:** Laravel 11 (PHP 8.x)  
- **Database:** MySQL (Railway-managed)  
- **Frontend:** Blade Templates, Tailwind CSS, JavaScript (Vite)  
- **Storage & Media:** Cloudinary, Laravel Storage  
- **Deployment:** Railway + GitHub Actions (optional CI/CD)  

---

## 📦 Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/ihkokil/TopOutsourcingPartners.git
cd TopOutsourcingPartners
```

### 2. Install PHP & Node Dependencies

```bash
composer install
npm install && npm run build
```

### 3. Environment Setup

Copy the example env and update credentials:

```bash
cp .env.example .env
```

Set your values:

* `DB_CONNECTION=mysql`
* `DB_HOST=your-db-host`
* `DB_DATABASE=your-db-name`
* `DB_USERNAME=your-db-user`
* `DB_PASSWORD=your-db-password`

### 4. Generate App Key

```bash
php artisan key:generate
```

### 5. Run Migrations & Seeders

```bash
php artisan migrate --seed
```

### 6. Start Development Server

```bash
php artisan serve
```

Now visit 👉 `http://localhost:8000`

---

## 📂 Project Structure (Highlights)

```
app/
 ├── Console/Commands/   # Custom Artisan commands (e.g., Sitemap generator)
 ├── Http/Controllers/   # Controllers for Blogs, Auth, Team Members, Newsletter
 ├── Models/             # Eloquent models (Blog, TeamMember, Subscriber, etc.)
 ├── Services/           # Cloudinary & Sitemap services
 └── Traits/             # Reusable model traits

resources/views/         # Blade templates (blogs, auth, team, layouts)
routes/                  # Web + console routes
public/                  # Public assets (CSS, JS, Images)
```

---

## 📬 Contact

👨‍💻 Developed by **Md. Iqbal Haider Khan (@ihkokil)**
🌍 [Portfolio / Website](https://www.linkedin.com/in/ihkokil/)

---

## 📄 License

This project is licensed under the **MIT License** – feel free to use and learn from it.
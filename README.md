# DataForge Quickstart: Try in 5 Minutes 🚀

## What is DataForge?  
DataForge is a **modular backend framework** for Laravel that simplifies **query management, entity handling, and API creation**—all with minimal effort. It removes the need for traditional ORM models and provides a dynamic, reusable SQL-based approach.

## Why Use DataForge?  
✅ **Faster Backend Development** – Auto-generated API endpoints 🔥  
✅ **Reusable SQL Queries** – No need to rewrite queries multiple times  
✅ **Dynamic Entity Handling** – Lazy-loading & seamless data fetching  
✅ **Prebuilt API Endpoints** – Instantly expose data with minimal setup  
✅ **Optimized Performance** – No ORM overhead, direct SQL execution ⚡  

## Get Started in 5 Minutes 🚀  

### 1️⃣ Clone the Quickstart Repo  
```bash
git clone https://github.com/Astra-Techno/dataforge-quickstart.git
cd dataforge-quickstart
```

### 2️⃣ Start the Laravel Project (Docker Recommended)  
```bash
cp .env.example .env
composer install
php artisan key:generate
docker-compose up -d
```

### 3️⃣ Run Database Migrations  
```bash
php artisan migrate
```

### 4️⃣ Test a Sample DataForge API Endpoint  
```bash
curl http://localhost/api/list/Product:list
```
Or open in a browser:  
[http://localhost/api/list/Product:list](http://localhost/api/list/Product:list)

### 5️⃣ Modify & Extend 🚀  
Explore `app/Sql` and `app/Entity` directories to see how queries and entities work. Modify them to fit your use case!

## 🔗 Next Steps  
- Read the **[Official Docs](https://data-forge.tech)** 📖  
- Join the **Community** for updates and discussions 🚀  
- Follow **@mjtech-dataforge** on Twitter for updates  

🔥 **Star the repo if you find this useful!** ⭐

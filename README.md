# 🏪 Directorio Comercial

Aplicación web desarrollada con **Laravel 11** para gestionar un directorio de comercios locales.  
Incluye administración de **categorías, comercios, productos y galerías de imágenes**, así como un slider principal en la página de inicio.

---

## 🚀 Requisitos previos

Antes de instalar, asegúrate de tener lo siguiente:

- PHP >= 8.2  
- Composer  
- MySQL o MariaDB  
- Node.js y NPM  
- Git (opcional, para clonar el repositorio)

---

## ⚙️ Instalación

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/directorio-comercial.git
cd directorio-comercial
````

### 2️⃣ Instalar dependencias PHP

```bash
composer install
```

### 3️⃣ Instalar dependencias de Node (opcional si usarás Vite o Mix)

```bash
npm install
```

### 4️⃣ Crear archivo `.env`

Copia el ejemplo:

```bash
cp .env.example .env
```

### 5️⃣ Configurar conexión a base de datos

Edita el archivo `.env` con tus credenciales MySQL:

```env
DB_DATABASE=directorio_comercial
DB_USERNAME=root
DB_PASSWORD=
```

### 6️⃣ Generar clave de aplicación

```bash
php artisan key:generate
```

### 7️⃣ Ejecutar migraciones (y seeders si existen)

```bash
php artisan migrate
php artisan db:seed
```

### 8️⃣ Ejecutar servidor local

```bash
php artisan serve
```

Luego abre en tu navegador:
👉 [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 🗂️ Estructura básica del proyecto

```bash
app/
├── Http/
│   └── Controllers/
│       ├── ComercioController.php
│       ├── CategoriaController.php
│       └── ...
├── Models/
│   ├── Comercio.php
│   ├── Categoria.php
│   └── ...
database/
├── migrations/
├── seeders/
public/
resources/
routes/
```

---

## 🧠 Tecnologías utilizadas

* **Laravel 11**
* **MySQL / MariaDB**
* **Bootstrap 5** (interfaz)
* **Vite / NPM** para compilación de assets
* **Eloquent ORM** para acceso a datos

---

## 👥 Autor
**Kevin Abel Venegas Bermúdez**
**Gerald**
**Jordi**
**Darwin**
Estudiante de Ingeniería en Sistemas – Universidad Nacional (Campus Sarapiquí)
Curso: *Fundamentos de Programación Web (EIF4280)*
Docente: *M.Sc. Olivier Blanco Sandí*
Período: II Ciclo 2025

---

## 📝 Licencia

Este proyecto se distribuye bajo la licencia [MIT](https://opensource.org/licenses/MIT).

---

<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
  </a>
</p>

<p align="center">
  <a href="https://github.com/laravel/framework/actions">
    <img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/l/laravel/framework" alt="License">
  </a>
</p>
```

---

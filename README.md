# Blank WordPress Template with ReactJS, Laravel, and WordPress Integration

This project is a **blank WordPress template** designed to help you kick-start your web development projects using **ReactJS** for the frontend, **Laravel** as the backend, and **WordPress** as a CMS (Content Management System). The goal is to provide a streamlined foundation for building a website with pre-configured settings, saving time and effort.

## 🚀 Features
- **ReactJS** for dynamic frontend development.
- **Laravel** backend integration.
- **WordPress** serves as the CMS with ACF, WP REST API, and Safe SVG plugins.
- **TailwindCSS** for utility-first styling.
- **Gulp** task runner for asset optimization.

## 🛠️ Requirements
To run this project, make sure you have the following:

- **Node.js**: Version 16 or above
- **PHP**: Version 7.4 or above
- **WordPress**: Latest version
- **Composer**: For managing Laravel dependencies
- **Gulp**: Task runner for automating tasks
- **MySQL**: Database for WordPress

## 📦 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/blank-wordpress-template.git
cd blank-wordpress-template

``` 
### 2. Install WordPress
- Download the latest version of WordPress.
- Extract it into your project directory.
- Configure the wp-config.php file with your database credentials.

### 3. Install Laravel (Backend)
- Go to the backend directory.

```bash
cd backend
composer install
cp .env.example .env
php artisan key:generate

```
### 4. Set Up ReactJS (Frontend)
- Go to the frontend directory:
```bash
cd frontend
npm install
npm start
```
### 5. Install WordPress Plugins
WP REST API: This will enable WordPress to interact with the React and Laravel setup.
ACF (Advanced Custom Fields): For creating custom content fields within WordPress.
Safe SVG: Allows the safe upload and use of SVG files in WordPress.
You can install these plugins directly via the WordPress admin dashboard or download and place them in the wp-content/plugins directory.

### 6 Install and Configure Gulp
Make sure Gulp is installed globally:
```bash
npm install -g gulp
```
- Run Gulp in the root directory:
````bash
gulp

````
### 7. Set Up TailwindCSS
Install TailwindCSS:
````bash

npm install -D tailwindcss
npx tailwindcss init

````
Configure tailwind.config.js to suit your project's needs.

### 8. Run the Project
Start Laravel using:

````bash
php artisan serve
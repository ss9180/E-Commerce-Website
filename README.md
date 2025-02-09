# E-commerce Website

A fully functional e-commerce website built using **HTML, CSS, JavaScript, PHP, and MySQLi** for database management.

## Features
- 📌 **Responsive Navigation Bar** with toggle effect
- 🎠 **Responsive Carousel** using Glide.js
- 📂 **Categories Section**
- 🆕 **New Arrival Products Section**
- 📩 **Contact Section**
- 🏁 **Footer Section**
- 📢 **Responsive Pop-Up**
- 🛍️ **Product Page** with pagination and sorting
- 🔍 **Product Details Page** with image zoom effect
- 🛒 **Cart Page**
- 🔑 **Responsive Login & Sign-Up Pages**

## Installation Guide

### Step 1: Install XAMPP
- Download and install **XAMPP** from [Apache Friends](https://www.apachefriends.org/).

### Step 2: Start XAMPP Services
- Open the **XAMPP Control Panel**.
- Start **Apache** and **MySQL** modules.

### Step 3: Create a Database
- Click the **Admin** button next to MySQL in the XAMPP Control Panel.
- You will be redirected to **phpMyAdmin**.
- Create a **new database** named **`ecommerce`**.

### Step 4: Create a Users Table
- Inside the `ecommerce` database, create a **new table** named **`users`** with **4 columns**:
  - `id` (Primary Key, Auto Increment)
  - `username` (VARCHAR)
  - `password` (VARCHAR)
  - `created_at` (TIMESTAMP)

### Step 5: Clone or Download the Project
- Clone this repository or download and extract it to the `htdocs` folder in XAMPP:
  ```sh
  cd C:\xampp\htdocs
  git clone https://github.com/ss9180/E-Commerce-Website 



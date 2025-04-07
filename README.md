# 📝 Blog Project

A modern and scalable **Blog Platform** built using **Laravel**. This project includes user authentication, article management, and a clean, responsive design.

This blog system allows users to read, create, edit, and comment on posts. Admins can manage the content, users, and settings from the **admin panel**.

---

## 🚀 Features

### 🌐 User Features
- **User Registration & Authentication** (Login, Register, Reset Password)
- **Article Management**: View, create, update, and delete blog posts
- **Comment System**: Readers can comment on articles
- **User Profiles**: Each user has a profile to view their posts and settings

### 🎛 Admin Features
- **Admin Panel**: Manage all users and articles
- **Role-Based Access Control (RBAC)**: Admin can assign roles to users
- **Content Moderation**: Admin can approve or delete comments
- **SEO Management**: Control meta tags for SEO optimization
- **Image Upload**: Integrated with custom image upload service

### 📧 Notifications
- **Email Notification**: Send email notifications to users for important updates
- **Comment Notification**: Notify users when someone comments on their posts

---

## 🛠 Technologies Used

```bash
# Backend
Laravel 11.x

# Frontend
Blade templates
Bootstrap 5

# Database
MySQL

# Authentication
Laravel Passport or Laravel Breeze for simple auth

# Image Handling
Intervention Image for image manipulation

# Notifications
Laravel Notifications (email, SMS)

# SEO
Slug generation via Laravel Slugify package

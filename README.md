# E-commerce Admin Dashboard

![License](https://img.shields.io/badge/License-MIT-lightgrey)
![Next.js](https://img.shields.io/badge/Next.js-13-blue)
![Prisma](https://img.shields.io/badge/ORM-Prisma-green)
![Database](https://img.shields.io/badge/Database-MySQL-yellow)
![UI](https://img.shields.io/badge/UI-ShadCN%20UI-brightgreen)

> **E-commerce Admin Dashboard** is a powerful and scalable platform designed to manage multiple e-commerce stores. Built with **Next.js**, **Prisma**, and **MySQL**, the dashboard provides features such as product management, order tracking, multi-store support, and Stripe payment integration.

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## 📦 Project Overview

The **E-commerce Admin Dashboard** enables e-commerce store owners to manage their online stores efficiently. This dashboard provides tools for product inventory management, sales tracking, multi-store administration, and order fulfillment.

With **multi-store support**, admins can handle different stores from a single dashboard, customizing each store's categories, billboards, and products. The dashboard also integrates with **Stripe** for payment processing, and features **Cloudinary** for image storage.

## 🚀 Features

- **Product Management**: Add, edit, and delete products. Manage sizes, colors, categories, and featured products.
- **Order Management**: Track orders, review details (total price, customer info, payment status), and manage archived products.
- **Multi-Store Support**: Manage multiple stores from a single dashboard with independent settings for each store.
- **Inventory Control**: Automatic archiving of products when they are out of stock to prevent overselling.
- **Billboard and Category Management**: Easily update billboards and categories with custom images and text.
- **Stripe Integration**: Handle payments securely through Stripe.
- **Cloudinary Integration**: Manage and upload product images through Cloudinary.
- **Dark Mode**: Switch between light and dark themes for the admin dashboard.

## 🛠 Technologies Used

- **Front-End**: 
  - [Next.js 13 (App Router)](https://nextjs.org) - A React framework with server-side rendering (SSR) and static site generation (SSG).
  - [Tailwind CSS](https://tailwindcss.com) - Utility-first CSS framework for styling.
  - [ShadCN UI](https://shadcn.dev) & [Radix UI](https://www.radix-ui.com/) - Modern UI libraries used for creating components in the dashboard.

- **Back-End**:
  - [Prisma](https://www.prisma.io) - A next-generation ORM used for database access with MySQL.
  - [Next.js API Routes](https://nextjs.org/docs/api-routes/introduction) - For managing server-side logic.

- **Database**:
  - **MySQL** hosted on **PlanetScale** - A scalable database for managing products, orders, and stores.

- **Storage**:
  - [Cloudinary](https://cloudinary.com) - A cloud service for managing images and media.

- **Payment Gateway**:
  - [Stripe](https://stripe.com) - A secure online payment system for processing orders.

## 📑 Setup and Installation

### Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js** (version 14 or above)
- **MySQL** or **PlanetScale** database setup
- **Stripe** account for payment processing
- **Cloudinary** account for managing images

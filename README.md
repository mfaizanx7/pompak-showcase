# PomPak Financial Literacy Platform

<div align="center">

### Government-backed Financial Education Platform

Backend development support for a national financial literacy platform built with Laravel and SQL Server, focusing on production support, feature enhancements, bug fixing, and enterprise software maintenance.

<br>

[![Laravel](https://img.shields.io/badge/Laravel-red?style=for-the-badge&logo=laravel)]
[![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver)]
[![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php)]
[![Portfolio](https://img.shields.io/badge/Portfolio-Case%20Study-111827?style=for-the-badge)](https://faizans-portfolio.vercel.app/)

</div>

---

# Overview

PomPak is a national financial literacy platform developed to promote financial education through interactive learning modules and digital educational content.

During my internship at the National Institute of Banking and Finance (NIBAF), I contributed to backend development by implementing feature enhancements, resolving production issues, testing application modules, and collaborating with senior developers within an enterprise Laravel codebase.

This project provided practical experience working on a large existing application rather than building a system from scratch.

---

# My Contribution

My responsibilities included:

- Supporting backend development
- Implementing feature enhancements
- Resolving reported backend issues
- Testing application modules
- Debugging production problems
- Working with SQL Server inside Laravel
- Collaborating with senior developers
- Maintaining existing functionality while introducing new changes

---

# Key Features

## Backend Support

- Feature enhancements
- Bug fixing
- Production issue resolution
- Module testing

---

## Enterprise Development

- Existing Laravel codebase
- Team collaboration
- Version control using Git
- SQL Server integration

---

## Database

- SQL Server
- Query debugging
- Database relationships
- Driver-specific implementation

---

# Project Screenshots

## Dashboard

![](Screenshot-1.png)

---

## Learning Modules

![](Screenshot-2.png)

---

## Administration

![](Screenshot-3.png)

---

## Platform

![](Screenshot-4.png)

---

# Technology Stack

## Backend

- Laravel
- PHP

## Database

- Microsoft SQL Server

## Version Control

- Git

## Development

- VS Code
- Composer

---

# High-Level Architecture

```text
Students
        │
        ▼
 Laravel Application
        │
 ┌──────┼────────────┐
 │      │            │
Modules Users     Reports
 │      │            │
 └──────┼────────────┘
        │
   SQL Server
        │
 Enterprise Database
```

---

# Installation

```bash
git clone https://github.com/mfaizanx7/pompak-showcase.git
```

```bash
composer install
```

```bash
cp .env.example .env
```

```bash
php artisan key:generate
```

```bash
php artisan serve
```

---

# Engineering Challenge

## Working with SQL Server in Laravel

Unlike previous projects that used MySQL, this platform was built on Microsoft SQL Server.

Several queries, date handling functions, and database behaviors differed from what I had previously experienced.

Understanding these differences while contributing to an existing enterprise application required careful testing and continuous learning.

---

# Solution

Before implementing changes, I reviewed the relevant Laravel SQL Server documentation and analyzed the existing implementation.

Every modification was tested before integration, ensuring compatibility with the existing production environment while minimizing the risk of introducing regressions.

---

# Lessons Learned

This internship significantly improved my understanding of enterprise software development.

Key takeaways included:

- Reading existing code before making changes
- Working within established coding standards
- Understanding SQL Server integration in Laravel
- Collaborating with senior developers
- Debugging production issues systematically
- Delivering incremental improvements instead of large rewrites

---

# Future Improvements

Potential future enhancements include:

- REST API integration
- Performance optimization
- Automated testing
- CI/CD pipeline
- Dockerized development environment
- Monitoring and logging

---

# Repository Notice

> **This repository is a portfolio showcase.**

The original PomPak source code is proprietary and cannot be shared publicly.

This repository documents my technical contribution, engineering experience, and the technologies used during the project without exposing confidential business logic or source code.

---

# Repository Status

| Status | Value |
|--------|-------|
| Project | Completed |
| Repository | Showcase |
| Source Code | Proprietary |
| Documentation | Complete |

---

# License

This repository is shared for portfolio purposes only.

---

# Author

## Muhammad Faizan Khan

Full-Stack Web Developer

Building production-ready web applications using Laravel, PHP, React.js, Node.js, and MySQL.

### Connect

Portfolio

https://faizans-portfolio.vercel.app

LinkedIn

https://linkedin.com/in/muhammad-faizan-khan-x7

GitHub

https://github.com/mfaizanx7

---

<div align="center">

### Thank you for visiting this repository.

⭐ If you found this project interesting, consider starring the repository.

</div>

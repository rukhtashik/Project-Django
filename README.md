# Project-Django
Food Ordering System(Информационная система заказов еды)

# 🍔 Food Ordering System

[![Django CI](https://github.com/yourname/food-ordering/actions/workflows/django.yml/badge.svg)](https://github.com/yourname/food-ordering/actions/workflows/django.yml)
[![Coverage](https://img.shields.io/badge/coverage-85%25-green)](https://github.com/yourname/food-ordering)
[![License](https://img.shields.io/badge/license-MIT-blue)](https://opensource.org/licenses/MIT)

Система онлайн-заказов еды для ресторанов с полным циклом от меню до аналитики.

## ✨ Особенности

- Онлайн-меню с категориями и фильтрами
- Корзина с онлайн-оплатой (Stripe)
- Личный кабинет с историей заказов
- Аналитика продаж
- REST API для мобильных приложений

## 🛠 Технологии

- **Backend**: Django 4.2, Python 3.10
- **Database**: SQLite
- **Frontend**: Bootstrap 5, HTMX
- **API**: DRF, Swagger
- **Инфраструктура**: Docker, Celery, Redis

## 🚀 Быстрый старт

```bash
# Установка
git clone https://github.com/yourname/food-ordering.git
cd food-ordering
cp .env.example .env
docker-compose up -d

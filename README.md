# 🛒 TechStore

**TechStore** — это современное веб-приложение интернет-магазина техники, разработанное с использованием **React**, **Node.js**, **Express** и **PostgreSQL**. Проект включает административную панель, корзину, JWT-аутентификацию и многое другое.

---

## 🚀 Стек технологий

### Клиентская часть:
- `React 17`
- `React Router DOM v6`
- `MobX`
- `React Bootstrap / Bootstrap 5`
- `Axios`
- `JWT Decode`
- `React UUID`

### Серверная часть:
- `Node.js + Express`
- `Sequelize + PostgreSQL`
- `JWT (jsonwebtoken)`
- `Bcrypt`
- `dotenv`
- `CORS`
- `Cookie-parser`
- `express-fileupload`

---

## 📦 Установка и запуск

### 1. Клонировать репозиторий
```bash
git clone https://github.com/your-username/TechStore.git
cd TechStore
````

### 2. Установка зависимостей

**Клиент:**

```bash
cd client
npm install
```

**Сервер:**

```bash
cd server
npm install
```

### 3. Создать `.env` файлы

Пример `.env` для `server/.env`:

```
PORT=5000
DB_NAME=your_db_name
DB_USER=your_db_user
DB_PASSWORD=your_db_password
DB_HOST=localhost
SECRET_KEY=your_jwt_secret
```

---

## ▶️ Запуск

**Сервер:**

```bash
cd server
npm run start-dev
```

**Клиент:**

```bash
cd client
npm start
```

---

## 📁 Структура проекта

```
TechStore/
├── client/        # React-приложение
│   ├── public/
│   └── src/
├── server/        # Node.js API
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── services/
│   └── static/
```

---

## 🔐 Функциональность

* Регистрация и вход с использованием JWT
* Панель администратора для управления товарами
* Загрузка изображений товаров
* Корзина пользователя
* Адаптивный интерфейс
* Разделение прав доступа
* Простая и расширяемая архитектура

---

## 📌 Планы на будущее

* Подключение оплаты
* Улучшенный поиск и фильтрация
* Докеризация проекта
* Покрытие тестами

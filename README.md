# Мировые достопримечательности API

## Описание проекта

Проект "Мировые достопримечательности" представляет собой веб-приложение для управления данными о мировых достопримечательностях с использованием **GraphQL**. Приложение позволяет добавлять, обновлять, удалять и получать информацию о достопримечательностях, таких как название, описание, страна, год постройки и изображение.

API реализовано с использованием **Node.js**, **Apollo Server** и **Express**. Для хранения данных используется **MySQL**.

## Инструкция по установке и запуску

### 1. Клонируйте репозиторий
Для начала, клонируйте репозиторий на ваш локальный компьютер:
```
git clone https://github.com/yourusername/landmark-api.git
cd landmark-api
```
-------------------------

### 1. Клонируйте репозиторий
```
npm install
```
-------------------------

### 1. Клонируйте репозиторий
```bash
const mysql = require('mysql2');

// Подключение к базе данных MySQL
const db = mysql.createConnection({
  host: 'localhost',      // адрес базы данных (можно использовать IP или localhost)
  user: 'root',           // ваш логин
  password: '',           // ваш пароль
  database: 'landmarks'   // имя базы данных
});
```
-------------------------

### 1. Клонируйте репозиторий
```bash
node index.js
```
-------------------------

### 1. Клонируйте репозиторий
```bash
http://localhost:4000/graphql
```
-------------------------

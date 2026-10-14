<div align="center">
  
  <img src="https://img.icons8.com/nolan/128/1A6DFF/C822FF/vinyl-record.png" alt="685 Music Logo" width="100"/>

  # 💿 685 Music Label | Экосистема для независимых артистов

  **Инновационная веб-платформа для дистрибуции музыки, управления роялти и питчинга.**

  [![Status](https://img.shields.io/badge/Status-Active-success.svg?style=for-the-badge)](#)
  [![Version](https://img.shields.io/badge/Version-1.0.0-blue.svg?style=for-the-badge)](#)
  [![License](https://img.shields.io/badge/License-Proprietary-red.svg?style=for-the-badge)](#)
  
  [Личный кабинет артиста](#) • [Панель модератора](#) • [Сайт лейбла](#)
  
  ---
</div>

## 🎵 О проекте

**685 Music Label** — это закрытая экосистема (SaaS-платформа), созданная для независимых музыкантов. Проект объединяет в себе функционал музыкального дистрибьютора, финансового трекера и умного ассистента. Архитектура построена на бессерверных технологиях (Serverless) с использованием **Firebase** и стильного Glassmorphism-дизайна (HTML/CSS/JS).

<br>

## ✨ Ключевые возможности

### 👤 Для артистов (`index.html`)
* **Дистрибуция релизов:** Удобная форма отгрузки треков (Сингл, EP, Альбом) с указанием метаданных (Текст, Авторы, Маркировки, Таймкоды TikTok).
* **Мониторинг финансов:** Просмотр баланса, история транзакций и подача заявок на вывод роялти (Банковская карта, СБП, Реквизиты).
* **Умный AI-Питчинг:** Встроенный нейросетевой алгоритм, который генерирует профессиональный пресс-релиз для редакторов площадок на основе метаданных трека.
* **Live-чат поддержки:** Система обратной связи с администрацией в реальном времени.
* **Тарифная сетка:** Интеграция с эквайрингом **ЮKassa** для оформления подписок и система подарочных промокодов.

### 🛡️ Для модераторов (`admin.html`)
* **Модерация контента:** Удобная канбан-подобная сетка заявок с возможностью одобрять, отклонять (с указанием причины) или удалять релизы.
* **Финансовый модуль:** Начисление роялти на баланс артистов в 2 клика.
* **Управление выплатами:** Отдельная панель для проверки заявок на вывод средств и их одобрения/отклонения.
* **Управление пользователями:** Блокировка (Ban), заморозка (Freeze), сброс/выдача тарифов.
* **Генератор промокодов:** Создание кодов на скидку (%) или подарочных тарифов с таймером истечения.
* **Экспорт базы данных:** Выгрузка всех данных о релизах и авторах в удобном `.csv` формате для дистрибьютора.

<br>

## 🛠️ Технологический стек

<div align="center">
  
| Frontend | Backend & BaaS | Integrations |
| :---: | :---: | :---: |
| ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) <br> ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) <br> ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) | ![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase) <br> **Firestore** (NoSQL Database) <br> **Firebase Authentication** | ![YooKassa](https://img.shields.io/badge/YooKassa-API-black?style=for-the-badge) <br> **GitHub Pages** (Hosting) |

</div>

<br>

## 📂 Структура проекта

```bash
📦 685-music-platform
 ┣ 📜 index.html         # Основной клиент (Личный кабинет артиста)
 ┣ 📜 admin.html         # Панель управления (Dashboard для модераторов)
 ┣ 📜 offer.html         # Документ: Публичная оферта
 ┣ 📜 privacy.html       # Документ: Политика конфиденциальности
 ┣ 📜 favicon.ico        # Иконка сайта
 ┗ 📜 README.md          # Документация проекта

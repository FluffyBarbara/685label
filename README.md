<div align="center">
  
  <!-- Векторный 3D-стилизованный логотип 685 Music (Никогда не сломается) -->
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 120 120" width="120" height="120">
    <defs>
      <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#ffffff" />
        <stop offset="50%" stop-color="#888888" />
        <stop offset="100%" stop-color="#111111" />
      </linearGradient>
      <linearGradient id="rainbow" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#1A6DFF" />
        <stop offset="50%" stop-color="#C822FF" />
        <stop offset="100%" stop-color="#ff3b30" />
      </linearGradient>
    </defs>
    <!-- Пластинка -->
    <circle cx="60" cy="60" r="55" fill="#0d0d0d" stroke="url(#rainbow)" stroke-width="2.5" />
    <circle cx="60" cy="60" r="48" fill="none" stroke="#222" stroke-width="1" />
    <circle cx="60" cy="60" r="40" fill="none" stroke="#2c2c2c" stroke-width="1.5" />
    <circle cx="60" cy="60" r="32" fill="none" stroke="#1f1f1f" stroke-width="1" />
    <!-- Яблоко пластинки -->
    <circle cx="60" cy="60" r="22" fill="#151515" stroke="url(#rainbow)" stroke-width="1.5" />
    <!-- Текст 685 -->
    <text x="60" y="58" font-family="'Plus Jakarta Sans', 'Arial Black', sans-serif" font-weight="900" font-size="10" fill="#ffffff" text-anchor="middle" letter-spacing="1">685</text>
    <text x="60" y="68" font-family="'Plus Jakarta Sans', sans-serif" font-weight="800" font-size="5" fill="#888888" text-anchor="middle" letter-spacing="1.5">MUSIC</text>
    <!-- Центр пластинки -->
    <circle cx="60" cy="60" r="3.5" fill="#000000" />
    <circle cx="60" cy="60" r="1.2" fill="#ffffff" />
  </svg>

  # 💿 685 Music Label | Экосистема для независимых артистов

  **Инновационная веб-платформа для дистрибуции музыки, управления роялти и питчинга.**

  [![Сайт](https://img.shields.io/badge/Сайт-685musiclabel.com-white.svg?style=for-the-badge&logo=google-chrome&logoColor=black)](https://685musiclabel.com)
  [![Status](https://img.shields.io/badge/Статус-В_сети-success.svg?style=for-the-badge)](https://685musiclabel.com)
  [![Version](https://img.shields.io/badge/Версия-1.0.0-blue.svg?style=for-the-badge)](#)
  [![License](https://img.shields.io/badge/Лицензия-Proprietary-red.svg?style=for-the-badge)](#)
  
  ### [🚪 Личный кабинет артиста](https://685musiclabel.com) • [💻 Панель модератора](https://685musiclabel.com/admin.html) • [📄 Сайт лейбла](https://685musiclabel.com)
  
  ---
</div>

## 🎵 О проекте

**685 Music Label** — это закрытая экосистема (SaaS-платформа), созданная для независимых музыкантов. Проект объединяет в себе функционал музыкального дистрибьютора, финансового трекера и умного ассистента. Архитектура построена на бессерверных технологиях (Serverless) с использованием **Firebase** и стильного Glassmorphism-дизайна (HTML/CSS/JS).

<br>

## ✨ Ключевые возможности

### 👤 Для артистов ([`index.html`](./index.html))
* **Дистрибуция релизов:** Удобная форма отгрузки треков (Сингл, EP, Альбом) с указанием метаданных (Текст, Авторы, Маркировки, Таймкоды TikTok).
* **Мониторинг финансов:** Просмотр баланса, история транзакций и подача заявок на вывод роялти (Банковская карта, СБП, Реквизиты).
* **Умный AI-Питчинг:** Встроенный нейросетевой алгоритм, который генерирует профессиональный пресс-релиз для редакторов площадок на основе метаданных трека.
* **Live-чат поддержки:** Система обратной связи с администрацией в реальном времени.
* **Тарифная сетка:** Интеграция с эквайрингом **ЮKassa** для оформления подписок и система подарочных промокодов.

### 🛡️ Для модераторов ([`admin.html`](./admin.html))
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
 ┣ 📜 index.html         # Основной клиент (Личный кабинет артиста) -> [https://685musiclabel.com](https://685musiclabel.com)
 ┣ 📜 admin.html         # Панель управления (Dashboard для модераторов) -> [https://685musiclabel.com/admin.html](https://685musiclabel.com/admin.html)
 ┣ 📜 offer.html         # Документ: Публичная оферта -> [https://685musiclabel.com/offer.html](https://685musiclabel.com/offer.html)
 ┣ 📜 privacy.html       # Документ: Политика конфиденциальности -> [https://685musiclabel.com/privacy.html](https://685musiclabel.com/privacy.html)
 ┣ 📜 favicon.ico        # Иконка сайта
 ┗ 📜 README.md          # Документация проекта

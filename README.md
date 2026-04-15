# 🐂🐄 Bulls & Cows Telegram Bot

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Telegram](https://img.shields.io/badge/Python-Telegram-Bot-22.6-blue)
![Database](https://img.shields.io/badge/SQLite-aisqlite-green)
![License](https://img.shields.io/badge/python-dotenv-1.0-yellow)

Telegram-бот для гри **«Бики та Корови»** з базою даних, статистикою та адмін-панеллю.

---

## 🎮 Опис

Це інтерактивний Telegram-бот, який дозволяє грати в класичну гру:

- 🤖 Бот загадує 4-значне число з унікальними цифрами  
- 🐂 Бик — цифра на правильній позиції  
- 🐄 Корова — цифра є, але не на своєму місці  
- 📊 Вся статистика зберігається в базі даних  

---

## 🚀 Функціонал

### 👤 Для гравців
- 🎮 Нова гра  
- 🏳️ Здатися  
- 📊 Персональна статистика  
- 🏆 Таблиця лідерів  
- 🔢 Inline-кнопки  

### 👑 Для адміністратора
- 👥 Перегляд всіх користувачів  
- 📈 Загальна статистика  
- 🔧 Призначення адмінів  
- 🧹 Скидання статистики  

---

## 🛠️ Технології

- Python 3.10+  
- python-telegram-bot  
- aiosqlite  
- SQLite  

---

## 📦 Встановлення

```bash
git clone https://github.com/your-username/bulls-cows-bot.git
cd bulls-cows-bot
pip install -r requirements.txt

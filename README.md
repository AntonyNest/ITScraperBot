 # ITScraperBot

---
Цей проєкт – Telegram-бот для моніторингу IT-вакансій з сайтів work.ua, rabota.ua, dou.ua та візуалізації змін зарплат за напрямками та мовами програмування.

## Функціонал
- Парсинг IT-вакансій з популярних ресурсів.
- Збереження даних у базі даних (SQLite).
- Перегляд останніх вакансій через Telegram-бот.
- Побудова та відправка графіків зміни зарплат у часі.

## Вимоги
- Django==4.2
- aiogram==3.0.0
- requests==2.31.0
- beautifulsoup4==4.12.2
- lxml==4.9.3
- matplotlib==3.7.1
- python-dotenv==1.0.0
- pandas==2.0.3
- `pip` для встановлення пакетів

## Встановлення
1. Клонуйте репозиторій:
   ```bash
   git clone <https://github.com/AntonyNest/ITScraperBot.git>install dependencies:
   
2. ip install -r requirements.txt
    - Start the FastAPI server:
3. Run the Telegram bot:
   - python app/bot.py

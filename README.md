# ITScraperBot

---

## A Web scraping project based on telegramBot to scrape the data from the websites.
This project is based backend combined with a Telegram bot to provide users with information search functionality. It scrapes job parameters listings from various websites and delivers them to users directly through Telegram. App scans job sites (work.ua, rabota.ua) and displays the results according to selected parameters.

---
### Stucture 

### Functionality (Use cases):
**Telegram Bot**:
- Search for jobs using keywords;
- Filter jobs by location, salary, or company;
- Displaying information in some views;
- Save favorite jobs.

**FastAPI Backend**:
- Real-time job scraping vacancies from certain sources;

### Technologies:
- telegrambot
- 
- BeautifulSoup

## Installation
1. Clone the repository:
git clone https://github.com/AntonyNest/fastWorkScraper.git
2. install dependencies:
- pip install -r requirements.txt
3. Start the FastAPI server:
- uvicorn app.main:app --reload
4. Run the Telegram bot:
- python app/bot.py




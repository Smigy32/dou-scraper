# DOU Scraper

DOU Scraper - це проєкт, який надає можливість отримати дані з сайту [DOU](https://dou.ua/) (український ресурс для професіоналів з сфери розробки програмного забезпечення). Цей скрапер дозволяє отримувати інформацію про вакансії, що публікуються на DOU.

## Властивості

- Отримання даних про вакансії: назва, посилання, назва компанії.
- Завантаження отриманних даних в .csv файл

## Вимоги

Для використання DOU Scraper потрібно мати встановлені наступні компоненти:

- Python 3.10
- Бібліотеки, вказані у `requirements.txt`
- Chrome веб-браузер версії 114.0.5735.198

## Встановлення

1. Склонуйте репозиторій:

   ```bash
   git clone https://github.com/Smigy32/dou-scraper.git
   ```

2. Перейдіть до директорії проекту:

   ```bash
   cd dou-scraper
   ```

3. Створіть віртуальне оточення та активуйте його:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

4. Встановіть залежності:

   ```bash
   pip install -r requirements.txt
   ```

## Використання

Для використання DOU Scraper необхідно запустити `run.py`:

```bash
python run.py
```
Після чого достатньо перейти за посиланням http://127.0.0.1:5000/

За змовчуванням програма використовує **Seleninum** як скрепінг технологію.
Якщо Ви хочете використовувати **Scrapy**, то перейдіть за посиланням  http://127.0.0.1:5000/?debug=1 та оберить **Scrapy** в дропдауні


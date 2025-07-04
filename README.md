# AIAssistant

Цей бот — AI-помічник майстра з ремонту ноутбуків, який допомагає користувачам з діагностикою проблем, консультаціями і пропонує звернутися до сервісу.

## Функції

- Приймає запити користувачів у Telegram
- Взаємодіє з AI через DeepInfra API для генерації відповідей
- Надсилає дані у Google Таблиці через Make (Integromat)
- Надає користувачам актуальну інформацію, яка стосується технічного та опраційного обстуговування, продажу та купівлі ноутбуків і комплектуючих
- Логіка роботи бота налаштована через промпти
- Власник боту може завантажувати інформацію в гугл таблиці, а також керувати своїм графіком роботи, відповідно до якого бот має свої налаштування

## Встановлення

1. Клонуй репозиторій:

   ```bash
   git clone https://github.com/svitlanahavrylets/telegram-ai-bot.git
   cd telegram-ai-bot
   ```

2. Встанови залежності:

npm install

3. Створи .env файл з такими змінними:

TELEGRAM*TOKEN=токен*твого_бота
DEEPINFRA_API_KEY=токен_DeepInfra

4. Запусти бота:

npm run dev

## Використання

- Знайди бота в Telegram за юзернеймом [@your_ai_assistant_and_helper_bot](https://t.me/your_ai_assistant_and_helper_bot)
- Почни спілкування, щоб отримати допомогу від AI
- Бот задаватиме уточнюючі питання та даватиме поради
- У разі складних випадків, бот радить звернутися до сервісу

## Безпека

- Не додавайте у репозиторій .env з токенами
- Використовуйте .gitignore для виключення конфіденційних файлів

## Ліцензія

MIT

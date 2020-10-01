# Проект CatBot

Это бот для Telegramm, который присылает пользователю котиков.

## Установка

1. Клонируйте репозиторий с Github.
2. Создайте виртуальное окружение.
3. Установите зависимости 'pip install -r requirements.txt'
4. Создайте файл 'settings.py'
5. Впиите в settings.py переменные:
```
API_KEY = "API - ключ бота"
PROXY_URL ="адрес прокси" 
PROXY_USERNAME = "логин из прокси"
PROXY_PASSWORD = "пароль на прокси"
USER_EMOJI = [':smiley_cat:', ':smiling_imp:', ':panda_face:', ':dog:']
```
6. Запустите бота командой 'python bot.py'
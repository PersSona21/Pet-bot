python version **3.12.4**
Чтобы установить все зависимости:

Eсли unix:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Если Windows:

```cmd
python -m venv .venv
.venv/bin/activate.bat
pip install -r requirements.txt
```

Делать бота будем с помощью библиотеки [python-telegram-bot](https://python-telegram-bot.org/) используя [Telegram Bot API](https://core.telegram.org/bots/api)
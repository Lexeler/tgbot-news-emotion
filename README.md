# Бот-анализатор эмоций в новостях 🤖📰

Телеграм-бот для анализа эмоциональной окраски новостей с Lenta.ru с использованием ИИ и визуализацией результатов.



## Возможности ✨
- 📅 Сбор новостей по дате/периоду
- 🤖 Классификация эмоций с помощью ИИ (агрессия, тревожность, сарказм, позитив, нейтрально)
- 📊 Графики распределения эмоций
- ⏳ Отслеживание прогресса с индикацией эмодзи
- 🔗 Прямые ссылки на новости с контекстом

## Установка 🛠️

### Требования
- Python 3.8+
- Аккаунт в Telegram
- Токен бота от [@BotFather](https://t.me/botfather)

### Настройка
1. Клонируйте репозиторий:
```bash
git clone https://github.com/yourusername/news-emotion-bot.git
cd news-emotion-bot
```

2. Установите зависимости:
```bash
pip install -r requirements.txt
```

3. Укажи телеграм токен:
```ini
API_TELEGRAM_TOKEN=ваш_токен_бота
```

4. Запустите бота:
```bash
python main.py
```

## Использование 🚀

### Команды
- `/start` — Запуск бота и получение инструкций
- `/help` — Справка по использованию
- `ДД-ММ-ГГГГ` — Анализ новостей за конкретную дату
- `ДД-ММ-ГГГГ ДД-ММ-ГГГГ` — Анализ за период

### Пример работы
1. Отправьте дату `15-03-2024`
2. Бот соберет новости с Lenta.ru
3. ИИ проанализирует эмоциональный контекст
4. Получите интерактивный график
5. Выбирайте эмоции для просмотра связанных новостей

Для изменения списка эмоций отредактируйте:
```python
CANDIDATE_LABELS = ["агрессия", "тревожность", "сарказм", "позитив", "нейтральное состояние"]
```

# Видеоплеер

Простой видеоплеер на HTML, CSS и JavaScript с использованием библиотеки Playable.
<img width="1013" height="764" alt="image" src="https://github.com/user-attachments/assets/ec87b538-7376-4ebd-9857-6a396b5f3cfa" />

## Демо

[Открыть плеер](https://olenevoid.github.io/devman-videoplayer/)

## Возможности

- Воспроизведение видео
- Пауза
- Включение/выключение звука
- Полноэкранный режим
- Прогресс-бар с перемоткой
- Отображение текущего времени и длительности

## Запуск

Требуется Python 3.12+.

```bash
pip install -r requirements.txt
python main.py
```

После запуска перейдите по адресу [http://127.0.0.1:5500](http://127.0.0.1:5500) в браузере.

## Структура

```
static/              — CSS, JS и шрифты
  fonts/             — иконки Font Awesome
  player.js          — логика плеера
  style.css          — стили
index.html           — главная страница
main.py              — сервер с автоперезагрузкой
```

## Технологии

- Python, Playable.js, jQuery, Font Awesome, LiveReload

## Разработка

Для форматирования и линтинга используется `requirements-dev.txt` — зависимости, которые нужны только при разработке (flake8, black, isort, pre-commit, djlint). Они не устанавливаются при деплое.

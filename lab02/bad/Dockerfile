# Плохая практика №1: Использование latest тега
FROM ubuntu:latest

# Плохая практика №2: Установка всех зависимостей в одном слое
RUN apt-get update && apt-get install -y \
    python3 \
    && rm -rf /var/lib/apt/lists/*

# Плохая практика №3: Использование ROOT пользователя
USER root

# Плохая практика №4: Не указание рабочей директории
COPY . .

# Плохая практика №5: Запуск приложения от root пользователя
CMD ["python3", "app.py"]


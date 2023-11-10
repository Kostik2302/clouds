# Используем конкретный тег Ubuntu, а не latest
FROM ubuntu:18.04

# Устанавливаем зависимости в нескольких слоях для оптимизации кэширования
RUN apt-get update && \
    apt-get install -y python3 && \
    rm -rf /var/lib/apt/lists/*

# Создаем пользователя и группу с необходимыми правами
RUN groupadd -r myuser && useradd -r -g myuser myuser

# Устанавливаем рабочую директорию и назначаем пользователя
WORKDIR /app
USER myuser

# Копируем только необходимые файлы, чтобы избежать копирования лишних данных
COPY --chown=myuser:myuser . .

# Задаем точку входа с использованием не-root пользователя
CMD ["python3", "app.py"]

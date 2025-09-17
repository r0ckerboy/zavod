# Используем версию на основе Alpine, в которой точно есть 'sh' и 'apk'
FROM n8nio/n8n:1.22.1-alpine

# Переключаемся на root для установки зависимостей
USER root

# Установка системных зависимостей
RUN apk add --no-cache ffmpeg git

# Возвращаемся на безопасного пользователя node
USER node

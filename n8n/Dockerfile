# Базовый образ n8n (основан на Alpine Linux)
FROM n8nio/n8n:latest

# Переключаемся на root для установки зависимостей
USER root

# Установка системных зависимостей через apk
RUN apk add --no-cache ffmpeg git

# Возвращаем пользователя node для безопасности
USER node

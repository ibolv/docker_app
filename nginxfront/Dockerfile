# Используем официальный образ Nginx
FROM nginx:latest

# Копируем конфигурационный файл в контейнер
COPY app.conf /etc/nginx/conf.d/default.conf

# Копируем статические файлы (если есть)
# COPY ./your_static_files /usr/share/nginx/html

# Открываем порт 9500
EXPOSE 9500
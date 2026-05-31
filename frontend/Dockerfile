FROM nginx:alpine

# Копируем статические файлы
COPY index.html /usr/share/nginx/html/
COPY request.html /usr/share/nginx/html/

# Копируем конфиг nginx
COPY nginx.conf /etc/nginx/conf.d/default.conf

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
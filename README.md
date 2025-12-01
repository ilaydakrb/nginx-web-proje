# Nginx Web Sunucusu - Docker Projesi

Bu proje, Docker container içinde Nginx ile basit bir index.html sayfasını çalıştırır.

## Docker Build
docker build -t nginx-web .

## Docker Run
docker run -p 8080:80 nginx-web

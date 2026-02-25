

# 1. Pull image nginx
docker pull nginx:alpine

# 2. Jalankan container dengan nama
docker run -d --name web-praktikum -p 8080:80 nginx:alpine

# 3. Akses di browser: http://localhost:8080

# 4. Lihat logs container
docker logs web-praktikum

# 5. Masuk ke dalam container
docker exec -it web-praktikum sh

# Di dalam container, coba:
ls -la /usr/share/nginx/html
cat /etc/nginx/nginx.conf
exit

# 6. Stop dan hapus container
docker stop web-praktikum
docker rm web-praktikum

# 7. membuat docker image
mkdir -p ~/praktikum-docker/app
cd ~/praktikum-docker

# 8. Build image
docker build -t praktikum-docker:v1 .

# 9. Jalankan container
docker run -d -p 8080:80 --name praktikum-web praktikum-docker:v1

# 10. Akses di browser: http://localhost:8080

# 11.Jalankan semua services
docker compose up -d

# 12.Cek status
docker compose ps

# 13.Lihat logs
docker compose logs -f

# Akses web: http://localhost:8080
# Akses api: http://localhost:8081

# 14. Cleanup
docker compose down -v

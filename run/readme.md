# Penggunaan RUN
docker run --name <nama> -d -e PMA_HOST=<ip> -e PMA_PORT=3306 -e PMA_USER=<user> -e PMA_PASSWORD=<passwd> -p <port_akses>:<port_docker> phpmyadmin
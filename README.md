# Proyek PHP dengan Docker

Repositori ini berisi proyek PHP yang disiapkan untuk dijalankan di dalam kontainer Docker. Berikut adalah instruksi untuk mengatur dan menjalankan proyek menggunakan Docker.

## Prasyarat

- Pastikan Anda telah menginstal [Docker](https://www.docker.com/get-started) di mesin Anda.
- Pastikan Anda telah menginstal [Docker Compose](https://docs.docker.com/compose/install/).

## Memulai

Ikuti langkah-langkah berikut untuk menyiapkan dan menjalankan aplikasi PHP Anda dalam kontainer Docker.

### 1. Kloning Repositori
git clone https://github.com/caesarars/backend_php.git

file ada di dalam folder

### 2. Docker
docker build -t my-php-project .

docker-compose up


akan ada di PORT : 

http://localhost:8082 untuk php

http://localhost:8083 untuk phpmyAdmin

http://localhost:3306 untuk mysql


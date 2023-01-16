# Docker-WordPress-SSL
WordPress + MySQL + phpMyAdmin + Nginx + SSL - CMS - Docker-compose

WordPress + MySQL + phpMyAdmin + Nginx + SSL - CMS - Docker-compose

Akses  "localhost:80"

phpMyAdmin - lihat "localhost:8080"

Ubah baris 23 dan 24 dari docker-compose.yml:

23 VIRTUAL_HOST: domainAnda.com #harus merupakan domain yang valid dan DNS yang mengarah ke server ini 24 LETSENCRYPT_HOST: domainAnda.com #harus merupakan domain yang valid dan DNS yang mengarah ke server ini


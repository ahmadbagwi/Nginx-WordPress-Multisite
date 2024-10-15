# Nginx Configuration for WordPress Multisite Subdirectories
WordPress Multisite adalah fitur dimana website dapat memiliki anak atau turunan dari website utama, dengan fitur Multisite setiap turunan dari website utama memiliki halaman admin tersendiri dan dapat dikelola secara mandiri.
Nginx adalah web server yang memiliki kelebihan cepat dan berfungsi sebagai proxy.

Pada repository ini terdapat konfigurasi standar Nginx yang dapat digunakan untuk website berbasis WordPress Multisite dengan fitur Subdirectories.
## Contoh
### Copy file
```
sudo cp dev-kbd /etc/nginx/sites-available/
sudo cp restrictions.conf /etc/nginx/global/
```
### Link file
```
sudo ln -s /etc/nginx/sites-available/dev-kbd /etc/nginx/sites-enabled/
```
### Restart
```
sudo nginx -t
sudo service nginx restart
```

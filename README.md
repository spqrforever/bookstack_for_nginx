# Install BookStack with Nginx
1. Copy bookstack.sh in Home directory
2. chmod a+x bookstack.sh
3. install Nginx, MySQL server and MySQL client
4. Copy server.conf in /etc/nginx/sites-available
5. Create symbol link

sudo ln -s /etc/nginx/sites-available/server.conf /etc/nginx/sites-enabled

6. restart Nginx service
7. sudo ./bookstack.sh
8.  cd /var/www/html
9.  sudo chmod -R 755 bookstack
10.  sudo chown -R www-data:www-data nextcloud

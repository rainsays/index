# index
```
git clone https://github.com/rainsays/index
chmod -R 777 index
docker run  -d --name=ls  --restart=unless-stopped -p 8000:8080 -v /root/index:/var/www/html -v  /mnt/downloads:/var/www/html/od/downloads   -v "/root/index/php8/:/etc/php8/"  trafex/php-nginx
--privileged 
```

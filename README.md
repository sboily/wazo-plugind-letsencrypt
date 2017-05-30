Add let's encrypt certificate.

    /opt/letsencrypt/letsencrypt-auto certonly --rsa-key-size 4096 --webroot --webroot-path /var/www/html/ -d demo.wazo.community

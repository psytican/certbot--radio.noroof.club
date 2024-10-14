# certbot--radio.noroof.club

1. docker compose up -d
2. docker exec -it certbot--radio-noroof-club--certbot certbot certonly --webroot --webroot-path=/var/www/certbot -d radio.noroof.club --email ev.panov@gmail.com --agree-tos --no-eff-email
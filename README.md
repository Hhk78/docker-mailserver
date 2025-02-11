```bash
python3 -m http.server --bind 0.0.0.0 80 &
certbot certonly --webroot -w . -d mail.31.com
killall python3
```

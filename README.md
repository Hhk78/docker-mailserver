```bash
python3 -m http.server --bind 0.0.0.0 80 &
certbot certonly --webroot -w . -d mail.31.com
killall python3
apk add py3-pip
rm /usr/lib/python3.12/EXTERNALLY-MANAGED
pip install --upgrade certbot josepy acme

```

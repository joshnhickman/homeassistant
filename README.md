## http

### letsencrypt
```bash
sudo certbot renew
```

### old
```bash
openssl req -sha256 -newkey rsa:4096 -nodes -keyout privkey.pem -x509 -day 730 -out certificate.pem
```


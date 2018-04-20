# docker-nginx
通过docker-compose使用nginx服务器



### create key

```
cd keys
openssl req -x509 -nodes -days 3650 -newkey rsa:2048 -subj "/CN=xxxx/O=xxxxx/C=JP" -keyout ./certificate.key -out ./certificate.crt

```


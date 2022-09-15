# Simple Ghost CMS by Docker Compose

## step to run

### 1. update env
```
DOMAIN=<yours domain>
DB_PASSWORD=<database password>
```

### 2. add ssl
create directory `ssl`
in ssl directory add 2 files

`ssl.crt` (ssl certified)

`ssl.key` (ssl key)

### 3. running
```
docker-compose up -d
```
# Dockerize Codeigniter App With docker-compose

## Test Running Application

```sh
## runing with docker compose
docker-compose -f docker-compose.yml up --build
# or run in background process 
docker-compose -f docker-compose.yml up --build -d
# or rebuild
docker-compose up --build --force-recreate --no-deps
```
```sh
app running in port 8181 ---> cek in browser
```
```sh
phpmyadmin running in port 8282 ---> cek in browser
```
```sh
login with username `ci` and password `ci`
```

## env-in-CodeIgniter
- https://github.com/technoknol/env-in-CodeIgniter

$host = $_ENV['DB_HOST'];
$username = $_ENV['DB_USERNAME'];
$password = $_ENV['DB_PASSWORD'];

env('MY_VARIABLE');

## link de erros
- https://www.canalti.com.br/programacao/web/php/codeigniter/corrigindo-erro-de-session-mkdir-invalid-path-no-codeigniter/

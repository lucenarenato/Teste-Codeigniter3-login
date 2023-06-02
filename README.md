# TESTE DEV - Codeigniter 3 (Many Minds)

## Dockerize Codeigniter App With docker-compose

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
app running in port 80 ---> cek in browser
```
```sh
phpmyadmin running in port 8282 ---> cek in browser
```
```sh
login with username `root` and password `password`
```
## Login
- 'admin@example.com', '123456'
## Uso de Biblioteca -  CodeIgniter-Aauth

- https://github.com/emreakay/CodeIgniter-Aauth/wiki/2)-Installation-and-Configuration

```
 'max_login_attempt'              => 3,
 'max_login_attempt_time_period'  => "5 minutes",
```

## env-in-CodeIgniter
- https://github.com/technoknol/env-in-CodeIgniter

$host = $_ENV['DB_HOST'];
$username = $_ENV['DB_USERNAME'];
$password = $_ENV['DB_PASSWORD'];

env('MY_VARIABLE');

## link de erros
- https://www.canalti.com.br/programacao/web/php/codeigniter/corrigindo-erro-de-session-mkdir-invalid-path-no-codeigniter/

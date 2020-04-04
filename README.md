# Docker Compose Laravel
Docker compose para laravel con phpmyadmin
### Requisitos
* Docker
* Docker compose
### Pasos
1. Crear carpeta `src`
2. `cd src`
3. agregar todos los archivos de tu aplicacion laravel
4. chmod +x artisan
5. sudo chmod 777 -R storage/
6. `docker-compose up -d --build`

App
* http://localhost:8080

Phpmyadmin
* http://localhost:8000/
### Comandos
* `docker-compose run --rm composer update`
* `docker-compose run --rm artisan migrate`

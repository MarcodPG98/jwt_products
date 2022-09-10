ejecutar los siguientes comandos

#1  composer require tymon/jwt-auth 

    o   composer require tymon/jwt-auth --ignore-platform-reqs

nota: el segundo por si hay problema al instalar jwt

#2 Generate JWT Secret

    php artisan jwt:secret

#3 Generate project key

    php artisan key:generate
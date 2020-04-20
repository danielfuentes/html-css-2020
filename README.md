# html-css-2019-II-migrar-a-laravel
Código HTML + CSS muy sencillo para migrar al Framework Laravel


## Amigas y amigos

Este constituye un código desarrollado con HTML + CSS, con la intención que el mismo lo puedas descargar y luego migrar todo al Framework Laravel.

## Recomendaciones para migrar a Laravel, luego de haber descargado este Proyecto:

- Crear una carpeta donde tendás tu proyecto de Laravel
- Te debes pasar a esa carpeta (cd laravel)
- Ejecutar el comando: composer create-project laravel/laravel proyecto
- Ahora debes ingresar a esa carpeta que ahora contiene tu proyecto de arranque en Laravel - (cd proyecto)
- Debes editar el archivo .env y allí debes crear la conexión a la Base de Datos, aquí puedes colocar cualquier nombre en base a tu proyecto deseado
- Si no tienes en el archivo .env el APP KEY, debes ejecutar el comando: php artisan key:generate

## Ahora vamos a ejecutar la creación de nuestra autenticación (Registro y Login) - Tal como lo ofcrece de manera automática Laravel

- Ejecutar el comando: composer require ui
- Ejecutar el comando: php artisan ui vue --auth

## Si en tu equipo no posees NODEJS, debes instalarlo, si tu sistema operativo es Windows: https://nodejs.org/es/download/ Si en el caso contrario posees Linux, sólo debes ejecutar el comando: sudo apt install nodejs

- Ejecutar el comando: npm install
- Ejecutar el comando: npm run dev
- Finalmebte debes activar el servidor ejecutando el comando: php artisan serve

Ingresa a tu navegador y escribes: localhost:8000 y listo ya tienes todo lo referido al Registro y Login en tu proyecto de Laravel, ahora SI !!! a migrar lo que descargastes a Laravel.

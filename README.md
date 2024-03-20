# CoderServer2

CoderServer2 fue creado utilizando el módulo de Node.js "Express" para cumplir la función de almacenar y manejar, mediante diferentes métodos, tanto un gestor de productos como uno de usuarios.


Ejecutando las Pruebas

Para realizar pruebas de funcionamiento, es necesario iniciar el servidor en la consola utilizando el siguiente comando: "npm run dev".

Luego, nos dirigimos al navegador, donde ingresamos a la dirección localhost:8080 para probar las siguientes rutas:

    1.- localhost:8080/
    2.- localhost:8080/api/products
    3.- localhost:8080/api/products?category=Manga
    4.- localhost:8080/api/products?category=Novelas
    5.- localhost:8080/api/products/:nid -- Ej: localhost:8080/api/products/dd0f8b41f1c46c35c1999b11
    6.- localhost:8080/api/users
    7.- localhost:8080/api/users?role=torre
    8.- localhost:8080/api/users?role=alfil
    9.- localhost:8080/api/users?role=peón
    10.- localhost:8080/api/users/:nid -- Ej: localhost:8080/api/users/abc1645ac12fc0a534b7f4f2
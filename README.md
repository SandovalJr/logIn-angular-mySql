# Versión

* Angular CLI: 9.0.7
* Node: 12.16.1
* OS: win32 x64

# MEAN Login y Registro con MySQL y AWT

![MEAN Todo](/screenshots/angular-login1.PNG)
#
![MEAN Todo](/screenshots/angular-login2.PNG)
#
![MEAN Todo](/screenshots/angular-login3.PNG)
#
![MEAN Todo](/screenshots/angular-login4.png)



# Configuración Inicial
1. Crea la base de datos con nombre: `nodejs_login1`
2. Ejecuta el script de base de datos para crear la estructura de la BD.
3. Clona el repo y ejecuta `npm install` en el server de Node js y en el client de Angular.


## Ejecución de Base de Datos MongoDB
1. ejecuta un SGBD (XAMPP puede servir) 

## Ejecución del servidor Node JS
1. desde el cmd nos ubicamos en la ruta del server
2. digitamos el comando `npm run dev`

## Ejecución del client de Angular 
1. desde el cmd nos ubicamos en la ruta del server
2. digitamos el comando `npm start`

# Solución a posibles errores
Si sale un error con `rxjs` vas al package.json y cambias esto: `"^6.1.0"` por esto: `"6.1.0"`

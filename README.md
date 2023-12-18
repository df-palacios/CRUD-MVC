hay que instalar node.js la v12.19.0

luego de instalarlo

Hay que ejecutar enconsola estando dentro de la carpeta

...\mvc\controlador\1-WebSocket  

el comando  "node testmvc.js"

luego hay que abrir el inicio.html en el navegador que esta en la carpeta vista

para las bases de datos se uso Msql

se importa el sql que esta en la carpeta modelo

para la conexion con la base de datos hay que modificar el archivo "tetsmvc.js"

al inicio esta este codigo

var myConnect = mysql.createConnection({
    host: 'localhost',
    user: 'usuarioNuevo',
    password: '1234',
    database: 'mvc'
});

esas credenciales tienes que cambiarlas por las que configuraste en tu base de datos
si no configuraste deberia ser 

user: root
password : ""
datebase: El nombre de la bases de datos

en este video aparece cómo correr el proyecto y se muestra funcionando:

https://drive.google.com/file/d/1RauC5geOuH07fzUPNwBI4H1z4qmrm8G3/view?usp=sharing



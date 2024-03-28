User registration system in a parking lot, backend made in node.js, SQL database, front end made in flat HTML+CSS+JS

install node.js v 12.19.0

then, open your terminal and change directory to: 

...\mvc\controlador\1-WebSocket  

run  "node testmvc.js"

then, open vista/inicio.html in your browser, 

mySQL was used for the database, you must import the .sql file inside the folder "modelo"


for the database connection, modify the file "tetsmvc.js"

look at this code at the start: 

var myConnect = mysql.createConnection({
    host: 'localhost',
    user: 'usuarioNuevo',
    password: '1234',
    database: 'mvc'
});

you must change those credentials, user and password. 

if you didn't set those values previously, the default are: 

user: root
password : ""
database: name of your database

video: 

https://drive.google.com/file/d/1RauC5geOuH07fzUPNwBI4H1z4qmrm8G3/view?usp=sharing



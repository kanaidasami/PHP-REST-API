Creata a database name restapi 
create a table name students with this talbe (id,name,age,city)
create a config.php file and past this code 

<?php
$hostname = "localhost";
$userName = "root";
$password = "";
$dbname   = "restapi";

$conn = mysqli_connect($hostname,$userName,$password,$dbname);

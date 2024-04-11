#ACE-Microservices
Microservicios con docker, php, mysql

 Creamos una cuenta AWS

 #instalamos Docker 
 sudo yum install -y docker 
 
 #instalamos docker-compose
 sudo install docker-compose (version XX ver.'3.9')

 Crear un topic SNS y suscribrse, y colocar el ARN en el archivo submit.php

 #Dar Roles al EC2
 Seleccionamos la instancia en la que estamos trabajndo, desplegamos el menu acciones> seguridad> modificar Rol de seguridad> elegimos el Rol "LabInstanceProfile"
 
luego vamos al servivio de IAM y buscamos en el menu izquierdo Rol> LabRole y añadimos la politica "SNSFullAccess"

 sudo docker compose up 

 acceder al formulario y probar para recibir el mensaje 

# Proyecto-Telematica
Proyecto final telematica Jeronimo Valencia Ospina

Para iniciar el servicio se debe entrar a la carpeta donde se encuentran los archivos

Luego se ejecuta el comando 

sudo docker build -t servidorblog:01 .

Una vez terminada de instalar se ejecuta

sudo docker run -d -v /home/upb/Documentos/ejercicio/vol/:/vol/ -p 80:80 servidorblog:01 python3 app.py  

# Proyecto-Telematica
Proyecto final telematica Jeronimo Valencia Ospina 000165785

Para iniciar el servicio se debe entrar a la carpeta donde se encuentran los archivos

Luego se ejecuta el comando 

sudo docker build -t servidorblog:01 .

Una vez terminada de instalar se ejecuta

sudo docker run -d -v /home/upb/Documentos/ejercicio/vol/:/vol/ -p 80:80 servidorblog:01 python3 app.py  

La ruta '/home/upb/Documentos/ejercicio/vol/' debe ser cambiada por la ruta del archivo data.xlsx dentro de vol/

El servicio funciona con un volumen, se puede actualizar el archivo .xlsx que está dentro de la carpeta vol del proyecto para actualizar las 4 publicaciones

## Descarga los datos para la práctica 6
1. Descarga cada archivo .csv de la RUOA de 2015 hasta finales de 2021:
Por minuto
https://www.ruoa.unam.mx/csv_data/more/minuto.php
2. Guardar en una carpeta
3. Crear una carpeta remota dentro del HDFS
$ hdfs dfs -mkdir /nombre_usuario/datos_RUOA
4. Subir los archivos a la nueva carpeta 
$ hdfs dfs -put /carpeta/local /nombre_usuario/datos_RUOA
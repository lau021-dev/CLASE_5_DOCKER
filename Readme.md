Tener instalado en el sistema operativo donde vamos a trabajar, Docker y docker-compose

1. Cree un directorio son el nombre mi_primer_dockerfile.
2. Dentro cree un Dockerfile, el cual estaadjuntado.
3. En el mismo dorectorio cree un archivo llamado ¨index.html¨ y aqui es donde personalizamos el contenido que queremos mostrar.
4.Abrimos nuestra terminal y navegamos hasta el directorio que creamos, donde se encuentran el archivo Dockerfile y el index.html
5.Escribimos el siguiente comando: sudo docker build -t mi_primer_dockerfile .
6.Una vez que se haya construido la imagen, creamos un archivo llamado "docker-compose.yml" en el mismo directorio.
7.Creamos un archivo llamado nginx.conf en el mismo directorio.
9.Guardamos ambos archivos y los cerramos.
10.Ejecutamos el siguiete comando sudo docker-compose up -d
11.Para detener el contenedor ejecutamos: sudo docker-compose down 

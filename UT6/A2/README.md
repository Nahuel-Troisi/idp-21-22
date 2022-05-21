# ACTIVIDAD 4 IDP

***Nahuel Ivan Troisi***
<br>
***1º de Ciclo Superior de Administración de Sistemas Informáticos en Red***

## AÑADIR CAJAS

a) Creamos un nuevo fichero donde alojar todos nuestros archivos de Vanguard. <br> ![](img/1/1.1.1.png)

b) Creamos un archivo "Vagrantfile" con la siguiente configuración. <br> ![](img/1/1.1.2.png)

c) Levantamos la máquina creada. <br> ![](img/1/1.2.1.png) <br> ![](img/1/1.2.2.png)

d) Accedemos a la máquina mediante SSH. <br> ![](img/1/1.3-1.4.png)

## REDIRECCIÓN DE PUERTOS

a) Editamos el archivo "Vagrantfile". <br> ![](img/3/3.1.png)

b) Levantamos la máquina con la nueva configuración. <br> ![](img/3/3.2.png)

c) Comprobamos que se han efectuado los cambios. <br> ![](img/3/3.3.png)

d) Mediante SSH instalamos "Apache2" en la MV. <br> ![](img/3/3.4.png)

e) Comprobamos el puerto asignado. <br> ![](img/3/3.5.png)

f) Eliminamos la MV. <br> ![](img/3/3.6.png)

## SUMINISTRO MEDIANTE SHELL SCRIPT

a) Mediante VisualStudio, creamos un archivo HTML en nuestra carpeta de Vagrant. <br> ![](img/4/4.1.png)

b) Del mismo modo, creamos un script con la siguiente configuración. <br> ![](img/4/4.2.png)

c) Editamos el archivo de configuración "Vagrantfile". <br> ![](img/4/4.3.png)

d) Levantamos la MV para comprobar que se han efectuado los cambios. <br> ![](img/4/4.4.png) 

e) Comprobamos que podemos acceder al servidor Apache. <br> ![](img/4/4.5.png)
 
## SUMINISTRO MEDIANTE PUPPET

a) Editamos el archivo de configuración "Vagrantfile". <br> ![](img/5/5.1.png)

b) Creamos el siguiente archivo mediante VisualStudio. <br> ![](img/5/5.2.png)

c) Levantamos la MV. <br> ![](img/5/5.3.png)

d) Cambiamos el nombre de la MV en el archivo de configuración. <br> ![](img/5/5.4.png)

e) Comprobamos que se ha efectuado el cambio. <br> ![](img/5/5.5.png)

## CAJA PERSONALIZADA

a) Instalamos el servicio SSH en la MV. <br> ![](img/6/6.1.png)

b) Añadimos el usuario "Vagrant" a la MV. <br> ![](img/6/6.2.png)

c) Accedemos con usuario Vagrant y configuramos el acceso por clave pública. <br> ![](img/6/6.3.png) <br> ![](img/6/6.4.png)

d) Editamos el archivo "Sudoers" para conceder permisos a Vagrant. <br> ![](img/6/6.5.png) <br> ![](img/6/6.6.png) 

e) Creamos la caja. <br> ![](img/6/6.7.png)

f) Comprobamos que se ha creado correctamente. <br> ![](img/6/6.8.png)

g) Añadimos la caja a nuestra carpeta de archivos. <br> ![](img/6/6.9.png)

h) Comprobamos la lista de cajas para corroborar que se ha añadido correctamente. <br> ![](img/6/6.10.png)

i) Editamos el archivo de configuración "Vagrantfile". <br> ![](img/6/6.11.png)

j) Levantamos la MV y comprobamos que se ejecuta correctamente. ![](img/6/6.12.png)

## CAJA WINDOWS

a) Buscamos la MV que más nos guste y la añadimos a través de Vagrant. <br> ![](img/7/7.1.png)

b) Listamos las MV para comprobar que se ha añadido correctamente. <br> ![](img/7/7.2.png)

c) Levantamos la MV. <br> ![](img/7/7.3.png)

d) Comprobamos que se ha realizado correctamente. <br> ![](img/7/7.4.png) <br> ![](img/7/7.5.png)







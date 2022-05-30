# ACTIVIDAD 6 IDP

***Nahuel Ivan Troisi***
<br>
***1º de Ciclo Superior de Administración de Sistemas Informáticos en Red***

## CONFIGURACIÓN DE LA MV

a) Vamos a hacer uso de dos máquinas virtuales, la primera va a ser reciclada de la anterior práctica
y la otra la vamos a crear nueva, pero sin instalar el sistema operativo, ya que va a instalarse a través
de PXE. <br> ![](img/1/1.1.png)

## SERVICIO DHCP

a) Instalamos el servicio DHCP en la MV 1. <br> ![](img/2/2.1.png)

b) Editamos la interfaz de uso. <br> ![](img/2/2.2.png)

c) Editamos el archivo de configuracion del DHCP. <br> ![](img/2/2.3.png)


## SERVICIO TFTP

a) Editamos la configuración del servicio TFTP después de haberlo instalado y reemplazamos
la dirección ip por defecto por la que posea nuestra MV. <br> ![](img/3/3.1.png)

## SERVIDOR NFS

a) Creamos un punto de montaje para la ISO. <br> ![](img/4/4.1.png) 

b) Editamos el archivo de configuración "/etc/exports". <br> ![](img/4/4.2.png) 

## MENÚ DE ARRANQUE 

a) Creamos los siguientes directorios. <br> ![](img/5/5.1.png) 

b) Editamos el archivo de arranque. <br> ![](img/5/5.2.png) 

## CONFIGURACIÓN DE UNA IMAGEN PARA INSTALAR 

a) Editamos el archivo del bootloader. <br> ![](img/6/6.1.png) 

b) Comprobamos que la MV 2 arranca desde el menú PXE. <br> ![](img/6/6.2.png)

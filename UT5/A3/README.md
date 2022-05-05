# ACTIVIDAD 3 IDP

***Nahuel Ivan Troisi***
<br>
***1º de Ciclo Superior de Administración de Sistemas Informáticos en Red***

## APLICAR DIRECTIVAS DE USUARIO

Vamos a crear las Unidades Organizativas "sith02" y "jedi02" respectivamente, donde vamos a añadir los usuarios correspondientes
a esas OU.

<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A3/img/1.1%20(1).PNG">
<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A3/img/1.1%20(2).PNG">

<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A3/img/1.1%20(3).PNG">
<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A3/img/1.1%20(4).PNG">

Una vez realizado, vamos a crear las distintas GPO`s para cada OU.

<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A3/img/1.2%20(1).PNG">
<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A3/img/1.2%20(2).PNG">

Dentro de estas dos nuevas GPO`s, vamos a realizar una serie de restricciones como se detalla a continuación.

<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A3/img/1.5%20(3).PNG">
<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A3/img/1.5%20(4).PNG">

Aplicamos este comando para hacer efectivos todos los cambios.

<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A3/img/1.5%20(1).PNG">

Si intentamos realizar alguna de las restriciones, nos saltará el siguiente mensaje:

<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A3/img/1.5%20(2).PNG">

## PAQUETE MSI
Vamos a crear una carpeta en el disco "E" con el nombre "software02" en la que vamos a guardar nuestro futuro archivo MSI y vamos
a permitir que esta se pueda compartir.

<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A3/img/2.1%20(1).PNG">
<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A3/img/2.1%20(2).PNG">

Una vez descargada la herramienta "EMCO" que necesitaremos para crear el archivo MSI seguimos los pasos del tutorial de J.A.Mora
para poder convertir un .exe en .msi. Una vez finalizado, comprobamos que nos genera dicho archivo.

<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A3/img/2.2.PNG">


## APLICAR DIRECTIVA DE EQUIPO
Vamos a crear otra OU llamada "equipos02" donde vamos a incluir todos los equipos del dominio, que, en nuestro caso sólo es un
único equipo.

<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A3/img/3.1%20(1).PNG">

Una vez configurado, vamos a crear otra GPO que nos permita añadir el paquete MSI con el programa de "Firefox" para que este
se intale en todas las maquinas cliente del servidor.

<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A3/img/3.1%20(2).PNG">
<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A3/img/3.1%20(2.1).PNG">
<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A3/img/3.1%20(3).PNG">

Una vez realizado, comprobamos que todas las máquinas cliente tienen instalado el programa "Firefox".













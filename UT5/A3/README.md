# ACTIVIDAD 3 IDP

***Nahuel Ivan Troisi***
<br>
***1º de Ciclo Superior de Administración de Sistemas Informáticos en Red***

## APLICAR DIRECTIVAS DE USUARIO

Vamos a crear las Unidades Organizativas "sith02" y "jedi02" respectivamente, donde vamos a añadir los usuarios correspondientes
a esas OU.

Una vez realizado, vamos a crear las distintas GPO`s para cada OU.

Dentro de estas dos nuevas GPO`s, vamos a realizar una serie de restricciones como se detalla a continuación.

Aplicamos este comando para hacer efectivos todos los cambios.

Si intentamos realizar alguna de las restriciones, nos saltará el siguiente mensaje:

## PAQUETE MSI
Vamos a crear una carpeta en el disco "E" con el nombre "software02" en la que vamos a guardar nuestro futuro archivo MSI.

Una vez descargada la herramienta "EMCO" que necesitaremos para crear el archivo MSI seguimos los pasos del tutorial de J.A.Mora
para poder convertir un .exe en .msi. Una vez finalizado, comprobamos que nos genera dicho archivo.

## APLICAR DIRECTIVA DE EQUIPO
Vamos a crear otra OU llamada "equipos02" donde vamos a incluir todos los equipos del dominio, que, en nuestro caso sólo es un
único equipo.

Una vez configurado, vamos a crear otra GPO que nos permita añadir el paquete MSI con el programa de "Firefox" para que este
se intale en todas las maquinas cliente del servidor.

Una vez realizado, comprobamos que todas las máquinas cliente tienen instalado el programa "Firefox".


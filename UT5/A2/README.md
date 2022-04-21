<center>

# ACTIVIDAD 2 IDP

</center>

***Nahuel Ivan Troisi*** <br>
***1º de Ciclo Superior de Administración de Sistemas Informáticos en Red*** 


## UNIRSE AL DOMINIO DESDE OPENSUSE
+ Usar Yast para unir la MV al dominio del PDC.
<br>
+ Yast -> Pertenencia a dominio de Windows (Unirse a un dominio)
<br>
+ Poner el nombre largo del dominio. Por ejemplo "ruiz42dom.curso2021".
<br>
+ Activar la Autenticación SMB.
<br>
+ Activar Crear home del usuario.
<br>
+ Poner la clave del Administrador del dominio.
<br>
+ Debe aparecer un mensaje de que se ha realizado la unión al dominio.
<br>
+ Comprobar en el servidor PDC, consultando los equipos del dominio.
<br>

<img src "https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A2/img/1.png">
<img src "https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A2/img/2.png">


## ABRIR SESIÓN DESDE EL CLIENTE
+ Iniciar sesión en el equipo GNU/Linux usando un usuario del dominio.
<br>
+ Desde el cliente, entramos al sistema con algún usuario del dominio de la siguiente 
forma nombre-de-dominio-corto\usuario-del-dominio. 
Por ejemplo: ruiz42dom\obiwan. Se recomienda usar el entorno gráfico XFCE.
<br>
+ Una vez iniciada la sesión ejecutar los comandos de comprobación:
<br>
~~~
whoami, esto debe devolver DOMINIO\USERNAME que ha iniciado sesión.
~~~
<br>
~~~
pwd, para consultar el directorio actual.
~~~
<br>
~~~
cat /etc/passwd | grep USERNAME, esto debe devolver vacío, indicando que 
el usuario no está definido como usuario local, por tanto, debe ser 
un usuario del dominio.
~~~
<br>

<img src "https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A2/img/3.png">
<img src "https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A2/img/4.png">


## RECURSOS COMPARTIDOS
Podemos acceder al recurso compartido del Window Server (PDC) de la siguiente forma:
<br>
+ Iniciar un explorador de archivos.
<br>
Escribir lo siguiente en la barra de ruta que está en la parte superior, por ejemplo: 
+ smb://ip-del-pdc/perfiles$/yoda.V5 para conectarse desde una máquina Windows.
+ smb://ip-del-pdc/perfiles$ para conectarse desde una máquina linux.

<img src "https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A2/img/5.png">

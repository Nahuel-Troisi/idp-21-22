<center>

# ACTIVIDAD 2 IDP

</center>

***Nahuel Ivan Troisi*** <br>
***1º de Ciclo Superior de Administración de Sistemas Informáticos en Red*** 


## UNIRSE AL DOMINIO DESDE OPENSUSE
+ Usar Yast para unir la MV al dominio del PDC.

+ Yast -> Pertenencia a dominio de Windows (Unirse a un dominio)

+ Poner el nombre largo del dominio. Por ejemplo "ruiz42dom.curso2021".

+ Activar la Autenticación SMB.

+ Activar Crear home del usuario.

+ Poner la clave del Administrador del dominio.

+ Debe aparecer un mensaje de que se ha realizado la unión al dominio.

+ Comprobar en el servidor PDC, consultando los equipos del dominio.


<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A2/img/1.png">
<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A2/img/2.png">

Accedemos al servidor remoto de la MV con Windows Server.

## ABRIR SESIÓN DESDE EL CLIENTE
+ Iniciar sesión en el equipo GNU/Linux usando un usuario del dominio.

+ Desde el cliente, entramos al sistema con algún usuario del dominio de la siguiente 
forma nombre-de-dominio-corto\usuario-del-dominio. 
Por ejemplo: ruiz42dom\obiwan. Se recomienda usar el entorno gráfico XFCE.

+ Una vez iniciada la sesión ejecutar los comandos de comprobación:

~~~
whoami, esto debe devolver DOMINIO\USERNAME que ha iniciado sesión.
~~~

~~~
pwd, para consultar el directorio actual.
~~~

~~~
cat /etc/passwd | grep USERNAME, esto debe devolver vacío, indicando que el usuario no está definido como usuario local, 
por tanto, debe ser un usuario del dominio.
~~~


<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A2/img/3.png">
<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A2/img/4.png">

Iniciamos sesión en los clientes de la MV de Windows Server desde OpenSuse y comprobamos que se ha
realizado correctamente con los comandos de comprobación. 

## RECURSOS COMPARTIDOS
Podemos acceder al recurso compartido del Window Server (PDC) de la siguiente forma:
<br>
+ Iniciar un explorador de archivos.

Escribir lo siguiente en la barra de ruta que está en la parte superior, por ejemplo: 
+ smb://ip-del-pdc/perfiles$/yoda.V5 para conectarse desde una máquina Windows.
+ smb://ip-del-pdc/perfiles$ para conectarse desde una máquina linux.

<img src="https://github.com/Nahuel-Troisi/idp-21-22/blob/main/UT5/A2/img/5.png">

Accedemos al sistema de archivos de Windows Server desde el gestor de ficheros de OpenSuse. 

***Nota***
<br>
No he podido acceder a la carpeta de "perfiles" ya que en mi MV de Windows Server he tenido problemas con los usuarios y no me deja acceder sino únicamente como 
Administrador, por lo que no he podido adjuntar una captura desde el explorador de archivos accediendo al perfil de "Yoda". 

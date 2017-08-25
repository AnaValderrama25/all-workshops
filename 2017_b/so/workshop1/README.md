### Taller 1
**Universidad ICESI**  
**Curso:** Sistemas Operativos  
**Docente:** Daniel Barragán C.  
**Tema:** Comandos de Linux, Estructura de directorio, Virtualización  
**Correo:** daniel.barragan at correo.icesi.edu.co


### Objetivos
* Conocer y emplear comandos de Linux para la realización de tareas administrativas

### Prerrequisitos
* Virtualbox o WMWare
* Máquina virtual con sistema operativo CentOS7

### Descripción
El primer taller del curso sistemas operativos trata sobre el sistema operativo Linux, la estructura de sus directorios y virtualización 

### Actividades

1. Explique la función de los directorios en la raíz de sistema operativo Linux-CentOS.
Proporcione ejemplos de los archivos que se encuentran en cada directorio (explique al menos un
archivo por directorio).
| Directorio | Función |
| /bin | Este directorio es un directorio estático, almacena todos los ejecutables de usuario parecidos a los archivos .exe |
| /sbin | Al igual que bin contiene los programas ejecutables que solo son ejecutables por el root user |
| /boot | Contiene los archivos de configuración de arranque necesarios para que el kernel pueda iniciar su funcionamiento |
| /dev | Contiene todos los dispositivos en forma de archivos |
| /proc | Este directorio contiene la información sobre el estado del sistema y sus procesos |
| /var | Contiene los archivos con información del sistema. Archivos de registros y bases de datos |
| /etc | Contiene archivos de configuración que no contiene binarios |
| /home | directorio personal para cada usuario |
| /initrd | Este directorio se emplea cuando se va a iniciar un arranque personalizado |
| /lib | Contiene las librerías necesarias para la ejecución de binarios |
| /media | 
| /opt | Este directorio es opcional contiene aplicaciones  externas |
| /root | Directorio de super usuario, solo el usuario root puede emplearlo |
| /srv |
| /sys |
| /tmp | Contiene los archivos temporales creados por el sistema y por los usuarios |
| /usr |
| /mnt |


| Directorio   | Archivo ejemplo | Descripción del contenido del directorio  |
|------|------|------|
| bin | 
| boot | 
| dev | 
| a directory | an example file | an awesome description |

2. En una tabla como se muestra a continuación escriba 10 comandos de Linux no visto en clase. Puede incluir comandos que funcionan una vez han sido instalados con yum

| Comando   | Usuario | Descripción   |
|------|------|------|
| $ an awesome command | who call it | an awesome description |

3. ¿Cuál es la utilidad del comando printenv en Linux?, Investigue acerca de la creación de variables de ambiente en Linux y como hacerlas permanentes. Cree una variable de ambiente, hágala permanente y muestre evidencias del funcionamiento.

### Nota

El informe debe ser entregado en formato README.md y debe ser subido a un repositorio de github. El repositorio de github debe ser un fork de https://github.com/ICESI-Training/so-workshop1 y para la entrega deberá hacer un Pull Request (PR) respetando la estructura definida. El código fuente y la url de github deben incluirse en el informe.  

## Referencias

* https://github.com/ICESI/so-commands/tree/master/centos7
* https://cmdchallenge.com  
* https://www.gutenberg.org

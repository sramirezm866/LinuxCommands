# Comandos de Linux :penguin:

_Acá se encuentra una recopilación de los comandos de Linux utilizados durante las clases y laboratorios realizados en el curso de Sistemas Operativos. Además, de una pequeña descripción de su funcionamiento._

## Básicos :computer:🚀

_Se enlistan comandos básicos para la administración de dicho Sistema Operativo._

_Administración de archivos y directorios:_


**_cd 'dir-name'_** crea un nuevo directorio.<br/>
**_ls_** sirve para ver las carpetas y archivos que están dentro de un directorio.<br/>
**_ls -l_** sirve para ver las carpetas y archivos que están dentro de un directorio en forma de lista. <br/>
**_ls -a_** sirve para ver las carpetas y archivos que están ocultos. <br/>
**_mkdir 'new-dir-name'_** crea un nuevo directorio.<br/>
**_rmdir 'dir-name'_** elimina un directorio.<br/>
**_touch archivo1.txt_** crea un nuevo archivo.<br/>
**_cat archivo1.txt_** se logra visualizar el contenido de un archivo.<br/>
**_nano archivo1.txt_** es un editor de texto.<br/>
**_vi archivo1.txt_** es un editor de texto.<br/>
**_mv 'file-name' 'new-file-name'_** renombrar un archivo o directorio.<br/>
**_mv 'file-name' 'new-file-path'_** mover un archivo o directorio.<br/>
**_more_** se usa para ver los documentos de texto mostrando una página a la vez en caso de que el archivo sea grande.<br/>
**_tail 'file-name'_** muestra el final de un documento.<br/>
**_tail –n # 'file-name'_** muestra solo # cantidad de línas del final del documento.<br/>
**_head 'file-name'_** muestra el inicio de un documento.<br/>
**_head –n # 'file-name'_** muestra solo # cantidad de línas del inicio del documento.<br/>
**_grep word file-name_** se utiliza para buscar una cadena de caracteres en un archivo específico.<br/>
**_pwd_** imprime el nombre del directorio actual integrando a su vez la ruta completa tomando como origen la raíz (/).<br/>
**_du -h 'file'_** muestra el tamaño del archivo.<br/>
**_stat 'file'_** muestra la fecha de creación del archivo.<br/>
**_file 'file'_** muestra el tipo de archivo.<br/>
**_chown 'user' 'file'_** propietario del archivo.<br/>
**_chmod 777 'file'_** dar permisos al archivo.<br/>
 
 
_Administración de paquetes y repositorios:_

**_sudo apt-updade_** actualiza la lista de paquetes.<br/>
**_sudo apt-upgrade_** actualiza todos los paquetes instalados.<br/>
**_sudo apt intall 'package-name'_** instalar un paquete de software.<br/>
**_sudo apt intall openssh-server_** instalar un paquete llamado openssh-server, dicho paquete sirve para habilitar ssh en el dispositivo.<br/>
**_sudo apt intall snapd_** instalar un paquete llamado snapd el cual es una tienda de aplicaciones.<br/>
**_sudo apt remove 'package-name'_** eliminar un paquete de software.<br/>
**_dpkg -l_** sirve para ver la lista de paquetes instalados.<br/>
**_dpkg -i 'package-name'_** sirve para instalar un paquete.<br/>
**_dpkg -r 'package-name'_** sirve para desinstalar un paquete.<br/>
**_sudo add-apt-repository 'repository'_** añade un repositorio.<br/>

**_ip addr_** sirve para ver la dirección IP del dispositivo.<br/>
**_sudo su_** sirve para iniciar seción como usuario raíz.<br/>
**_whoami_** muestra el nombre del usuario que actualmente se encuentra en sesión.<br/>
**_uname -a_** muestra la versión del kernel.<br/>
**_lsb_release -a_** muestra toda la información Linux Standard Base (LSB) específica para la distribución de Linux.<br/>
**_man 'command'_** muestra el manual de uso de un comando.<br/>
**_alias actualizar = "sudo apt update && sudo apt upgrade"_** crea un alias para un comando.<br/>
**_useradd 'user' –p 'password'_** crea un usuario nuevo.<br/>
**_sudo passwd 'user' _** cambia el password del usuario especificado.<br/>
**_history_** ver el historial de comandos que se han ejecutado.<br/>
 
**_ps -aux_** ver los procesos que están corriendo en el equipo.<br/>
**_kill -# pid_** matar un proceso que está corriendo en el equipo.<br/>
**_pstree_** visualizar el árbol de procesos, mostrando la relación padre hijo.<br/>
**_top_** da información acerca del uso de la cpu, de la memoria, de los procesos en ejecución, entre otros, en tiempo real.<br/>
**_htop_** permite al usuario monitorear interactivamente los recursos vitales del sistema.<br/>
**_uptime_** se utiliza para averiguar cuánto tiempo está activo el sistema (en ejecución).<br/>
**_df -h_** muestra información relacionada con los sistemas de archivos. (espacio total y el espacio disponible).<br/>
**_demicode -t processor_** obtener información acerca del procesador.<br/>
**_demicode -t bios_** obtener información acerca del bios.<br/>
**_swapon_** se utiliza para especificar los dispositivos en los que se realizará la búsqueda y el intercambio.<br/>
**_swapoff_** desactiva el intercambio en los dispositivos y archivos especificados.<br/>
**_free_** proporciona información sobre el uso de memoria usada y no utilizada y la memoria de intercambio de un sistema.<br/>
**_mount_** la salida incluirá todos los sistemas de archivos, incluidos los virtuales, como cgroup, sysfs y otros.<br/>
**_gparted_** administra las particiones.<br/>
**_gnome-disk-utility_** muestra información sobre el disco.<br/>
**_echo 'string'_** se usa para mostrar la línea o cadena de texto que se pasa como argumento.<br/>
**_bash 'script.sh'_** ejecutar un script de bash.<br/>


### Pre-requisitos 📋

_Que cosas necesitas para instalar el software y como instalarlas_

```
Da un ejemplo
```

### Instalación 🔧

_Una serie de ejemplos paso a paso que te dice lo que debes ejecutar para tener un entorno de desarrollo ejecutandose_

_Dí cómo será ese paso_

```
Da un ejemplo
```

_Y repite_

```
hasta finalizar
```

_Finaliza con un ejemplo de cómo obtener datos del sistema o como usarlos para una pequeña demo_

## Ejecutando las pruebas ⚙️

_Explica como ejecutar las pruebas automatizadas para este sistema_

### Analice las pruebas end-to-end 🔩

_Explica que verifican estas pruebas y por qué_

```
Da un ejemplo
```

### Y las pruebas de estilo de codificación ⌨️

_Explica que verifican estas pruebas y por qué_

```
Da un ejemplo
```

## Despliegue 📦

_Agrega notas adicionales sobre como hacer deploy_

## Construido con 🛠️

_Menciona las herramientas que utilizaste para crear tu proyecto_

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - El framework web usado
* [Maven](https://maven.apache.org/) - Manejador de dependencias
* [ROME](https://rometools.github.io/rome/) - Usado para generar RSS

## Contribuyendo 🖇️

Por favor lee el [CONTRIBUTING.md](https://gist.github.com/villanuevand/xxxxxx) para detalles de nuestro código de conducta, y el proceso para enviarnos pull requests.

## Wiki 📖

Puedes encontrar mucho más de cómo utilizar este proyecto en nuestra [Wiki](https://github.com/tu/proyecto/wiki)

## Versionado 📌

Usamos [SemVer](http://semver.org/) para el versionado. Para todas las versiones disponibles, mira los [tags en este repositorio](https://github.com/tu/proyecto/tags).

## Estudiante ✒️

_Elaborado por:_

* **Sindy Emileidy Ramírez Mora** - *Trabajo Inicial* - [villanuevand](https://github.com/villanuevand)

## Licencia 📄

Este proyecto está bajo la Licencia (Tu Licencia) - mira el archivo [LICENSE.md](LICENSE.md) para detalles

## Expresiones de Gratitud 🎁

* Comenta a otros sobre este proyecto 📢
* Invita una cerveza 🍺 o un café ☕ a alguien del equipo. 
* Da las gracias públicamente 🤓.
* etc.

# Comandos de Linux :penguin:

_Acá se encuentra una recopilación de los comandos de Linux utilizados durante las clases y laboratorios realizados en el curso de Sistemas Operativos. Además, de una pequeña descripción de su funcionamiento._

_Se enlistan comandos básicos para la administración de dicho Sistema Operativo._

## Administración de archivos y directorios: :computer:🚀

**_cd 'dir-name'_** moverse a un directorio.<br/>
**_cd .._** retroceder al directorio anterio.<br/>
**_cp 'file-name' 'path'_** copiar el contenido de un directorio o fichero a una ubicación específica.<br/>
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
**_find -name 'file-name'_** para encontrar un archivo por nombre.<br/>
**_locate 'file-name'_** para localizar un archivo.<br/>
 
## Administración de paquetes y repositorios: :computer:📦

**_sudo apt-updade_** actualiza la lista de paquetes.<br/>
**_sudo apt-upgrade_** actualiza todos los paquetes instalados.<br/>
**_sudo apt intall 'package-name'_** instalar un paquete de software.<br/>
**_sudo apt intall openssh-server_** instalar un paquete llamado openssh-server, dicho paquete sirve para habilitar ssh en el dispositivo.<br/>
**_sudo apt install mysql server_** instalar MySQL.<br/>
**_sudo apt intall snapd_** instalar un paquete llamado snapd el cual es una tienda de aplicaciones.<br/>
**_sudo apt remove 'package-name'_** eliminar un paquete de software.<br/>
**_dpkg -l_** sirve para ver la lista de paquetes instalados.<br/>
**_dpkg -i 'package-name'_** sirve para instalar un paquete.<br/>
**_dpkg -r 'package-name'_** sirve para desinstalar un paquete.<br/>
**_sudo add-apt-repository 'repository'_** añade un repositorio.<br/>

**_ip addr_** sirve para ver la dirección IP del dispositivo.<br/>
**_ping 'host-name or ip-address'_** sirve para ver la conectividad con un servidor.<br/>
**_hostname_** ver el nombre de la máquina.<br/>
**_sudo su_** sirve para iniciar seción como usuario raíz.<br/>
**_whoami_** muestra el nombre del usuario que actualmente se encuentra en sesión.<br/>
**_uname -a_** muestra la versión del kernel.<br/>
**_lsb_release -a_** muestra toda la información Linux Standard Base (LSB) específica para la distribución de Linux.<br/>
**_man 'command'_** muestra el manual de uso de un comando.<br/>
**_alias actualizar = "sudo apt update && sudo apt upgrade"_** crea un alias para un comando.<br/>
**_useradd 'user' –p 'password'_** crea un usuario nuevo.<br/>
**_sudo passwd 'user' _** cambia el password del usuario especificado.<br/>
**_history_** ver el historial de comandos que se han ejecutado.<br/>
**_sudo systemtl status 'service-name'_** ver si un servicio se encuentra corriendo en el equipo.<br/>

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

## Docker: :whale:📦

**_sudo apt install docker-ce_** instalar docker.<br/>
**_docker search 'image-name'_** buscar imágenes disponibles en Docker Hub.<br/>
**_docker pull 'image-name'_** descargar una imagen a la computadora.<br/>
**_docker images_** muestra las imágenes que se han descargado.<br/>
**_docker ps_** muestra los contenedores que están activos.<br/>
**_docker start 'container-id'_** inicia un contenedor..<br/>

## Estudiante ✒️

_Elaborado por:_

* **Sindy Emileidy Ramírez Mora** - *ULACIT*

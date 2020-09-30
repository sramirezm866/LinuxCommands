# Comandos de PowerShell 

_Repositorio con comandos de PowerShell._

## Básicos: :computer:🚀

**_get-alias_** optiene la lista de alias de PowerShell.<br/>
**_get-psdrives_** optener un listado de PS drives a disposición.<br/>
**_get-help "cmdlet" -Detailed_** Optener ayuda detallada sobre el uso de un comandlet.<br/>
**_get-help "cmdlet" -examples_** Optener ejemplos sobre el uso de un comandlet.<br/>
**_get-module "module-name"_** Instalar un modulo.<br/>
**_import-module "module-name"_** Importar un modulo.<br/>
**_get-module_** Ver la lista de módulos instalados.<br/>
**_get-childitem_** Ver la lista de directorios y archivos de donde estamos ubicados.<br/>
**_get-item "test.txt"_** Ver información de un archivo específico.<br/>
**_get-content "test.ini"_** Ver el contenido de un archivo.<br/>
**_set-content -value "test"_** Remplazando contenido de un archivo.<br/>
**_add-content -value "test"_** Añadir contenido de un archivo.<br/>
**_get-item -name "test" -ItemType directory_** Crear un directorio.<br/>
**_remove-item_** Elimina un directorio o archivo.<br/>
**_get-process_** Lista de todos los procesos que se están ejecutando en el sistema.<br/>
**_start-process "C:\Windows\notepad.exe"_** Ejecutar un nuevo proceso.<br/>
**_stop-process -name "name or id process"_** Detener un proceso que se esté ejecutando en el sistema.<br/>
**_wait-process -id "id process"_** Esperar a que se detenga un proceso que se está ejecutando.<br/>
**_get-service_**  Lista de todos los servicios que se están ejecutando en el sistema.<br/>
**_get-service | select-object *_** Select-object detallada las propiedades.<br/>
**_get-item win.ini | get-member *_** Get-Member optener listado de atributos y métodos.<br/>
**_Get-ChildItem -file | Where-Object -Property name -Like "w*"_** Where-object para realizar filtrado de resultados.<br/>
**_Get-ChildItem | Measure-Object "w*"_** Measure-Object para obtener estadísticas (count, average, maximum,minimun,...) sobre los resultados de cualquier cmdlet que devulva objetos.<br/>
**_"La hora es: {0:HH:mm}" -f $var._** Concatenar.<br/>
**_"Hola, {0}, {1}" -f $var, "Jaime" _** Concatenar.<br/>



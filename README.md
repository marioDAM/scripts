# Scripts
Porque necesito un sitio para organizarme las porciones de código

## Categorías
- [Java](#java)
- [Jars compilated](#jars)
- [MAF](#maf)
- [Movilizer](#movilizer)
- [PHP](#php)
- [Python](#python)
- [Shortcuts](#shortcuts)
- [Sistemas Operativos](#ssoo)
- [Software](#software)
- [Varios](#varios)

### Java
__[ConexionSingleton](/scripts/java/ConexionSingleton.java):__ Clase usada para devolver objetos Connection a una base de datos MySQL implementando el patrón Singleton

__[LectorCSV](/scripts/java/LectorCSV.java):__ Clase para leer ficheros CSV simples y complejos (requiere OpenCSV para estos últimos)

__[Manejador excepciones](/scripts/java/ManejadorExcepciones.java):__ Clase usada para formatear las excepciones en un string legible

__[Manejador Log4j](/scripts/java/ManejadorLog4j):__ Clase y fichero log4j.properties para manejar un logger por consola y ficheros con Log4j

__[ManejadorMovilizer](/scripts/java/ManejadorMovilizer.java):__ Clase usada para generar objetos Movilizer. Actualmente en la versión 2.5

__[ManejadorProperties](/scripts/java/ManejadorProperties.java):__ Clase para leer una propiedad concreta de archivos properties usando el patrón Singleton

__[Ordenar Map por valor](/scripts/java/SortMapByValue.java)__

__[WSDLImport](/scripts/java/wsimport.md):__ Instrucciones sobre como realizar un import de un WSDL a un proyecto Java

### JARs
__[Movilizer werbservice 16.11.2.4](/scripts/jar/movilizer-webservice-16.11.2.4.jar)__

### MAF
__[Colas MAF](/scripts/maf/manejadorColasMAF.groovy):__ Cómo manejar colas MAF en nodos Cassandra

__[CounterBO. Creación](/scripts/maf/creacionCounterBO.groovy):__ Creación de CounterBO y persistencia en la nube

__[CounterBO. Lectura de Counter de la nube](/scripts/maf/lecturaCounterBO.groovy):__ 

__[CounterBO. Bloquear en transacción](/scripts/maf/counterBloqueado.groovy):__ Bloqueo del counter en una transacción para evitar iteraciones no deseadas

__[Datacontainer. Lectura](/scripts/maf/lecturaDatacontainer.groovy)__ 

__[Datacontainer online. Lectura](/scripts/maf/lecturaDatacontainerOnline.groovy):__ Lectura de datacontainer online y respuesta a la movelet

__[Environment](/scripts/maf/Environment.groovy):__ Clase para manejar el acceso a los distintos systems ID del proyecto

__[Log](/scripts/maf/log.groovy):__ Creación de logs en el portal

__[Masterdata. Lectura](/scripts/maf/lecturaMasterdata.groovy):__ Lectura de masterdata conociendo previamente la clave

__[Masterdata. Query](/scripts/maf/queryMasterdata.groovy)__

__[Masterdata. Creación](/scripts/maf/creacionMasterdata.groovy)__

__[SSCC Generator](/scripts/maf/ssccGenerator.groovy):__ Clase para trabajar con la generación de códigos SSCC

### Movilizer
__[CheckAndUncheckElements](/scripts/movilizer/CheckAndUncheckElements.mxml):__ Pantalla de selección de checkboxes en tablas Movilizer

__[ConnectToBluetoothPrinter](/scripts/movilizer/ConnectToBluetoothPrinter.mxml):__ Cómo conectar una impresora Bluetooth desde Movilizer

__[ConnectWebBrowser](/scripts/movilizer/ConnectWebBrowser.mxml):__ Abre una página web en el navegador por defecto de Windows desde Movilizer

__[Emmet snippets - Eclipse](/scripts/movilizer/movilizerEmmetSnippets.xml):__ Snippets para atajos de teclado con Emmet en Eclipse

__[Emmet snippets - IntelliJ](/scripts/movilizer/movilizerEmmetSnippetsIntelliJ.xml):__ Snippets para atajos de teclado con Emmet en IntelliJ

__[GoogleMapsRequests](/scripts/movilizer/GoogleMapsRequests.mxml):__ Funciones MEL para trabajar con la API de Google Maps

__[ScanItems](/scripts/movilizer/ScanItems.mxml)__ Pantalla de escaneo de elementos usada en dispositivos Windows CE

__[TimeUtils](/scripts/movilizer/TimeUtils.mxml):__ Librería MEL para trabajar con tiempos

__[VSCode user snippets](/scripts/movilizer/movilizer.code-snippets)__ Code snippets personalizados para VS Code de Movilizer v16

### PHP
__[Ficheros](/scripts/php/Ficheros.php):__ Clase para trabajar con ficheros. Actualmente solo lee ficheros de un directorio

__[GoogleMapsGeo](/scripts/php/GoogleMapsGeo.php):__ Clase para trabajar con la geocodificación con la API de Google Maps

__[MailSender](/scripts/php/MailSender.php):__ Clase para realizar envíos de correos electrónicos. Requiere phpmailer para envíos complejos

### Python
__[barraProgresoTerminal](/scripts/python/barraProgresoTerminal.py):__ Genera una barra de progreso en la terminal

__[clonarRepositorio](/scripts/python/clonarRepositorio.py):__ Clonación de todas las ramas de un repositorio git, tanto público como privado

__[googleMapsAPI](/scripts/python/googleMapsAPI.py):__ Clase para trabajar con la API de Google Maps

__[importarDesdeRutaRelativa](/scripts/python/importFromRelativePath.py):__ Cómo importar ficheros desde una ruta relativa a otra

__[lamppController](/scripts/python/lamppController.py):__ Script para controlar el servidor XAMPP en Ubuntu

__[LectorXLSX](/scripts/python/LectorXLSX.py):__ Lector de ficheros XLSX con Python3

__[ManejadorXamppUbuntu](/scripts/python/manejadorXamppUbuntu.py)__ Arranca / detiene los servicios de XAMPP en Ubuntu

__[Python3 como entorno predeterminado en Mac OS Catalina](/scripts/python/Python3%20as%20default.md)__


### SS.OO.
__[Activar Windows 10](/scripts/sistemasOperativos/activar-windows.md)__

__[Anclar Papelera al dock de Ubuntu](/scripts/sistemasOperativos/PapeleraDockUbuntu.sh):__ Fichero .sh para permitir anclar la papelera al dock de Ubuntu

__[Borrar Java de Mac OS](/scripts/sistemasOperativos/removeJavaFromMacOS.md)__

__[EliminarOneDrive](/scripts/sistemasOperativos/eliminarOneDrive.cmd):__ Fichero .cmd para forzar la desinstalación de OneDrive de Windows 10

__[RestaurarVisorFotos](/scripts/sistemasOperativos/restaurarVisorFotos.reg):__ Habilita el uso del visor de fotos de Windows 7 en Windows 10. Requiere reinicio del sistema operativo

__[Ver serial Windows 10](/scripts/sistemasOperativos/verSerial.md)__

### Software
__[Atajos de teclado para Notepad++](/scripts/software/atajosNotepad++.md)__

__[Configuración IntelliJ](/scripts/software/ConfigIntelliJ.md)__

__[Configuración Sublime Text 3](/scripts/software/ConfigSublimeText.md)__

__[Configuración Visual Studio Code](/scripts/software/ConfigVSCode.md)__

### Varios
__[Cheatsheet comandos GIT](/scripts/varios/cheatsheetGit.md)__

__[Links interesantes](/scripts/varios/LinksInteresantes.md)__

__[Subreddits intersantes](/scripts/varios/subreddits.md)__

__[Respuestas automatizadas](/scripts/varios/RespuestasAutomatizadas.md)__

__[Markdown Jekyll shortcuts en VS Code](/scripts/varios/jekyll-shortcuts-vscode.json)__

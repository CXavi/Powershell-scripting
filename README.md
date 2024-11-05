# Powershell-scripting
Mòdul  dual NF4 powershell

Repositorio de practicas con powershell:

Act6-ej1:

  Solicita la ruta: Usamos Read-Host para que el usuario ingrese la ruta en la que desea buscar.
  
  Solicita el nombre del archivo o directorio: Usamos Read-Host para ingresar el nombre del archivo o directorio a buscar
  
  Verifica que exista: Test-Path comprueba si el archivo o directorio existe en la ruta indicada.
  
  Mensaje de resultado: Si Test-Path confirma la existencia, se imprime un mensaje indicando que se ha encontrado el archivo/directorio, y si    no indica que no se ha encontrado en la ruta.
  
Act6-ej2:

  Solicita la ruta de origen: Usando Read-Host, el usuario introduce la ruta del directorio que quiere copiar.
  
  Solicita la ruta de destino: Con Read-Host de nuevo, se solicita la ubicación donde se quiere guardar la copia de seguridad.
  
  Comprueba si existe la ruta de origen: Test-Path verifica que el directorio de origen realmente existe.
  
  Copia de seguridad: Si el directorio de origen existe, Copy-Item copia todos los archivos y subdirectorios del origen al destino. El           parámetro Recurse permite copiar de manera recursiva.
  
  Mensaje de resultado: Una vez completada la copia, se informa al usuario. Si la ruta de origen no existe, se muestra un mensaje de error.

# Gestión de Usuarios de Correo

Aplicación de consola en Java que permite registrar y listar usuarios.

## Funcionalidades acordadas

- Registrar usuario (nombre y correo)
- Listar usuarios registrados
- Persistencia en archivo usuarios.txt

Como las instrucciones indican se usáron

- Arquitectura por capas
- Manejo de archivos
- try-with-resources
- try-catch
- Uso de throws

## Instrucciones de ejecución
Primero al inicializar el codigo en Netbeans se le mostrará un menu de 3 opciones
Si desea Registrar una persona debera poner el Número 1 y poner el nombre y correo de dicha persona.
Si desea ver la lista de personas que han sido registradas anteriormente deberá poner el Número 2 y podrá ver la lista
Si desea salir del Sistema deberá poner el Número 3 y se le sacará del Sistema sin problemas(estaría raro que hayan problemas con eso)
Si usted llega a cometer errores tales como:
- Poner un número que no esta en la lista
- Dejar algún espacio en blanco
- No colocar una forma de correo(No usar @)
## Se le informara del error que cometió y podrá volver a intentar hacer la acción que deseaba anteriormente

[Curso kicad V6](Curso%20kicad%20V6.md)

## Configuracion del entorno de esquema

Antes de comenzar a trabajar, es necesario configurar el entorno el area de trabajo de nuestro editor equema de esta forma nos preparamos para generar BOM y la documentacion  necesaria con la que debe contar un proyecto de PCB, empecemos con [Configurar editor de esquema](Configurar%20editor%20de%20esquema.md)


## Primero pasos

En el caso de este curso vamos a usar modulos chinos de los cuales vamos a extraer sus componentes y nos vamos a fijar en como estan hechos para copiarlos. en nuestro caso vamos a usar los modulos:


|      | Nombre producto|
| ----------- | -----------   |
| ![](https://i.imgur.com/5Cz3X9Y.png) |**MÓDULO LECTOR DE MEMORIA MICRO SD CARD**|
| ![](https://i.imgur.com/ERuHQTI.png) |**Módulo CANBUS con MCP2551** |
|![](https://i.imgur.com/pibkGdK.png)|**MÓDULO MPU6050: ACELERÓMETRO, GIROSCOPIO I2C** |

En esta etapa debemos analizar el circuito de los distintos modulos y averiguar que simbolo no esta en la libreria de simbolos por defecto de kicad.

Cuando el simbolo no existe en kicad tenemos 2 opciones:

*  **Buscar componentes en la web**
Antes de dibujar un simbolo nuevo es conveniente averigar si alguien ya lo ha hecho , de este modo nos podriamos ahorrar un valioso tiempo
*  **Dibujar comoponente**
Si no se encontro el componente es necesario dibujarlo para esto abrimos el [Editor de simbolo](Editor%20de%20simbolo.md) 

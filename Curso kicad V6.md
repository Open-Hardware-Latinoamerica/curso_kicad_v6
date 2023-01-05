## Introduccion 

### Porque usar Kicad?
1. Libre
2. Ligero
3. Multiplataforma
### Proyector hechos en Kicad

### Elementos de kicad

* [[Editor de esquema]]
* [[Editor de simbolo]]
* [[Editor de PCB]]
* [[Editor de footprint]]
* [[Gerber view]]
* [[Conversor de imagen]]
* [[Calculadora]]
* [[Editor de hoja]]
* [[Pluging]]

![](https://i.imgur.com/RCOImkz.png)

## Alcance del curso

Disenar y fabricar una placa de desarrollo en la que se puedan probar lo distintos perifericos disponibles en un stm32f1XX (bluepill)
![bluepill](https://i.imgur.com/QzVFhJl.png)

Los perifericos disponibles seran:

| Periferico      | Descripcion   | Cantidad |
| ----------- | -----------   |---------------|
| GPIO        | Boton         | 2 |
| GPIO        | LED           | 3 |
| ADC         | Potenciometro | 1 |
| Timer       | Encoder       | 1 |
| UART        | Wifi          | 1 |
| SPI         | MicroSD       | 1 |
| I2C         | OLED          | 1 |
| I2C         | Acelerometro  | 1 |
| CAN         | J1939         | 1 |

## Procedimiento para iniciar un proyecto electronico

### Acotar el alcance
Si no se hace un alcance del proyecto se corre el riesgo que el proyecto nunca termine debido a que siempre se van a querer agregar funciones, es por esta razon que lo mas recomendable es tomarse un tiempo para dibujar que es lo que se quiere en el proyecto, discutirlo con el equipo de trabajo o cliente. 

Yo recomiendo usar [[Inkscape]] para realizar este tipo de esquemas, se pueden realizar diagrama de bloque con los detalles y es facil de entenderlo por todos los integrantes del grupo.

Otro cosa que se puede viasular aqui es, como quiero que se vea mi PCB o mi producto final, debo acegurarme que la ubicacion de los botones  leds tiene una ubicacion ergonimica para el usuario final, en caso que el proyecto lleve una carsada eso ayudara mucho cuando se disene la carcasa.

### Reciclaje de componentes

El segundo objetivo de este curso es que podamos fabricar la PCB y que le demos un uso poductivo.

Los componentes que usaremos seran componentes SMD y debido a que en el mercado latinoamericano no se encuentra mucha varierdad, optaremos por reciclar.

En que consiste? Tomaremos modulos chinos "Conocidos" extraer el circuito y el footprint de cada componente, este metodo es sumamente practivo y economico debido a que en todas partes del mundo llegan estos modulos.

| Ventajas      | Desventajas   |
| ----------- | -----------   |
| No se gasta dinero en importacion de los componentes | Se deben tener los modulos antes de hacer el diseno del PCB|
| El proyecto se basa en circuitos probados| Se debe contar con estacion de calor y tener destreza para soldadura SMD|

## Terminacion de PCB

La PCB se realizara en 2 capas con tamano minimo de componente de 0603, considerarn que estos sean los componentes dispuestos en los modulos chinos.

De esta foma se garantiza que los componentes se puedan soldar facilmente.

## [[Acerca de mi]]




## Sigueinte tema: [[Editor de esquema]]


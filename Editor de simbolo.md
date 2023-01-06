[Importar simbolo](Importar%20simbolo.md)

## Partes de la ventana de edicion de simbolos. 

![](https://i.imgur.com/1Mlgmko.png)

## Crear nuevo libreria

Para crear un simbolo es necesario crear una nueva libreria en un entorno local de simbolos, si eres una persona que se dedica o se va a dedicar al diseno de PCB aconsejo que se crea una biblioteca por cada categoria de componentes ademas de agregar un prefijo personal, por ejemplo:

* mr_Fuentes conmutadas
* mr_Encoders
* mr_Microcontroladores
* mr_Conectores

De esta forma sera mas facil mantenerlas cuando se quiera [Sincronizar con github](Sincronizar%20con%20github.md) y no se corre el riesgo de que se puedan llamar igual a las libririas por defecto.

## Crear Simbolo

Una vez se tiene la libreria creada se procede a crear un simbolo, para esto se escoje la libria creada previamente.

El nombre del simbolos es importante y existe un acuerdo llamado [KLC Symbols](https://klc.kicad.org/symbol/)  (TAMBIEN PARA NOMBRE DE BIBLIOTECA PERO SE VERA DESPUES ) propuesto por kicad donde se especifican la forma en que se debe escribir, si se hace siguiendo este acuerdo nuestro simbolo pueder ser enviado a las librias oficiales de kicad y ser integradas en la proxima actualizacion.

### Directrices generales de denominación de símbolos

1.  El nombre de la biblioteca no debe duplicarse en el nombre del símbolo
2.  Si existe un símbolo con el mismo nombre para varios fabricantes, el nombre del fabricante se escribe primero
3.  Los símbolos completamente especificados se nombran según el número de pieza del fabricante.
	1.  Si varios fabricantes producen piezas compatibles pero sus sufijos de número de pieza para especificar el paquete difieren, entonces se usa el número de pieza base común con un sufijo de nombre claro para la huella (p. ej ., `L78L05_TO92`)
	2.  Las partes no funcionales del MPN deben reemplazarse con un comodín. (Consulte los [requisitos para el uso de comodines en MPN](https://klc.kicad.org/symbol/s2/s2.2) )
5.  Los símbolos genéricos utilizan el tipo de dispositivo
    1.  Puede abreviarse para componentes comunes (p. ej ., `Conn` para `Connector`)
    2.  El designador de referencia puede sustituirse por componentes comunes (p. ej `D`., `C`, `LED`)
6.  Indique la cantidad de elementos para matrices de símbolos (p. ej., matriz de resistencias con 8 elementos - `Resistor_x8`)
7.  Cualquier modificación del símbolo original, indicado agregando el motivo
    1.  Diferente orden de pines - `Q_NPN_CBE`,`Q_NPN_BCE`
    2.  Para variantes de unidades múltiples de símbolos típicamente de una sola unidad, agregue el sufijo`_Split`

![](https://i.imgur.com/eBPDzQj.png)

**Nombre del simbolo :** aqui es donde se aplican las [[#Directrices generales de denominación de símbolos]] antes mensionadas.

**Designador por defecto :** Este valor depende del tipo de componente para mas detalles puede ver la seccion  [Designador de referencia de componente](https://klc.kicad.org/symbol/s6/s6.1/)

Los demas valores los dejaremos como estan

### Requerimientos generales del dibujo

1. Debe estar centrado
2. La regilla debe estar en 1.27mm (50mil)
3. El cuerpo del símbolo debe tener un ancho de línea de `10mil`( `0.254mm`)

### Funcion de pines y ubicacion

La funcion de los pines debe estar de acuerdo a la funcion que cumplen en el componente, por ejemplo la entrada de potencia debe estar como `input_power` pines GPIO de un MCU por ejemplo debe estar como `biderectional` 

## Agregar modelo 3D

Solo se debe [Agregar modelo 3D](Agregar%20modelo%203D.md) cuando el componente es unico y no tiene variaciones, en caso contrario se debe dejar el campo en blanco y completarse en el edito de esquema

Volver a [Editor de esquema](Editor%20de%20esquema.md)

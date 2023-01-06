El editor de esquema tiene multiples parametros que pueden ser configurados para mejorar la productividad, estos son:

### Plantilla de nombre

Esto es importante configurarlo para agegar metadata el componente, valores como voltaje del capacitor, corriente maxima del capacitor o numero de parte del fabricante. estos datos seran usado posteriormente para la lista de materiales  (BOM)

| Nombre de campo      | Funcion   |Visible|
| ----------- | -----------   |----------------------|
|   NPM      | Numero de parte del fabricante         | No |
| PLACE| Indica si el componente se incluira se soldara o no| Si |
|V| Voltaje maximo del capacitor|Si|
|P| Potencia maxima de la resistencia|Si|
|I| Corriente maxima del inductor|Si|
|Tol| Presion de la resistencia|Si|
|TC| Cohefiente termico del capacitor|Si|

### Configuracion de pagina

En este apartado se asignan los siguientes parametros.

| Nombre de campo      | Funcion   |
| ----------- | -----------   |
|Fecha de creacion|Es preferible marcarlo desde el primer momento que se crea el proyecto, asi sabes cuanto tiempo te tomo hacerlo|
|Revision | Indica que version del proyecto se esta realizando|
|Titulo| Nombre del proyecto|
|Empresa| Nombre de la empresa en la que trabajas|
|Comentario 1| Colocaremos el nombre del autor|
|Comentario 2| Colocaremo el nombre de un revisor|

### Formato de la hoja

yo recomiendo usar solo 2 timpos de formatos, el formato A4 y el formato A3 y siempre en horizontal

### Configuracion hoja de dibujo

Configuramos un formato de hoja segun norma ANSIS o ISO para colocar los detalles antes mensionados, esto lo haremos usando [[Crear entorno local|variables de entorno]] y la hoja la editaremos con el [[Editor de hoja]] y quedara como plantilla para proyectos futuros 

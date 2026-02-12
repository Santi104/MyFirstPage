# MyFirstPage

Join this page, and enjoy the experience!

------------------------------------------------------------------------

## Question #1

El HTML segun mis conocimientos, se puede decir que es como el esqueleto
de las paginas web, es en donde nosotros le proporcionamos la
informacion necesaria al navegador para que comprenda que informacion
debe mostrar en pantalla, texto, y la ser el esqueleto no hay forma de
generarle "estilo" avanzado a la que desarrollamos.

------------------------------------------------------------------------

## Question #2

Una etiqueta HTML es una forma de decirle a la web, que se le va a
inyectar un tipo de informacion en especifico, bien sea como:

-   title -\> que se encarga de como su nombre lo dice permitir que toda
    informacion ingresada sea convertida en titulo (exactamente en el
    titulo que tendra toda la pagina.)

-   h1 y sus subtipos --\> Un formato que permite agregar texto de
    titulo (que a diferencia de title genera texto dentro de la pagina.)

-   ```{=html}
    <p>
    ```
    --\> esta etiqueta que permite crear un parrafo dentro de la web, y
    que trae consigo un tamaño predeterminado de fuente.

-   div, header, section, footer --\> por asi decirlo es una forma de
    segmentar la informacion que manejamos y agregamos dentro de html.
    por ejemplo el header es la cabecera de nuestra pagina especialmente
    usado para barras de navegacion, y el footer por asi decirlo el pie
    de pagina, la seccion mas inferior de la pagina.

-   `<a>`{=html} --\> para el manejo de enlaces, y conexiones entre
    secciones de nuestro proyecto.

-   img --\> para insertar imagenes a la nuestro proyecto web.

------------------------------------------------------------------------

## Question #3

un atributo en html son por asi decirlo configuraciones adicionales que
se le pueden agregar a las etiquetas previamente mencionadas,
permitiendo nuevas funcionalidades.

Las mas comunes:

*Class *id *href *src

------------------------------------------------------------------------

## Question #4

El CSS es un lenguaje utilizado para permitir desarrollar un mejor
aspecto visual a las paginas web, asignando color, cambio de fuente,
tamaños, posiciones, entre otros.

------------------------------------------------------------------------

## Question #5

Una propiedad en css es una caracteristica que se le agrega a un
elemento permitiendo cambiar su apariencia.

Las mas comunes:

color, background-color, font-family, font-size, width, height, margin,
display.

------------------------------------------------------------------------

## Question #6

Los selectores es una forma de aplicar estilos a elementos especificos
de html

Selector de etiqueta: p { }

clase: .clase { }

id: #id { }

universal: \* { }

descendente: div p { }

hijo directo: div \> p { }

de atributo: input\[type="text"\] { }

Pseudoclases: a:hover

Pseudoelementos: p::first-letter

------------------------------------------------------------------------

## Question #7

Es un lenguaje de programacion que permite agregar interactividad a las
paginas web, esto lo hace por medio de peticiones, consultas y
solicitudes al HTML o CSS.

------------------------------------------------------------------------

## Question #8

Los datos primitivos en JavaScript son:

String Number Boolean Null Undefined BigInt Symbol

------------------------------------------------------------------------

## Question #9

Son estructuras que permiten hacer condiciones o bucles en determinadas
tareas, con el fin de evitar lo mas posible la redundancia de codigo.

------------------------------------------------------------------------

## Question #10

La estructura if else permite crear condiciones de que pasaria sí y en
caso de que no, es una forma de darle al codigo parametros en caso de
que cumpla la condicion o no.

switch se puede ver como una mejor version de un if anidado permitiendo
analizar con mayor rapidez una gran variedad de posibles casos, a
comparacion del if que usa condiciones.

y por ultimo los bucles permiten generar una serie de procesos por una
determinada cantidad de veces (a veces infinitos), todo bucle parte de
una condicion encargada de romper la cadena de eventos (parar el bucle)
y su funcionamiento basicamente es mientras que tal variable sea menor
que un valor se repetira la logica que creemos al interior de este.

------------------------------------------------------------------------

## Question #10

Permiten identificar a simple vista el rol que cumple la variable o
metodos que se esta llamando, con el fin de reducir errore y mejorar la
legibilidad.

------------------------------------------------------------------------

## Question #11

una variable de entorno es un valor con nombre dinamico en la
computadora que puede influir en el comportamiento de los procesos en
ejecucion. en si son datos que pueden guardar informacion de fuentes
externas al codigo, por ejemplo como informacion sobre la conexion a la
base de datos, puertos de servidor, ubicacion de archivos, entre otros.

------------------------------------------------------------------------

## Question #12

Son como su nombre lo dice herramientas que nos ofrece el navegador
Chrome (o si mal estoy la mayoria de navegadores) para permitir observar
de forma mas logica los elementos que la conforman, y asi permitir
depurar e inspeccionar las paginas web.

------------------------------------------------------------------------

## Question #13

El panel elements permite ver o modificar el html de la pagina, asi
mismo con sus estilos. Mas que todo es una forma de poder testear de
forma practica parte del frontend de la pagina en tiempo real, sin dañar
los cambios ya efectuados en el editor.

------------------------------------------------------------------------

## Question #14

El apartado Console o consola es el encargado de mostrar los errores
ocasionados en gran parte por procesos o logica proveniente del
JavaScript de la pagina, ademas de poder insertar codigo JS en el mismo
lugar.

------------------------------------------------------------------------

## Question #15

El panel Network esta orientado a todo lo relacionado con las conexiones
de la pagina, muestra lo que son peticiones HTTP, los tiempos de carga,
archivos cargados, entre otros. Esto es importando debido a que permite
detectar errores provenientes de las conexiones internas de nuestra
pagina web, observar el rendimiento de los tiempos de carga, y el uso de
las APIs
# Practica2-DIW

**Pregunta 1**

1.1 ¿En qué́ consiste el efecto de faux columns o columnas falsas Pon un ejemplo propio de su utilización.

Es una técnica que consiste en simular columnas de la misma altura cuando en realidad estas columnas no la tienen. Esto suele hacerse, por ejemplo, con fotos de fondo que disimulen la diferencia de altura entre columnas.

Supongamos que tenemos una página con dos columnas, las dos son independientes y tienen informaciones diferentes, una con más cantidad que otra, por lo que una será más grande que otra.
Para aplicar el efecto se coloca una foto de fondo en el contenedor general con los colores correspondientes a las columnas, para que parezca que tengan la misma altura


1.2 ¿Cuáles son los cinco estados de los enlaces Crea un ejemplo con HTML y CSS en el que se aprecie el funcionamiento de cada uno de ellos.

- Link El estado por defecto del enlace.

- Visited El enlace cuando se ha visitado.

- Hover Un enlace cuando se le pasa el cursor por encima y cambia de apariencia.

- Active El enlace cuando está siendo clicado.

- Focus El enlace cuando tiene el foco, por ejemplo cuando le damos al tabulador y vamos seleccionando.


1.3 Pon un ejemplo propio de correcta utilización de cada uno de los tipos de lista, explicando por qué es el tipo más adecuado en cada caso.

Encontramos 3 tipos de listas, desordenada, ordenada y definición

- Lista desordenada (ul): Es utilizada cuando el orden de los elementos es irrelevante, como por ejemplo si quisieramos hacer una lista de la compra.

- Lista ordenada (ol): Se utiliza cuando el orden si es importante como por ejemplo los pasos de un tutorial.

- Lista de definición (dl): Se utiliza para presentar terminos concretos con su definición como por ejemplo en un tutorial, se podrían explicar los tecnicismos mediante una lista de definición.

**Pregunta 2**

2.1 ¿En qué́ propiedad/es del modelo de cajas se pueden aplicar valores negativos? Pon un ejemplo en el que tenga sentido hacerlo.

Se pueden aplicar valores nagativos en el "margin" para mover elementos hacia afuera del contenedor en el que se encuentre.

2.2 ¿Para qué́sirven las propiedades min-width , max-width , min-height y max-height ? Pon un ejemplo propio de su utilización.



- Min-width: Establece el ancho mínimo que puede tener un elemento. Si el contenido es más pequeño, el elemento seguirá teniendo este ancho.
  
- Max-width: Define el ancho máximo que puede tener un elemento. Si el contenido excede este ancho, el elemento no crecerá más.

- Min-height: Establece la altura mínima que puede tener un elemento.

- Max-height: Define la altura máxima que puede tener un elemento.

2.3 Describe el funcionamiento de la propiedad overflow y sus posibles valores. Investiga posibles usos de interés de esta propiedad.

La propiedad overflow controla cómo se manejan los contenidos que exceden el tamaño de un elemento. Sus posibles valores son:

- Visible: El contenido que se desborda se muestra fuera del elemento. Este es el valor predeterminado.

- Hidden: El contenido que se desborda se oculta y no se puede acceder.

- Scroll: Se agrega una barra de desplazamiento para permitir al usuario desplazarse por el contenido desbordante, tanto vertical como horizontalmente.

- Auto: Se agregan barras de desplazamiento solo si el contenido se desborda. Si no hay desbordamiento, no se muestran.

**Pregunta 3**

3.1 ¿En qué consiste el Quirks mode? ¿De qué forma hay que tenerlo en cuenta al diseñar nuestras páginas?

Quirks mode es un modo de renderizado en los navegadores web que imita el comportamiento de los navegadores antiguos. Este modo se activa cuando una página web no incluye una declaración de tipo de documento (doctype) o si utiliza un doctype que no es estándar.

3.2 ¿Cuáles son las principales características que debe tener una página web para ser accesible? Pon ejemplos de cada una de ellas.

Disponible: El contenido debe estar disponible para todos, utilizando alternativas textuales y adaptabilidad para usuarios con discapacidades sensoriales.

Operable: El sitio debe poder ser usado con diferentes dispositivos.

Comprensible: El contenido debe ser claro y fácil de entender y utilizar un lenguaje simple.

Robusto: El sitio debe estar preparado para ser accesible en el futuro.


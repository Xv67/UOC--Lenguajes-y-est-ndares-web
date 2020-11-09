# UOC--Lenguajes-y-estandares-web-ACT2
Trabajos de parciales de la asignatura


Explicación de las entidades utilizadas.

Encabezado:

Hemos de usar el mismo encabezado para las tres páginas. En el mostramos el título del documento común a todas las páginas, que no ha de ser un h1 sino un elemento de menor importancia ya que no va a otorgar información relevante ni jerarquizar el contenido de las páginas. Además, establecemos el menú de navegación, <nav>.

Como la imagen de fondo forma parte del decorado la he colocado a través del css.

Para ajustar el tamaño y la posición del título he ajustados los valores de la propiedad padding, además de ajustar el tamaño y el color de la letra, y el sombreado.

Agregué un borde y un fondo de color al párrafo, con cierto grado de opacidad para que me permita ver la imagen de fondo. 

Las imágenes de fondo se superponen unas con otras y es por eso que se puede lograr este efecto alterando la opacidad.

Para lograr que la imagen ocupe todo el ancho de la pagina establecí el valor cover de la propiedad background-size, y background-repeat: no-repeat para que se rellene utilizando la misma imagen y que no se rellene agregando otra imagen.

Para lograr que la imagen del fondo del titulo y el fondo negro del menú de navegación se muestren unidos he modificado el margen de la imagen con valor negativo.

Para quitar los bullet point de los elementos de la lista del menú de navegación establece el valor none a la propiedad list-styel.

Establecí el ancho y el alto deseado, el color de fondo y el color de las letras, tamaño y estilo de las letras.

Para que se los list ítems se muestren uno al lado del otro modifique la propiedad display al valor inline-bloque, y luego los distancie acomodando sus márgenes.

Para centrarlos me valí de la pseudoclase ::first-child y modifiqué el margen izquierdos del primer list ítem.

Alteré los valores iniciales del elemento a, para eliminar el subrayado text-decoration: none; y para 

Luego modifique las pseudoclases interactivas :hover, para alterar el estilo cuando se pasa el cursor por encima, en esta pseudoclase, modifique el color de fondo y ajuste el tamaño de los padding para lograr que el fondo se ajuste al fondo negro.
 :link el color inicial y :visited para que los enlaces se sigan viendo blancos luego de visitados.

Pie de página:

Para el pie de página utilice las mismas dimensiones que el menú de navegación, para ajustarlo al ancho de la página. (creo que debe haber una forma más específica de hacerlo pero no la estoy pudiendo encontrar.)

Luego, para modificar el enlace utilice las mismas reglas que para modificar los encales en la barra de navegación.

Imágenes:

Las imágenes están ubicadas dentro de la carpeta images que se encuentra dentro de la carpeta css (esta se encuentra en la misma ubicación que nuesro archivo index.html) entonces la ruta que apunta a todas ellas es la misma “css/images/nombre-de-la-imagen”.

El atributo alt es el que nos permite describir la imagen en caso de que la página se cargue mál y no pueda mostar nuestra imagen o en caso de AT.

A través del atributo title he proporcionado más información respecto de la imagen.

He utilizado los elementos <figure> y <figcaption> con el propósito de proporcionar un contenedor semántico para las figuras y vincularlas claramente con su pie de página.

He utilizado un elemento <div> con una clase especial para darle estilo a todo el cuerpo del articulo.

El <footer> tiene un estilo particular que he ajustado a través de CSS.

Las imágenes que se encuentran en la página index, han sido sombreadas mediante box-shadow y ajustadas en la posición deseada modificándole los márgenes.

Los bloques de información de la pagina diseño:

Agregar la propiedad max-width: 100% al elemento img nos permitirá ajustar la imagen a un tamaño menor que la caja, pero nunca uno mayor.

Cada bloque fue contenido por un elemento div que les dio el borde negro fino y el borde superior grueso de color azul.

El elemento div es una caja que por naturaleza se despliegua en bloque, pero esto puede ser modificado a través de los valores que le atribuyamos a la propiedad display. 
En este caso utilicé su valor inline-block que genera una caja de elemento de bloque que fluye con el contenido circundante como si fuera una sola caja en línea 


Para redondear la imagen utilce la propiedad border-radius.
Para ubicarla en la parte superior modifiqué los valores margin-top.

El sombreado  se lo he dado utilizando la propiedad box-shadow.

Página Index:

Los títulos de todas las páginas han sido mdificados mediante 3 clases básicamente.

El tamaño de letra y el alineado, así como también la sangría, los especifiqué en la clase .container, que es la que contiene el cuerpo de todas las páginas.

Página Colores:

He armado las listas de definición utilizando las etiquetas <dl>
Los términos a definir enmarcados en las etiquetas <dt>
Y las definiciones en <dd>

La propiedad border-radius permite arquear las esquinas del borde de la caja. Los valores utilizados:
/* (first radius values) / top-left | top-right | bottom-right | bottom-left */
border-radius: 10px 5% / 20px 25em 30px 35em;
Aunque no he conseguido arquear la esquina superior izquierda como realmente era.

Para que se superpongan los dos bordes he ajustado los márgenes superiores e inferiores para no se doblen.

Ajusté la sangría de los títulos mediante la propiedad text-indent; y el alineado del texto en cada caja, mediante text-align Así como la separación entre líneas a través de la propiedad line-height.

Acomodé el tamaño de las imágenes mediante la propiedad width, en una regla css con los selectores específicos que las identificara, y las ubique ajustando los padding.

He creado listas desordenadas para acomodar los diferentes ítems dentro de la definición y cambie el icono utilizando la propiedad content pero primero removí el bullet point mediante la propiedad list-style: none.
Modifiqué los márgenes y la indentación para acomodar la separación.
Utilice el pseudo elemento :before para añadir el carácter ante de cada list ítem. 













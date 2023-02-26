[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9908037&assignment_repo_type=AssignmentRepo)

# Proyecto DIW - DWECL

## ÍNDICE

1. [DESCRIPCIÓN](#id1)
2. [PROTOTIPO](#id2)
3. [MODIFICACIONES A LA GUÍA DE ESTILOS](#id3)
4. [ENTREGA 4](#id4)
5. [RECURSOS](#id5)

## DESCRIPCIÓN<a name="id1"></a>

Tienda online especializada en productos CBD. Contamos con un gran catálogo de productos CBD y
nuestro principal objetivo es ayudar con este producto desconocido o mal visto a personas que realmente
necesitan este producto, para mejorar en calidad de vida a un precio razonable.

## PROTOTIPO<a name="id2"></a>

- Figma: https://www.figma.com/file/H6EygoKHnAPwDWw7BzolCw/Figma-Roca?t=Dnu428EX7Q70h3eD-0

## MODIFICACIONES A LA GUÍA DE ESTILOS<a name="id3"></a>

- Tarjeta de productos:

La descripción del producto y el nombre del mismo por motivos estéticos los deje con el
fondo uniforme verde, no me gustaba como quedaba con el fondo en blanco, como el figma,
pero si que me parecía estético con la sombra y el mismo color.

- Logo de la página:

En el figma lo que tenía era solo un titulo, pero me decidí a crear uno en canva, me parece
más estético y profesional.

- Foto de perfil:

Le añadí una foto de una silueta, me parece más estético.

- Fuente de la página:

Después de realizar diferentes pruebas, finalmente utilicé la Roboto Regular 400 para toda la página. Es la que más
me gusto y se adapta a una mejor legibilidad a mi parecer. Para los titulos de productos y producto usé Arial con unos efectos de CSS.

- Iconos de las redes sociales del footer:

Quité uno que no me parecía útil para nada, además los agrandé un poco, y para que sean más visibles
no le puse el border-radius, así creo que destacan más.

- Inputs de registrarse:

Añadí el teléfono de contacto y los organicé para una mejor lectura.

- Perfil:

El acceso a la página del perfil es mediante click en la foto de perfil, soy consciente de que no es del todo intuitivo y de hecho pensé en añadir
un nuevo enlace en el menú del navbar, pero creo que no tiene mucho sentido teniendo en cuenta que el problema real es la falta de una vista con el
login ya realizado, así que para mantener lo expuesto en el figma lo solucioné de esta manera.

Añadido botón cancelar que te devuelve al index, para el caso de no querer modificar nada.

- Pedidos:

Le quité el borde a la tabla, me parece que estaba feo. También aplique un diseño diferente a los tr, de forma alterna a pares, creo que queda mejor.
Además le añadí un border-radius a la tabla para seguir la línea de la página.

- Inicio:

Añadí una página más para el inicio, es una página básica de bienvenida.

- Producto:

Añadí una página de producto, la hice como una demo al hacer click en un producto, lleva al mismo producto siempre. También añadi un border-radius a las imagenes.

## ENTREGA 4<a name="id4"></a>

- Transiciones:

Están en el menú de la página, botón de búsqueda, fotografía de perfil, iconos de redes sociales del footer y en las tarjetas de productos. Se seleccionaron estos
elementos para darle algo de movimiento y fluidez a la página.

- Animaciones:

Están en el logo tal y como se pide en la actividad 3, además de aplicar un movimiento de la imagen de las tarjetas de los productos al hacerle foco con el ratón (:hover). Se seleccionaron estos elementos para llamar la atención del cliente, principalmente en el caso de los productos.

- Interactividad:

En la página de Contacto añadí el <\details> con el gif, y el <\dialog> donde mismo, accionado por el botón "Llamame".

- Imágenes:

Le añadí un filtro de escala de grises al hacer foco (:hover), dejé comentada la opción de cambiar la imagen por la de blanco y negro con content mediante CSS.

- Audio:

Chrome por defecto bloquea el audio y video en autoplay, en el caso del video simplemente lo ponemos en mute y listo, pero el audio en mute no tiene sentido. Para poder solucionarlo añadimos nuestra url local en contenido no seguro, permitiendo el sonido, en el caso del Mozilla pide permisos al navegar por la página, se lo concedemos y listo.

URL para configurar -> chrome://settings/content/insecureContent (Aquí añadimos la url del proyecto, por ejemplo: file:///home/roca/proyecto-diw-miguelangelroca/"archivo")

- Video:

El testimonio lo puse en la página de contacto, el video de fondo está en el index. 

Para mantener el diseño responsivo al bajar de los 600px se quita el video de fondo y vuelve la imagen de fondo original.

## RECURSOS<a name="id5"></a>

- CSS Reset: https://raulperez.tieneblog.net/mi-propio-css-reset/
- CSS Documentation: https://developer.mozilla.org/es/docs/Web/CSS

- Can I use?: https://caniuse.com/
- Bootstrap: https://getbootstrap.com/
- Tailwind: https://tailwindcss.com/docs
- W3C CSS Validator: https://jigsaw.w3.org/css-validator/
- W3C HTML Validator: https://validator.w3.org/

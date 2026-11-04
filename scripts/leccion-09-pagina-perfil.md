# Guion – Lección 9: Creando tu página de perfil

**Duración estimada:** 7 min
**Editor:** CodePen (https://codepen.io/pen/)
**Archivos:** `/starter-files/leccion-09-pagina-perfil` → `/completed-examples/leccion-09-pagina-perfil`

---

## 1. Introducción

**Narración:**
"¡Hola! Llegamos a la parte más emocionante del curso: vamos a juntar todo lo que aprendimos para crear nuestra propia página de perfil. Usaremos títulos, párrafos, listas, imágenes, enlaces y CSS. Al final tendrás una tarjeta de presentación que puedes compartir con tus amigos."

**Texto en pantalla:** Lección 9 – Tu página de perfil
**Visual:** Mostrar el resultado final terminado.

## 2. Preparar CodePen 

**Narración:**
"Abre CodePen; no necesitas instalar nada. Copia el código del archivo `index.html` de la carpeta starter-files, solo lo que está entre `<body>` y `</body>`, y pégalo en el panel HTML. Luego copia todo `style.css` en el panel CSS. CodePen conecta el HTML y el CSS solito."

**Texto en pantalla:** Panel HTML ← lo que está dentro de `<body>` · Panel CSS ← style.css
**Visual:** Pegar el código en cada panel.

## 3. Estructura HTML: pasos 1 a 6 

**Narración:**
"Empecemos con la foto. Usamos la etiqueta `img` con el atributo `src` para la dirección de la imagen y `alt` para describirla. Le agregamos la clase `foto` para darle estilo después."

"Ahora tu nombre va en un `h1`, porque es el título más importante. Debajo, un párrafo con la clase `subtitulo` para tu grado y tu ciudad."

"Agregamos un `h2` 'Sobre mí' y un párrafo contándonos qué te gusta. Luego otro `h2` 'Mis pasatiempos' con una lista `ul` y tres elementos `li`."

"Por último, un `h2` 'Mi sitio favorito' y un enlace `a`. Fíjate que el `href` empieza con `https://`. Con `target="_blank"`, el enlace se abre en otra pestaña."

**Texto en pantalla:** `<img>` · `<h1>` · `<p>` · `<h2>` · `<ul>` + `<li>` · `<a>`
**Visual:** Escribir cada paso y mostrar cómo cambia la vista previa.

## 4. Algo nuevo: las clases 

**Narración:**
"Antes de ir al CSS, algo nuevo. En la lección 7 aplicamos estilos a todas las etiquetas de un tipo, por ejemplo a todos los `h1`. Pero ¿y si queremos darle estilo solo a un elemento? Para eso usamos el atributo `class`, que es como ponerle un nombre o una etiqueta adhesiva. Por ejemplo, a nuestra imagen le pusimos `class="foto"`."

"En el CSS, para elegir una clase escribimos un punto antes del nombre: `.foto`. Así el estilo se aplica solo a los elementos que tienen esa clase."

**Texto en pantalla:** HTML: `class="foto"` → CSS: `.foto { }` · ¡No olvides el punto!
**Visual:** Flecha que une `class="foto"` en el HTML con `.foto` en el CSS.

## 5. Dar estilo con CSS: pasos 7 a 13 

**Narración:**
"Nuestra página ya tiene contenido, pero se ve muy simple. Vamos al panel CSS. Usaremos lo que aprendimos en las lecciones 7 y 8, y conoceremos algunas propiedades nuevas."

"En el `body` ponemos un fondo celeste claro, la fuente Arial y centramos el texto."

"A `.tarjeta` le damos fondo blanco y dos propiedades nuevas: `max-width: 400px`, para que no sea más ancha de 400 píxeles, y `margin: 40px auto`, que deja espacio por fuera y la centra en la pantalla. Con `padding`, que ya conocemos, dejamos espacio por dentro. Y otra propiedad nueva: `border-radius`, que redondea las esquinas."

"Si a la foto le ponemos `border-radius: 50%`, ¡se vuelve un círculo!"

"Cambiamos el color del `h1` a azul y el del subtítulo a gris. En la lista quitamos las viñetas con `list-style: none`."

"Y para terminar convertimos el enlace en un botón: fondo azul, texto blanco, algo de `padding` y esquinas redondeadas. Con `text-decoration: none` quitamos el subrayado, y con `display: inline-block` el padding funciona bien en el enlace."

**Texto en pantalla:** Propiedades nuevas: `max-width` · `margin` · `border-radius` · `list-style` · `text-decoration`
**Visual:** Escribir cada regla y mostrar el cambio en la vista previa.

## 6. Cierre

**Narración:**
"¡Listo! Ya tienes tu página de perfil. Cambia el nombre, la foto, los colores y los pasatiempos para que sea tuya. Puedes comparar tu código con la solución en la carpeta completed-examples. En la siguiente lección veremos los errores más comunes y cómo arreglarlos."

**Texto en pantalla:** ¡Personalízala! · Siguiente: Lección 10 – Errores comunes

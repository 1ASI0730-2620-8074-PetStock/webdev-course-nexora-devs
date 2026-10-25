# Guion – Lección 9: Creando tu página de perfil

**Duración estimada:** 6–7 min
**Editor:** CodePen (https://codepen.io/pen/)
**Archivos:** `/starter-files/leccion-09-pagina-perfil` → `/completed-examples/leccion-09-pagina-perfil`

---

## 1. Introducción (0:00 – 0:45)

**Narración:**
"¡Hola! Llegamos a la parte más emocionante del curso: vamos a juntar todo lo que aprendimos para crear nuestra propia página de perfil. Usaremos títulos, párrafos, listas, imágenes, enlaces y CSS. Al final tendrás una tarjeta de presentación que puedes compartir con tus amigos."

**Texto en pantalla:** Lección 9 – Tu página de perfil
**Visual:** Mostrar el resultado final terminado.

## 2. Preparar CodePen (0:45 – 1:30)

**Narración:**
"Abre CodePen; no necesitas instalar nada. Copia el código del archivo `index.html` de la carpeta starter-files y pégalo en el panel HTML. Luego copia `style.css` en el panel CSS. En CodePen no hace falta la etiqueta `<link>`, porque el CSS ya se conecta solo."

**Texto en pantalla:** Panel HTML ← index.html · Panel CSS ← style.css
**Visual:** Pegar el código en cada panel.

## 3. Estructura HTML: pasos 1 a 6 (1:30 – 3:45)

**Narración:**
"Empecemos con la foto. Usamos la etiqueta `img` con el atributo `src` para la dirección de la imagen y `alt` para describirla. Le agregamos la clase `foto` para darle estilo después."

"Ahora tu nombre va en un `h1`, porque es el título más importante. Debajo, un párrafo con la clase `subtitulo` para tu grado y tu ciudad."

"Agregamos un `h2` 'Sobre mí' y un párrafo contándonos qué te gusta. Luego otro `h2` 'Mis pasatiempos' con una lista `ul` y tres elementos `li`."

"Por último, un `h2` 'Mi sitio favorito' y un enlace `a`. Fíjate que el `href` empieza con `https://`. Con `target="_blank"`, el enlace se abre en otra pestaña."

**Texto en pantalla:** `<img>` · `<h1>` · `<p>` · `<h2>` · `<ul>` + `<li>` · `<a>`
**Visual:** Escribir cada paso y mostrar cómo cambia la vista previa.

## 4. Dar estilo con CSS: pasos 7 a 13 (3:45 – 6:00)

**Narración:**
"Nuestra página ya tiene contenido, pero se ve muy simple. Vamos al panel CSS."

"En el `body` ponemos un fondo celeste claro, la fuente Arial y centramos el texto."

"A `.tarjeta` le damos fondo blanco, un ancho máximo de 400 píxeles y `margin: 40px auto` para centrarla. Con `padding` dejamos espacio por dentro y con `border-radius` redondeamos las esquinas."

"Para que la foto sea un círculo usamos `border-radius: 50%`."

"Cambiamos el color del `h1` a azul y el del subtítulo a gris. En la lista quitamos las viñetas con `list-style: none`."

"Y para terminar convertimos el enlace en un botón: fondo azul, texto blanco, algo de `padding`, esquinas redondeadas y `text-decoration: none` para quitar el subrayado."

**Texto en pantalla:** Recuerda: las clases se seleccionan con un punto → `.tarjeta`
**Visual:** Escribir cada regla y mostrar el cambio en la vista previa.

## 5. Cierre (6:00 – 6:45)

**Narración:**
"¡Listo! Ya tienes tu página de perfil. Cambia el nombre, la foto, los colores y los pasatiempos para que sea tuya. Puedes comparar tu código con la solución en la carpeta completed-examples. En la siguiente lección veremos los errores más comunes y cómo arreglarlos."

**Texto en pantalla:** ¡Personalízala! · Siguiente: Lección 10 – Errores comunes

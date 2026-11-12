# Guion – Lección 9: Creando tu página de perfil

**Duración:** 5 min
**Editor:** CodePen
**Video:** https://youtu.be/Sq7geX_w4jA
**Práctica:** https://codepen.io/Nexora-Web-cu/pen/dPGBPQG
**Archivos:** `/starter-files/leccion-09-pagina-perfil` → `/completed-examples/leccion-09-pagina-perfil`

---

## Parte 1: Presentación (diapositivas)

**Diapositiva 1 – Portada**
"¡Hola! Bienvenido a la lección 9. Llegamos a la parte más emocionante del curso: vamos a juntar todo lo que aprendimos para crear nuestra propia página de perfil, como una tarjeta de presentación que puedes compartir con tus amigos. Vamos a usar HTML y CSS. ¡Empecemos!"

**Diapositiva 2 – ¿Qué vamos a construir?**
"Hoy vamos a construir una tarjeta de perfil, como las que ves en las redes sociales. Primero, con HTML, ponemos el contenido: tu foto, tu nombre, tu grado, algo sobre ti, tus pasatiempos y un enlace a tu página favorita. Después, con CSS, le damos diseño: colores, una tarjeta blanca centrada, una foto redonda y un botón. Y al final, la personalizas con tus propios datos para que sea solo tuya."

**Diapositiva 3 – Preparar CodePen**
"Para esta práctica vamos a usar CodePen, una página donde escribes código y ves el resultado al instante. No tienes que instalar nada, solo necesitas tu navegador. Abre el enlace que está en la descripción del video. Vas a ver tres paneles: HTML, CSS y JavaScript. Hoy solo usaremos HTML y CSS. Y abajo está la vista previa, donde verás cómo cambia tu página."

**Diapositiva 4 – Estructura HTML**
"Estas son las etiquetas que vamos a usar, y todas ya las conoces. img sirve para poner una imagen, como tu foto. h1 es el título principal, ahí va tu nombre. p sirve para escribir párrafos. h2 es un subtítulo, para separar las partes de la página. ul y li forman una lista, perfecta para tus pasatiempos. Y a crea un enlace para ir a otra página."

**Diapositiva 5 – Las clases**
"Hoy aprendemos algo nuevo: las clases. Imagina que pones una etiqueta adhesiva con un nombre en tu cuaderno para encontrarlo rápido. Una clase hace lo mismo: le pone un nombre a un elemento de la página. Por ejemplo, a la foto le ponemos class igual a foto. Después, en el CSS, la llamamos escribiendo un punto antes del nombre: punto foto. Así el estilo se aplica solo a ese elemento. ¡Que no se te olvide el punto!"

**Diapositiva 6 – Propiedades nuevas**
"También veremos propiedades nuevas de CSS. max-width pone un ancho máximo, para que la tarjeta no crezca demasiado. margin auto la centra en la pantalla. border-radius redondea las esquinas, y si le ponemos 50 por ciento, la foto se vuelve un círculo. list-style none quita los puntitos de la lista. Y text-decoration none quita la raya de abajo de los enlaces."

**Diapositiva 7 – Los 13 pasos**
"Haremos 13 pasos cortitos. Del paso 1 al 6 trabajamos en el HTML: agregamos la foto, el nombre, el grado, una parte sobre ti, tus pasatiempos y un enlace. Y del paso 7 al 13 trabajamos en el CSS: le damos color al fondo, armamos la tarjeta, hacemos la foto redonda y convertimos el enlace en un botón."

**Diapositiva 8 – Actividad práctica**
"¡Ahora te toca a ti! Vamos a CodePen."

---

## Parte 2: Práctica en CodePen

**Inicio**
"Esta caja main será nuestra tarjeta. Todo irá aquí adentro."

### HTML

**Paso 1 – Foto** · `<img src="..." alt="..." class="foto">`
"La etiqueta img pone una imagen. src es el enlace de la foto, alt la describe por si no carga, y class le pone el nombre foto para darle estilo después."

**Paso 2 – Nombre** · `<h1>`
"h1 es el título principal, el más grande. Lo usamos para el nombre."

**Paso 3 – Grado y ciudad** · `<p class="subtitulo">`
"p sirve para escribir párrafos. Le ponemos la clase subtitulo para cambiarle el color luego."

**Paso 4 – Sobre mí** · `<h2>` + `<p>`
"h2 es un subtítulo, más pequeño que h1. Sirve para separar las partes de la página."

**Paso 5 – Pasatiempos** · `<ul>` + `<li>`
"ul crea una lista y cada li es un elemento de la lista. ¡Hasta con emojis!"

**Paso 6 – Enlace** · `<a href="https://..." target="_blank" class="boton">`
"La etiqueta a crea un enlace. href es la dirección, siempre con https, y target blank lo abre en otra pestaña. Ya tenemos el contenido, pero se ve muy simple. ¡Vamos al CSS!"

### CSS

**Inicio**
"En CSS escribimos a qué le damos estilo, abrimos llaves y adentro ponemos las propiedades, cada una con punto y coma al final."

**Paso 7 – Fondo** · `body`
"body es toda la página. background-color cambia el fondo a celeste, font-family cambia la letra, y text-align center centra el texto."

**Paso 8 – Tarjeta** · `.tarjeta`
"Para llamar a una clase usamos un punto: punto tarjeta. Le damos fondo blanco, un ancho máximo de 400 píxeles, margin auto para centrarla, padding para el espacio por dentro, y border-radius para redondear las esquinas."

**Paso 9 – Foto redonda** · `.foto`
"Si redondeamos la foto al 50 por ciento... ¡se vuelve un círculo!"

**Pasos 10 y 11 – Colores** · `h1` y `.subtitulo`
"color cambia el color de las letras: el nombre en azul y el subtítulo en gris. Fíjate que h1 no lleva punto porque es una etiqueta, pero subtitulo sí, porque es una clase."

**Paso 12 – Lista** · `ul`
"list-style none quita los puntitos de la lista."

**Paso 13 – Botón** · `.boton`
"Y convertimos el enlace en un botón: fondo azul, letras blancas, espacio por dentro, esquinas redondeadas, y text-decoration none para quitar la raya de abajo. ¡Y listo! Mira cómo quedó nuestra tarjeta de perfil."

---

## Parte 3: Cierre

"¡Y listo! Pasamos de una página vacía a una tarjeta de perfil con diseño. Recuerda lo más importante: HTML pone el contenido, como la foto, el nombre y la lista, y CSS le da el estilo, como los colores, la tarjeta y el botón. Las clases se escriben con class en el HTML, y en el CSS se llaman con un punto. Ahora te toca a ti: cambia el nombre, la foto, los colores y tus pasatiempos para que sea solo tuya. Y si quieres comparar, la solución está en el repositorio. En la próxima lección aprenderemos a encontrar y corregir los errores más comunes. ¡Nos vemos!"

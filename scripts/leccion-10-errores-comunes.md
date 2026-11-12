# Guion – Lección 10: Errores comunes

**Duración:** 5 min
**Editor:** CodePen
**Video:** https://youtu.be/1uC0paN-yPw
**Práctica:** https://codepen.io/Nexora-Web-cu/pen/zxrVxEe
**Archivos:** `/starter-files/leccion-10-errores-comunes` → `/completed-examples/leccion-10-errores-comunes`

---

## Parte 1: Presentación (diapositivas)

**Diapositiva 1 – Portada**
"¡Hola de nuevo! Bienvenido a la lección 10, la última del curso. Hoy vamos a aprender algo muy importante: cómo encontrar y corregir los errores más comunes en HTML y CSS. Esto te va a servir en todas las páginas que hagas."

**Diapositiva 2 – ¿Qué es un bug?**
"A los errores en el código les llamamos bugs, que en inglés significa bichos. Equivocarse es completamente normal: hasta los programadores con muchos años de experiencia cometen errores todos los días. Lo importante es saber encontrarlos y corregirlos. En esta lección hay 6 errores escondidos: 3 en el HTML y 3 en el CSS."

**Diapositiva 3 – La misión**
"Esta es la página de perfil que hicimos en la lección anterior, pero ahora tiene errores. A la izquierda ves cómo se ve con errores: no hay foto, el texto está gigante y no hay tarjeta. A la derecha ves cómo debería verse. Tu misión es arreglarla."

**Consejos**
"Antes de empezar, tres consejos para encontrar errores. Primero, revisa que cada etiqueta que abres también se cierre. Segundo, fíjate en los colores del editor: si una palabra tiene un color raro, puede estar mal escrita. Y tercero, haz un cambio a la vez y mira la vista previa, así sabes qué arregló cada cambio."

**Diapositiva 4 – Actividad práctica**
"Ahora pausa el video e intenta encontrar los errores tú solo. ¿Listo? ¡Vamos a CodePen a cazarlos juntos!"

---

## Parte 2: Práctica en CodePen

**Inicio**
"Mira la vista previa: no hay foto, el texto se ve gigante y no hay tarjeta. Empecemos por el HTML."

### HTML

**Error 1 – Atributo mal escrito** · `scr` → `src`
"La foto no aparece. Si miramos bien, dice s c r, pero lo correcto es s r c, que viene de source, fuente en inglés. El navegador no entiende scr, así que lo ignora. Lo corregimos... ¡y ya aparece la foto!"

**Error 2 – Etiqueta sin cerrar** · `<h1>` → `</h1>`
"Todo el texto se ve gigante. Es porque el h1 nunca se cerró: a la etiqueta del final le falta la barra. Sin ella, el navegador cree que todo lo que sigue es parte del título. Agregamos la barra... y el texto vuelve a su tamaño normal."

**Error 3 – Enlace sin https://** · `developer.mozilla.org` → `https://developer.mozilla.org`
"El botón no lleva a MDN. Al enlace le falta https dos puntos barra barra. Sin eso, el navegador busca la página dentro de nuestro propio sitio y no la encuentra. Lo agregamos, y listo. El HTML ya está bien. Ahora vamos al CSS."

### CSS

**Error 4 – Propiedad mal escrita** · `colour` → `color`
"La tarjeta no se ve blanca. Escribimos colour con u, como se escribe en inglés británico, pero CSS solo entiende color, sin u. Borramos la u... ¡y aparece la tarjeta blanca!"

**Error 5 – Falta el punto de la clase** · `foto` → `.foto`
"La foto no es redonda. Al selector le falta el punto. Sin punto, CSS busca una etiqueta llamada foto, que no existe. Recuerda: las clases siempre llevan punto en el CSS. Lo agregamos... ¡y ahora sí es un círculo!"

**Error 6 – Falta el punto y coma** · `color: #1a73e8` → `color: #1a73e8;`
"El nombre no cambia ni de color ni de tamaño. Falta el punto y coma al final de la línea. Sin él, CSS junta esta línea con la siguiente y no entiende ninguna de las dos. Agregamos el punto y coma... ¡y listo!"

**Final de la práctica**
"¡Lo logramos! Corregimos los 6 errores y la página quedó perfecta. Recuerda que equivocarse es parte de aprender. Ahora repasemos lo que corregimos."

---

## Parte 3: Resumen y cierre (diapositivas)

**Resumen: errores en HTML**
"Repasemos los errores del HTML. Primero, un atributo mal escrito: en la imagen decía scr en vez de src, y por eso la foto no aparecía. Segundo, una etiqueta sin cerrar: al h1 le faltaba la barra en la etiqueta del final, y todo el texto se veía gigante. Y tercero, un enlace sin https: sin esa parte, el navegador no encuentra la página. Recuerda: revisa siempre cómo escribes los atributos y que cada etiqueta se cierre."

"Un truco: cuando la página se vea rara, revisa primero el HTML. Muchas veces el problema es una letra cambiada o una etiqueta que olvidaste cerrar. Lee tu código despacio, línea por línea, como si fuera un texto."

**Resumen: errores en CSS**
"Y en el CSS también encontramos tres errores. Primero, una propiedad mal escrita: colour con u no existe, lo correcto es color, sin u. Segundo, una clase sin punto: en el CSS, las clases siempre se escriben con un punto adelante, como punto foto. Y tercero, un punto y coma que faltaba: cada propiedad debe terminar con punto y coma, si no, CSS no entiende esa línea ni la siguiente. Un solo símbolo puede cambiar toda la página."

"En el CSS, revisa siempre tres cosas: que las propiedades estén bien escritas en inglés, que las clases tengan su punto, y que cada línea termine con punto y coma. Si cumples eso, evitarás la mayoría de errores."

**Próximos pasos**
"¡Felicitaciones, terminaste el curso! Ya sabes crear una página web con HTML y CSS, y también sabes encontrar y corregir errores. Si quieres seguir aprendiendo, te recomendamos dos páginas gratuitas en español: MDN Web Docs, donde puedes consultar cualquier etiqueta o propiedad, y freeCodeCamp, donde puedes practicar con retos. El siguiente paso es aprender JavaScript, el lenguaje que le da movimiento e interactividad a tus páginas. ¡Sigue practicando y crea muchas páginas! ¡Nos vemos!"

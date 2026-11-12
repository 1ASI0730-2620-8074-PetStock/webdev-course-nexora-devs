# **Lección 2: Tu primera página HTML**

**Duración total:** 5 min
**Editor:** CodePen (https://codepen.io/pen/)
**Archivos:** /starter-files/leccion-02-primer-html → /completed-examples/leccion-02-primer-html

## Introducción 

En esta lección aprenderemos qué es una etiqueta, cómo se abre y se cierra, cuáles son las etiquetas que forman el esqueleto de toda página, y cómo escribir títulos con los encabezados. Al final, practicarás creando tu primera página.

## ¿Qué es HTML y qué es una etiqueta?

Con HTML le dices al navegador qué es cada cosa de tu página. Esto es un título, esto es un texto.

Para eso usamos etiquetas. Una etiqueta es una palabra escrita entre los símbolos menor que y mayor que.

## Etiqueta DOCTYPE

```html
<!DOCTYPE html>
```

Toda página HTML empieza con una línea especial: doctype html. Esta línea le avisa al navegador que el documento es una página HTML moderna. Siempre va en la primera línea y no necesita cierre.

## Etiquetas html, head, title y body

Después viene la etiqueta html, que envuelve toda la página. Dentro tiene dos partes

La primera es head, que significa cabeza. Aquí van datos de la página que no se ven en pantalla. Por ejemplo, la etiqueta title, que guarda el nombre que aparece en la pestaña del navegador.

La segunda es body, que significa cuerpo. Aquí va todo lo que sí se ve: títulos, textos e imágenes. Si quieres que algo aparezca en la página, va dentro de body.

## Encabezados h1 a h6 y párrafo p

Dentro de body, lo primero que usarás son los encabezados, que sirven para escribir títulos. Hay seis niveles: h1, h2, h3, h4, h5 y h6.

El h1 es el título principal de la página, el más importante. El h2 es para subtítulos y así hasta el h6.

Y para escribir texto normal, debajo de un título, usamos la etiqueta p, de párrafo.

# Estructura completa de un documento HTML

```html
<!DOCTYPE html>
<html>
<head>
    <title>Mi Primera Página</title>
</head>
<body>

    <h1>¡Hola, Mundo!</h1>
    <p>Esta es mi primera página web.</p>

</body>
</html>
```

## Actividad práctica

¡Ahora te toca a ti! Abre el enlace de CodePen que está en la descripción del video. CodePen ya trae la estructura completa de la página, así que tú no tienes que escribirla.

En el panel HTML encontrarás comentarios que te dicen qué hacer. 

- Uno: agrega un h1 con el título de tu página. 
- Dos: agrega un h2 que diga ‘Sobre mí’ y, debajo, un párrafo con la etiqueta p presentándote. 
- Tres: agrega otro h2 que diga ‘Mis pasatiempos’ y, debajo, su párrafo.
- Cuatro: agrega un último h2 que diga ‘Lo que estoy aprendiendo’ y su párrafo.

Pausa el video y hazlo con calma. Luego puedes comparar tu resultado con el ejemplo terminado.

## Buenas prácticas

Antes de terminar, tres consejos para escribir buen HTML.

- Uno: siempre cierra tus etiquetas. Si olvidas un cierre, la página puede verse mal.

- Dos: usa un solo h1 por página, porque es el título principal.

- Tres: respeta el orden de los encabezados. Después de un h1 va un h2, no un h5. Y no uses un encabezado solo para que el texto se vea grande: los encabezados sirven para organizar.

## Conclusión

¡Muy bien! Hoy aprendiste la estructura basica del HTML. En la siguiente lección aprenderás a dar formato al texto con nuevas etiquetas. ¡Nos vemos!
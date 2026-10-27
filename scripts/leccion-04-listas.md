# Guion – Lección 4: Creación de listas

**Duración estimada:** 5–6 min
**Editor:** CodePen (https://codepen.io/pen/)
**Archivos:** `/starter-files/leccion-04-listas` → `/completed-examples/leccion-04-listas`

---

## 1. Introducción (0:00 – 0:40)

**Narración:**
"¡Hola de nuevo! Una lista de compras, los pasos de un juego, una receta de cocina: ¡todo eso son listas! En HTML también podemos crearlas. Hoy Lucía quiere publicar su receta favorita de chocolate caliente, y para eso necesita dos tipos de listas. ¡Vamos a ayudarla!"

**Texto en pantalla:** Lección 4 – Creación de listas · 🍫 Receta de chocolate caliente
**Visual:** Mostrar el resultado final: ingredientes con viñetas y pasos con números.

## 2. Dos tipos de listas (0:40 – 1:40)

**Narración:**
"En HTML hay dos tipos de listas. La lista con viñetas se usa cuando el orden no importa, como en los ingredientes: da igual si escribes primero la leche o el chocolate. Su etiqueta es `ul`, de 'unordered list', que significa lista sin orden."

"La lista numerada se usa cuando el orden sí importa, como en los pasos de una receta. Su etiqueta es `ol`, de 'ordered list', que significa lista ordenada."

"Y en las dos, cada elemento va dentro de una etiqueta `li`, de 'list item', que significa elemento de la lista."

**Texto en pantalla:**
`ul` → viñetas (el orden NO importa)
`ol` → números (el orden SÍ importa)
`li` → cada elemento de la lista
**Visual:** Diapositiva con dos columnas: ingredientes (con viñetas) y pasos (con números), mostrando la etiqueta de cada una.

## 3. Preparar CodePen (1:40 – 2:10)

**Narración:**
"Abre CodePen; no necesitas instalar nada. Copia el código del archivo `index.html` de la carpeta starter-files, solo lo que está entre `<body>` y `</body>`, y pégalo en el panel HTML. Esta lección tampoco usa CSS."

**Texto en pantalla:** Panel HTML ← lo que está dentro de `<body>`
**Visual:** Abrir CodePen, pegar el código y mostrar la vista previa: los títulos y el párrafo, sin listas todavía.

## 4. Lista con viñetas: paso 1 (2:10 – 3:10)

**Narración:**
"Paso 1: los ingredientes. Debajo del título 'Ingredientes' abrimos una lista con `<ul>`. Dentro, cada ingrediente va en su propia etiqueta `li`: leche, chocolate, azúcar y canela. Al final cerramos con `</ul>`. Mira la vista previa: cada elemento tiene su viñeta."

"Un detalle importante: los `li` siempre van dentro de un `ul` o de un `ol`. Nunca solos."

"Pausa el video y haz el paso 1."

**Texto en pantalla:** `<ul>` + `<li>` = lista con viñetas
**Visual:** Escribir la lista línea por línea y hacer zoom a las viñetas en la vista previa.

## 5. Lista numerada: paso 2 (3:10 – 4:10)

**Narración:**
"Paso 2: la preparación. Aquí el orden sí importa, así que usamos `<ol>`. Dentro escribimos un `li` por cada paso: calienta la leche; agrega el chocolate y el azúcar; sirve en una taza; y disfrútalo con cuidado. Cerramos con `</ol>`. Fíjate: nosotros no escribimos los números. El navegador los pone solito."

"Pausa el video y haz el paso 2."

**Texto en pantalla:** `<ol>` + `<li>` = lista con números automáticos
**Visual:** Escribir la lista y señalar los números que aparecen solos en la vista previa.

## 6. Reto: ¡se olvidó un paso! (4:10 – 4:50)

**Narración:**
"Paso 3, el reto. ¡Lucía se olvidó de un paso! Antes de servir hay que apagar el fuego. Agrega un `li` nuevo entre el paso 2 y el paso 3, con el texto 'Apaga el fuego'. ¿Viste? No cambiamos ningún número, y el navegador los ordenó otra vez."

"Pausa el video y haz el reto."

**Texto en pantalla:** Agregas un `li` → los números se ajustan solos
**Visual:** Insertar el `li` en medio y marcar cómo 'Sirve en una taza' pasa del número 3 al 4.

## 7. Cierre (4:50 – 5:30)

**Narración:**
"¡Excelente! Hoy aprendiste a crear listas: `ul` para viñetas, `ol` para números y `li` para cada elemento. Recuerda: si el orden no importa, usa `ul`; si importa, usa `ol`. En la siguiente lección vamos a añadir imágenes a nuestra página."

**Texto en pantalla:**
`ul` sin orden · `ol` con orden · `li` cada elemento
➡️ Siguiente: Lección 5 – Añadiendo imágenes
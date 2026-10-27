# Guion – Lección 3: Dando formato al texto

**Duración estimada:** 5–6 min
**Editor:** CodePen (https://codepen.io/pen/)
**Archivos:** `/starter-files/leccion-03-formato-texto` → `/completed-examples/leccion-03-formato-texto`

---

## 1. Introducción (0:00 – 0:40)

**Narración:**
"¡Hola! ¿Alguna vez viste una palabra en negrita, en cursiva o resaltada en una página web? Todo eso se logra con etiquetas de HTML. Hoy vamos a ayudar a Lucía a darle formato al texto de su página personal: vamos a destacar lo importante, separar ideas y cortar líneas. Y al final hay una adivinanza para ti."

**Texto en pantalla:** Lección 3 – Dando formato al texto
**Visual:** Mostrar el resultado final y, al lado, la misma página sin formato (antes y después).

## 2. Preparar CodePen (0:40 – 1:20)

**Narración:**
"Abre CodePen; no necesitas instalar nada. Copia el código del archivo `index.html` de la carpeta starter-files, pero solo lo que está entre `<body>` y `</body>`. No copies esas dos etiquetas, porque CodePen ya las incluye. Pégalo en el panel HTML. Hoy no vamos a usar el panel CSS."

**Texto en pantalla:** Panel HTML ← lo que está dentro de `<body>` · Hoy no usamos CSS
**Visual:** Abrir CodePen, pegar el código y mostrar la vista previa sin formato.

## 3. Negrita, cursiva y resaltado: pasos 1 a 3 (1:20 – 3:10)

**Narración:**
"Paso 1. Queremos que 'Lima, Perú' se vea importante. Usamos la etiqueta `strong`: abrimos con `<strong>`, escribimos el texto y cerramos con `</strong>`. ¡Listo! Ahora está en negrita."

"Paso 2. Para darle énfasis a la palabra 'dibujar' usamos la etiqueta `em`. Abrimos con `<em>` y cerramos con `</em>`. El texto se pone en cursiva."

"Paso 3. Para resaltar 'HTML y CSS' usamos `mark`, como si pasáramos un marcador amarillo por encima."

"Las tres etiquetas funcionan igual: una de apertura, el texto y una de cierre con barra. Quizás veas por ahí las etiquetas `b` e `i`. Se ven igual, pero nosotros usamos `strong` y `em` porque le dicen al navegador que esas palabras realmente son importantes."

"Pausa el video y haz los pasos 1, 2 y 3 en tu CodePen. Cuando termines, seguimos."

**Texto en pantalla:**
`<strong>` → negrita
`<em>` → cursiva
`<mark>` → resaltado
**Visual:** Escribir cada paso y marcar con un círculo el cambio en la vista previa.

## 4. Líneas y saltos de línea: pasos 4 y 5 (3:10 – 4:25)

**Narración:**
"Paso 4. Ahora queremos separar la presentación de Lucía de su adivinanza. Para eso usamos `hr`, que dibuja una línea horizontal. Esta etiqueta es especial: no se cierra, porque no envuelve ningún texto."

"Paso 5. Mira la adivinanza. En el código está escrita en cuatro líneas, pero en la página aparece toda junta. ¡HTML ignora cuando presionamos Enter! Para cortar una línea usamos `br`. Escribimos `<br>` al final de los tres primeros versos, y ahora cada verso aparece en su propia línea. Un consejo: `br` sirve para versos y poemas. Para separar párrafos usamos `p`."

"Pausa el video y haz los pasos 4 y 5."

**Texto en pantalla:** `<hr>` y `<br>` no se cierran · Enter en el código ≠ línea nueva en la página
**Visual:** Mostrar la adivinanza en una sola línea; luego agregar los `<br>` y mostrar cómo cada verso baja a su propia línea.

## 5. Combinar etiquetas: paso 6 (4:25 – 5:05)

**Narración:**
"Paso 6. ¡También podemos combinar etiquetas! Queremos que '¿Ya la adivinaste?' salga en negrita y en cursiva a la vez. Abrimos `strong`, luego `em`, escribimos el texto y cerramos en orden inverso: primero `em` y después `strong`. Es como con las medias y los zapatos: te los pones en un orden y te los quitas en el orden contrario."

"Pausa el video, haz el paso 6 e intenta adivinar la adivinanza. ¡La respuesta está en el cierre!"

**Texto en pantalla:** `<strong><em>texto</em></strong>` → se cierra en orden inverso
**Visual:** Animación con cajas: `strong` envuelve a `em`, que envuelve al texto.

## 6. Cierre (5:05 – 5:40)

**Narración:**
"¡Muy bien! Hoy aprendiste cinco etiquetas: `strong`, `em`, `mark`, `hr` y `br`. ¿Ya sabes la respuesta de la adivinanza? ¡Es la pera! Y un último consejo: cuando crees tu propia página, no escribas tu dirección ni tu teléfono. En la siguiente lección aprenderemos a crear listas."

**Texto en pantalla:**
`<strong>` negrita · `<em>` cursiva · `<mark>` resaltado · `<hr>` línea · `<br>` salto de línea
🍐 Respuesta: la pera
➡️ Siguiente: Lección 4 – Creación de listas
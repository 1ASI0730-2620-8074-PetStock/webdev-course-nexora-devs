# Guion – Lección 10: Errores comunes y próximos pasos

**Duración estimada:** 6–7 min
**Editor:** CodePen (https://codepen.io/pen/)
**Archivos:** `/starter-files/leccion-10-errores-comunes` → `/completed-examples/leccion-10-errores-comunes`

---

## 1. Introducción (0:00 – 0:40)

**Narración:**
"¡Hola de nuevo! Hasta los programadores con experiencia se equivocan. Lo importante es saber encontrar los errores. En esta lección tenemos la misma página de perfil de la lección anterior, pero con 6 errores escondidos: 3 en el HTML y 3 en el CSS. ¡Vamos a cazarlos!"

**Texto en pantalla:** Lección 10 – ¡Caza de errores! 🔍 (6 errores)
**Visual:** Mostrar la página rota junto a la página correcta.

## 2. Preparar CodePen (0:40 – 1:10)

**Narración:**
"Copia el `index.html` y el `style.css` de la carpeta starter-files de esta lección en CodePen. Busca los comentarios con `¿?`: son tus pistas."

**Visual:** Pegar el código y mostrar la vista previa con errores.

## 3. Errores en HTML (1:10 – 3:00)

**Error 1: atributo mal escrito**
"La imagen no aparece. Si miramos bien, dice `scr` en vez de `src`. El navegador no conoce `scr`, así que lo ignora. Lo corregimos y la foto aparece."
**Texto en pantalla:** ❌ `scr` → ✅ `src`

**Error 2: etiqueta sin cerrar**
"Todo el texto se ve gigante. El `h1` no se cerró: dice `<h1>` en lugar de `</h1>`. Sin la barra, el navegador cree que todo lo que sigue es parte del título."
**Texto en pantalla:** ❌ `<h1>` → ✅ `</h1>`

**Error 3: enlace sin https://**
"El botón no lleva a MDN. Si a un enlace a otro sitio le falta `https://`, el navegador lo busca dentro de nuestra propia página."
**Texto en pantalla:** ❌ `developer.mozilla.org` → ✅ `https://developer.mozilla.org`

## 4. Errores en CSS (3:00 – 5:00)

**Error 4: propiedad mal escrita**
"La tarjeta no se ve blanca. Escribimos `background-colour` con 'u'. CSS usa el inglés de Estados Unidos: `color`, sin 'u'."
**Texto en pantalla:** ❌ `colour` → ✅ `color`

**Error 5: falta el punto de la clase**
"La foto no sale redonda. El selector dice `foto`, sin el punto. Sin punto, CSS busca una etiqueta llamada `<foto>`, que no existe. Para las clases siempre va el punto: `.foto`."
**Texto en pantalla:** ❌ `foto` → ✅ `.foto`

**Error 6: falta el punto y coma**
"El título no cambia ni de color ni de tamaño. Después de `color: #1a73e8` falta el punto y coma, así que CSS junta esa línea con la siguiente y no entiende ninguna de las dos."
**Texto en pantalla:** ❌ `color: #1a73e8` → ✅ `color: #1a73e8;`

## 5. Consejos para encontrar errores (5:00 – 5:40)

**Narración:**
"Tres consejos: primero, revisa que cada etiqueta que abres también se cierre. Segundo, fíjate en los colores del editor: si algo se ve de un color raro, puede estar mal escrito. Tercero, haz un cambio a la vez y mira la vista previa."

**Texto en pantalla:**
✔ Abre y cierra etiquetas
✔ Revisa los colores del editor
✔ Un cambio a la vez

## 6. Próximos pasos y cierre (5:40 – 6:40)

**Narración:**
"¡Felicitaciones, terminaste el curso! Ya sabes crear una página web con HTML y CSS. Si quieres seguir aprendiendo, tienes recursos gratuitos en español: MDN Web Docs para consultar cualquier etiqueta, y freeCodeCamp para practicar con retos. El siguiente paso es JavaScript, que le da interactividad a tus páginas. ¡Sigue practicando y crea muchas páginas!"

**Texto en pantalla:**
📘 MDN Web Docs: developer.mozilla.org/es
💻 freeCodeCamp: freecodecamp.org/espanol
➡️ Siguiente paso: JavaScript
🎉 ¡Gracias por aprender con nosotros!

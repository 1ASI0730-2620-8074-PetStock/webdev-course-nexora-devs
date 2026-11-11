# Guion – Lección 10: Errores comunes y próximos pasos

**Duración estimada:** 6–7 min
**Editor:** CodePen (https://codepen.io/pen/)
**Archivos:** `/starter-files/leccion-10-errores-comunes` → `/completed-examples/leccion-10-errores-comunes`

---

## 1. Introducción

**Narración:**
"¡Hola de nuevo! Hasta los programadores con experiencia se equivocan. Lo importante es saber encontrar los errores. En esta lección tenemos la misma página de perfil de la lección anterior, pero con 6 errores escondidos: 3 en el HTML y 3 en el CSS. ¡Vamos a cazarlos!"

**Texto en pantalla:** Lección 10 – ¡Caza de errores! 🔍 (6 errores)
**Visual:** Mostrar la página rota junto a la página correcta.

## 2. Consejos para encontrar errores 

**Narración:**
"Tres consejos: primero, revisa que cada etiqueta que abres también se cierre. Segundo, fíjate en los colores del editor: si algo se ve de un color raro, puede estar mal escrito. Tercero, haz un cambio a la vez y mira la vista previa."

**Texto en pantalla:**
✔ Abre y cierra etiquetas
✔ Revisa los colores del editor
✔ Un cambio a la vez

## 3. Preparar CodePen

**Narración:**
"Abre CodePen. Copia lo que está entre `<body>` y `</body>` del `index.html` de la carpeta starter-files y pégalo en el panel HTML. Luego copia todo `style.css` en el panel CSS. Pausa el video e intenta encontrar los errores tú solo."

**Visual:** Pegar el código y mostrar la vista previa con errores.

## 3. Consejos para encontrar errores 

**Narración:**
"Tres consejos: primero, revisa que cada etiqueta que abres también se cierre. Segundo, fíjate en los colores del editor: si algo se ve de un color raro, puede estar mal escrito. Tercero, haz un cambio a la vez y mira la vista previa."

**Texto en pantalla:**
✔ Abre y cierra etiquetas
✔ Revisa los colores del editor
✔ Un cambio a la vez

## 4. Errores en HTML

**Error 1: atributo mal escrito**
"La imagen no aparece. Si miramos bien, dice `scr` en vez de `src`. El navegador no conoce `scr`, así que lo ignora. Lo corregimos y la foto aparece."
**Texto en pantalla:** ❌ `scr` → ✅ `src`

**Error 2: etiqueta sin cerrar**
"Todo el texto se ve gigante. El `h1` no se cerró: dice `<h1>` en lugar de `</h1>`. Sin la barra, el navegador cree que todo lo que sigue es parte del título."
**Texto en pantalla:** ❌ `<h1>` → ✅ `</h1>`

**Error 3: enlace sin https://**
"El botón no lleva a MDN. Si a un enlace a otro sitio le falta `https://`, el navegador lo busca dentro de nuestra propia página."
**Texto en pantalla:** ❌ `developer.mozilla.org` → ✅ `https://developer.mozilla.org`

## 5. Errores en CSS 
**Error 4: propiedad mal escrita**
"La tarjeta no se ve blanca. Escribimos `background-colour` con 'u'. CSS usa el inglés de Estados Unidos: `color`, sin 'u'."
**Texto en pantalla:** ❌ `colour` → ✅ `color`

**Error 5: falta el punto de la clase**
"La foto no sale redonda. El selector dice `foto`, sin el punto. Sin punto, CSS busca una etiqueta llamada `<foto>`, que no existe. Para las clases siempre va el punto: `.foto`."
**Texto en pantalla:** ❌ `foto` → ✅ `.foto`

**Error 6: falta el punto y coma**
"El título no cambia ni de color ni de tamaño. Después de `color: #1a73e8` falta el punto y coma, así que CSS junta esa línea con la siguiente y no entiende ninguna de las dos."
**Texto en pantalla:** ❌ `color: #1a73e8` → ✅ `color: #1a73e8;`



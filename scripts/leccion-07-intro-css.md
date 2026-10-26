
# Lección 07: Introducción a CSS

## Duración
6 minutos aproximadamente.

## Objetivo
Aprender qué es CSS y cómo utilizarlo para cambiar
la apariencia de una página HTML.

## 1. Introducción (1 minuto)

En esta lección aprenderemos a utilizar CSS.

CSS significa Cascading Style Sheets, que en español
se conoce como Hojas de Estilo en Cascada.

HTML nos permite crear el contenido de una página,
mientras que CSS permite modificar su apariencia.

Por ejemplo, podemos cambiar los colores del texto,
el fondo de la página y los tipos de letra.

## 2. Conectar HTML con CSS (1 minuto)

Para utilizar un archivo CSS debemos conectarlo
con nuestro documento HTML.

Dentro de la etiqueta head escribimos:

    <link rel="stylesheet" href="style.css">

De esta manera, nuestro HTML utilizará los estilos
definidos en el archivo style.css.

## 3. Selectores y propiedades (2 minutos)

Una regla CSS tiene un selector y varias propiedades.

Ejemplo:

    h1 {
        color: darkblue;
    }

El selector h1 indica que aplicaremos el estilo
a los títulos principales.

La propiedad color permite cambiar el color
del texto.

También podemos cambiar el fondo:

    body {
        background-color: lightblue;
    }

## 4. Actividad práctica (1 minuto)

Abrimos CodePen y utilizamos nuestro código HTML.

En la sección CSS escribimos los estilos
para cambiar:

- El color del fondo.
- El color del título principal.
- El color de los subtítulos.
- El color de los párrafos.

Observamos cómo los cambios aparecen en la página.

## 5. Conclusión (1 minuto)

Hoy aprendimos qué es CSS y cómo utilizar
selectores y propiedades.

En la siguiente lección continuaremos mejorando
nuestra página con fuentes, tamaños y alineaciones.

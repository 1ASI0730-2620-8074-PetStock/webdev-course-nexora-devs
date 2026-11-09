# **Lección 06: Cómo crear enlaces en HTML**

## **INICIO**

Hola a todos. Bienvenidos a la **Lección 6: Cómo crear enlaces en HTML**.

En la lección anterior aprendimos a insertar imágenes. Ahora aprenderemos a crear **enlaces**, también conocidos como *links*.

Los enlaces permiten visitar otras páginas, consultar información y conectar diferentes recursos.

Para nuestro ejemplo vamos a crear una página llamada **“Mis recursos favoritos”**.

---

## **¿Qué es un enlace?**

Un enlace permite al usuario acceder a otra página o recurso.

Para crear un enlace utilizamos:

```html
<a>
```

La letra `a` viene de *anchor*, que significa **ancla**.

Para indicarle al navegador hacia dónde debe dirigirnos utilizamos el atributo `href`.

---

## **¿Qué es el atributo href?**

`href` indica la dirección de destino.

La estructura básica es:

```html
<a href="URL">Texto del enlace</a>
```

Por ejemplo:

```html
<a href="https://developer.mozilla.org/">Aprender HTML</a>
```

Aquí:

- `<a>` crea el enlace.
- `href` contiene la dirección.
- El texto es lo que el usuario verá y podrá seleccionar.

---

## **Crear nuestro primer enlace**

Comenzamos con:

```html
<h1>Mis recursos favoritos</h1>

<p>Los enlaces permiten visitar otras páginas web.</p>
```

Ahora agregamos nuestro primer recurso:

```html
<a href="https://developer.mozilla.org/es/docs/Learn_web_development">
    Guía de desarrollo web de MDN
</a>
```

Cuando el usuario haga clic sobre el texto, el navegador intentará abrir la dirección indicada en `href`.

---

## **¿Cómo crear varios enlaces?**

Podemos crear tantos enlaces como necesitemos.

```html
<a href="https://developer.mozilla.org/es/docs/Learn_web_development">
    Guía de desarrollo web de MDN
</a>

<a href="https://www.w3schools.com/html/">
    Tutorial de HTML
</a>
```

Cuando tenemos varios recursos, podemos organizarlos utilizando una lista.

---

## **Enlaces dentro de una lista**

Para crear una lista utilizamos `ul` y `li`.

```html
<ul>
    <li>Elemento de la lista</li>
</ul>
```

Ahora colocamos los enlaces dentro:

```html
<ul>
    <li>
        <a href="https://developer.mozilla.org/es/docs/Learn_web_development">
            Guía de desarrollo web de MDN
        </a>
    </li>

    <li>
        <a href="https://www.w3schools.com/html/">
            Tutorial de HTML
        </a>
    </li>
</ul>
```

Así tenemos una lista donde cada elemento contiene un enlace.

---

## **Ejemplo: Mis recursos favoritos**

Ahora aplicamos todo lo aprendido.

Primero:

```html
<h1>Mis recursos favoritos</h1>

<p>Los enlaces permiten visitar otras páginas web.</p>
```

Después:

```html
<h2>Aprender desarrollo web</h2>
```

Ahora agregamos nuestros dos recursos dentro de una lista:

```html
<ul>
    <li>
        <a href="https://developer.mozilla.org/es/docs/Learn_web_development">
            Guía de desarrollo web de MDN
        </a>
    </li>

    <li>
        <a href="https://www.w3schools.com/html/">
            Tutorial de HTML
        </a>
    </li>
</ul>
```

Finalmente agregamos CodePen:

```html
<p>
    <a href="https://codepen.io/">
        Practica código en CodePen
    </a>
</p>
```

Ahora tenemos una página con diferentes recursos que podemos visitar haciendo clic sobre cada enlace.

---

## **Ahora te toca a ti**

Ahora vamos a practicar.

Crea una página llamada **“Mis recursos favoritos”**.

Después:

1. Crea un subtítulo llamado **“Aprender desarrollo web”**.
2. Agrega dos enlaces relacionados con el desarrollo web.
3. Colócalos dentro de una lista utilizando `ul` y `li`.
4. Agrega un tercer enlace para practicar en CodePen.

Recuerda:

```html
<a href="URL">Texto del enlace</a>
```

Finalmente, haz clic en cada enlace y comprueba que las direcciones funcionan correctamente.

---

## **Puntos clave**

- **`<a>`** permite crear enlaces.
- **`href`** indica la dirección de destino.
- El texto dentro de `<a>` es lo que verá el usuario.
- Podemos crear múltiples enlaces.
- Los enlaces pueden combinarse con listas utilizando `ul` y `li`.
- Los enlaces permiten conectar nuestra página con otros recursos de la web.

---

## **CONCLUSIÓN**

Y con esto terminamos la **Lección 6**.

Ahora sabemos cómo crear enlaces y cómo utilizar `href` para conectar nuestra página con otros recursos.

También aprendimos a combinar enlaces con listas para organizar mejor la información.

En la siguiente lección comenzaremos a trabajar con **CSS**, lo que nos permitirá cambiar la apariencia y el diseño de nuestras páginas HTML.

¡Nos vemos en la próxima lección!

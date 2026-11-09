# **Lección 05: Cómo insertar imágenes en HTML**

## **INICIO**

Hola a todos. Bienvenidos a la **Lección 5: Cómo insertar imágenes en HTML**.

Hasta ahora hemos aprendido a utilizar diferentes etiquetas para construir el contenido de una página web.

En esta lección aprenderemos a incorporar **imágenes** utilizando HTML.

Las imágenes nos permiten mostrar fotografías, productos, logotipos, ilustraciones y muchos otros recursos visuales dentro de una página.

Para nuestro ejemplo vamos a crear una página sobre **nuestros animales favoritos**.

---

## **¿Cómo insertamos una imagen en HTML?**

Para insertar una imagen utilizamos la etiqueta:

```html
<img>
```

A diferencia de etiquetas como `h1` o `p`, `img` no necesita una etiqueta de cierre.

Pero necesitamos indicarle al navegador **qué imagen queremos mostrar**.

Para eso utilizamos el atributo `src`.

```html
<img src="imagen.jpg">
```

El atributo `src` viene de *source*, que significa **fuente**.

En otras palabras, `src` le indica al navegador **dónde puede encontrar la imagen** que queremos mostrar.

---

## **Imágenes almacenadas localmente**

Una forma de utilizar imágenes es guardarlas dentro de nuestro propio proyecto.

Por ejemplo:

```text
mi-proyecto/
│
├── index.html
├── gato.jpg
└── perro.jpg
```

Si `gato.jpg` está en la misma carpeta que nuestro archivo HTML, podemos escribir:

```html
<img src="gato.jpg">
```

También podemos organizar las imágenes dentro de una carpeta:

```text
mi-proyecto/
│
├── index.html
│
└── imagenes/
    └── gato.jpg
```

En ese caso:

```html
<img src="imagenes/gato.jpg">
```

La ruta escrita en `src` debe coincidir con la ubicación real de la imagen.

---

## **Imágenes desde Internet**

Otra opción es utilizar una imagen que se encuentre en Internet.

En lugar del nombre de un archivo, podemos colocar una dirección web en `src`.

Por ejemplo:

```html
<img src="https://images.unsplash.com/photo-1514888286974-6c03e2ca1dba?w=500">
```

En este caso, la imagen no está guardada dentro de nuestro proyecto. El navegador la obtiene desde un servidor externo.

Podemos tener entonces:

```html
<!-- Imagen local -->
<img src="gato.jpg">

<!-- Imagen desde Internet -->
<img src="https://images.unsplash.com/photo-1514888286974-6c03e2ca1dba?w=500">
```

La diferencia está en el origen de la imagen.

---

## **¿Qué es el atributo alt?**

Ahora agregaremos otro atributo importante: **`alt`**.

El atributo `alt` proporciona una descripción de la imagen.

```html
<img src="gato.jpg" alt="Gato mirando a la cámara">
```

El texto de `alt` describe lo que aparece en la imagen.

También resulta útil cuando la imagen no puede cargarse y para tecnologías de asistencia.

Por eso debemos utilizar una descripción clara y relacionada con la imagen.

---

## **¿Cómo cambiar el tamaño de una imagen?**

Podemos establecer el ancho utilizando `width`.

```html
<img 
    src="gato.jpg"
    alt="Gato mirando a la cámara"
    width="300"
>
```

El valor `300` indica un ancho de 300 píxeles.

Así podemos recordar:

- `src` → indica dónde está la imagen.
- `alt` → describe la imagen.
- `width` → establece su ancho.

---

## **Ejemplo: Mis animales favoritos**

Ahora vamos a aplicar todo lo aprendido.

Primero escribimos:

```html
<h1>Mis animales favoritos</h1>

<p>Estas son algunas imágenes de animales que me gustan.</p>
```

Después agregamos el primer animal:

```html
<h2>Gato</h2>

<img 
    src="https://images.unsplash.com/photo-1514888286974-6c03e2ca1dba?w=500"
    alt="Gato mirando a la cámara"
    width="300"
>

<p>Los gatos son curiosos y ágiles.</p>
```

Y repetimos el proceso con un perro:

```html
<h2>Perro</h2>

<img 
    src="https://images.unsplash.com/photo-1552053831-71594a27632d?w=500"
    alt="Perro sentado sobre el césped"
    width="300"
>

<p>Los perros pueden ser grandes compañeros.</p>
```

De esta manera conseguimos una página que combina títulos, imágenes y texto.

---

## **Ahora te toca a ti**

Ahora vamos a practicar.

Crea una página llamada **“Mis animales favoritos”**.

Agrega un animal utilizando un título `h2`, una imagen y una descripción.

Puedes utilizar una imagen local o una imagen disponible en Internet.

Recuerda utilizar:

```html
<img 
    src="URL_DE_LA_IMAGEN"
    alt="Descripción del animal"
    width="300"
>
```

Después agrega un segundo animal y una segunda imagen.

Comprueba que las imágenes aparecen correctamente.

Si una imagen no aparece, revisa principalmente el valor de `src` y verifica que la ruta o dirección sea correcta.

---

## **Puntos clave**

- **`<img>`** permite insertar imágenes en HTML.
- **`src`** indica dónde se encuentra la imagen.
- Podemos utilizar imágenes **locales** o **alojadas en Internet**.
- En una imagen local, la ruta debe coincidir con la ubicación del archivo.
- En una imagen de Internet, debemos utilizar una dirección válida.
- **`alt`** proporciona una descripción.
- **`width`** permite establecer el ancho.

---

## **CONCLUSIÓN**

Y con esto terminamos la **Lección 5**.

Ahora sabemos cómo insertar imágenes y cómo obtenerlas desde nuestros propios archivos o desde Internet.

También aprendimos a utilizar `src`, `alt` y `width`.

En la siguiente lección aprenderemos a crear **enlaces**, que nos permitirán conectar nuestra página con otros sitios y recursos de la web.

¡Nos vemos en la próxima lección!

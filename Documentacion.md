# Creación de mi Currículum Web

## Lo básico

- **HTML:** son las siglas de HyperText Markup Language (Lenguaje de Marcado de Hipertexto). No es para programar: sirve para decirle al navegador qué es cada cosa de mi página, por ejemplo «esto es un título» o «esto es una imagen».
- **Etiqueta:** es una palabra entre `< >`. Es como una caja: casi siempre la abro, meto algo adentro y la cierro. La de cerrar lleva una diagonal. Por ejemplo, `<p>` abre y `</p>` cierra.
- **Etiqueta que no se cierra:** algunas no llevan nada adentro, entonces no se cierran. Por ejemplo `img`, `meta` y `link`.
- **Atributo:** es información extra que le pongo a una etiqueta, como una nota pegada en la caja. Siempre va dentro de la etiqueta que abre y se escribe así: `nombre="valor"`. Si pongo varios, los separo con un espacio, nunca con coma.
- **Comentario:** `<!-- nota -->` es una nota para mí. El navegador no la muestra.
- **Sangría:** son los espacios al inicio de cada línea. No cambian nada en la página, pero me ayudan a ver qué está dentro de qué.

## Etiquetas de la parte de arriba (lo que no se ve)

- **`<!DOCTYPE html>`:** le avisa al navegador que mi archivo es HTML. Siempre va en la primera línea. No se cierra.
- **`html`:** la caja más grande; ahí va toda mi página. Se cierra.
- **`head`:** la "cabeza" de mi página: información que no se ve, como el título de la pestaña o el idioma. Se cierra.
- **`meta`:** datos técnicos de la página. No se cierra.
- **`title`:** el texto que sale en la pestaña del navegador. Se cierra.
- **`link`:** conecta mi página con otro archivo, como el de diseño (CSS). No se cierra.

## Etiquetas de lo que sí se ve

- **`body`:** el "cuerpo": todo lo que se ve en la página. Se cierra.
- **`header`:** el encabezado, la parte de arriba donde me presento. Se cierra.
- **`img`:** muestra una imagen, como mi foto. No se cierra.
- **`main`:** la caja del contenido principal. Solo hay una. Se cierra.
- **`aside`:** una caja para cosas que acompañan a lo principal. Es mi columna izquierda. Se cierra.
- **`div`:** una caja que no significa nada especial, solo sirve para agrupar. Es mi columna derecha. Se cierra.
- **`section`:** junta cosas del mismo tema, como «Contacto» o «Habilidades». Se cierra.
- **`p`:** un párrafo, o sea, texto normal. Se cierra.
- **`a`:** un enlace, algo a lo que le das clic y te lleva a otro lado. Se cierra.
- **`ul`:** una lista con puntitos (viñetas), donde el orden no importa. Se cierra.
- **`li`:** cada renglón de la lista. Siempre va dentro de un `ul`. Se cierra.

## Los títulos funcionan como un libro

- **`h1`:** el título del libro. En mi CV es mi nombre. Solo debe haber uno.
- **`h2`:** los capítulos, como «Contacto», «Habilidades» y «Educación».
- **`h3`:** los temas dentro de un capítulo, como el nombre de mi carrera dentro de «Educación».
- No me debo saltar niveles: no pongo un `h3` si antes no hay un `h2`.

## Atributos que he usado

- **`lang`** (en `html`): el idioma de la página. `es` es español.
- **`charset`** (en `meta`): con `UTF-8` se ven bien los acentos y la ñ. Sin esto, "Saúl" podría salir raro.
- **`name="viewport"` y `content`** (en `meta`): hacen que la página se vea bien en el celular y no salga diminuta.
- **`rel`** (en `link`): dice qué tipo de archivo conecto. `stylesheet` significa "hoja de estilos" (diseño).
- **`href`** (en `link` y en `a`): la dirección a donde apunta. En `link` es mi archivo de diseño; en `a` es a donde lleva el enlace.
- **`src`** (en `img`): dónde está guardada la imagen.
- **`alt`** (en `img`): un texto que describe la imagen. Lo usan las personas ciegas con programas que leen la pantalla, y también sale si la imagen no carga.
- **`target="_blank"`** (en `a`): hace que el enlace se abra en una pestaña nueva.

## Cómo funcionan los enlaces

Un enlace es como un letrero con dos lados:

- **Atrás (no se ve):** la dirección, que va en `href`.
- **Al frente (sí se ve):** el texto, que va entre la etiqueta que abre y la que cierra.

Direcciones especiales para `href`:

- **`tel:`** + mi número sin espacios: en el celular abre la llamada.
- **`mailto:`** + mi correo: abre la app de correo con mi dirección ya escrita.
- **`https://`** + la página: abre un sitio de internet, como mi LinkedIn.

En la computadora, `tel:` y `mailto:` pueden no hacer nada si no tengo una app de llamadas o de correo. En el celular sí funcionan.

## Bitácora

### Día 1
- Hice el esqueleto de la página: el idioma, el título de la pestaña y la conexión con el archivo de diseño.

### Día 2
- Hice el encabezado con mi foto, mi nombre y mi carrera.
- La foto sale enorme; se arregla con CSS más adelante.

### Día 3
- Separé la página en dos columnas: `aside` a la izquierda y `div` a la derecha.
- Hice la sección de Contacto con enlaces a mi teléfono, mi correo y mi LinkedIn.
- Me equivoqué al no cerrar los `a` y al poner la dirección como texto, y ya lo corregí.

### Día 4
- Hice las secciones de Habilidades, Educación y En aprendizaje.
- Aprendí las listas (`ul` y `li`) y los niveles de títulos (`h1`, `h2`, `h3`).
- Ya terminé la columna izquierda.
# Creación del Currículum Web

Proyecto para aprender HTML y CSS haciendo mi CV como página web.

## Conceptos básicos

- **HTML:** HyperText Markup Language (Lenguaje de Marcado de Hipertexto). No es un lenguaje de programación: sirve para decirle al navegador qué es cada parte de la página.
- **Etiqueta:** una palabra entre `< >` que dice qué es cada cosa. Funciona como una caja: casi todas se abren `<p>` y se cierran `</p>`, y el contenido va en medio.
- **Etiqueta vacía:** no se cierra porque no lleva nada adentro. Ejemplos: `meta`, `link`, `img`.
- **Atributo:** un dato extra de una etiqueta. Va dentro de la etiqueta que abre, con la forma `nombre="valor"`. Si hay varios, se separan con un espacio, sin coma.
- **Comentario:** `<!-- nota -->` es una nota para mí. El navegador la ignora y no aparece en la página.
- **Sangría:** los espacios al inicio de la línea. No cambian nada para el navegador, pero me ayudan a ver qué está dentro de qué.

## Etiquetas que he usado

- **`!DOCTYPE html`:** aviso de que el archivo es HTML moderno. Siempre va en la primera línea. No se cierra.
- **`html`:** la caja que contiene toda la página. Se cierra.
- **`head`:** información sobre la página que no se ve (título, idioma, estilos). Se cierra.
- **`meta`:** datos técnicos de la página (metadatos). No se cierra.
- **`title`:** texto de la pestaña del navegador. Se cierra.
- **`link`:** conecta un archivo externo, como el CSS. No se cierra.
- **`body`:** todo lo que sí se ve en la página. Se cierra.
- **`header`:** encabezado, la parte de presentación de la página. Se cierra.
- **`img`:** muestra una imagen. No se cierra.
- **`h1`:** el título más importante. Solo debe haber uno en la página. Se cierra.
- **`p`:** párrafo, un bloque de texto normal. Se cierra.

## Atributos que he usado

- **`lang`** (en `html`): idioma de la página. `es` = español.
- **`charset`** (en `meta`): juego de caracteres. `UTF-8` permite acentos, ñ y emojis.
- **`name="viewport"` y `content`** (en `meta`): que la página use el ancho real de la pantalla y empiece sin zoom. Es importante en el celular.
- **`rel`** (en `link`): qué tipo de archivo conecto. `stylesheet` = hoja de estilos.
- **`href`** (en `link`): ruta del archivo que conecto.
- **`src`** (en `img`): ruta donde está guardada la imagen.
- **`alt`** (en `img`): texto que describe la imagen. Lo leen los lectores de pantalla y aparece si la imagen no carga.

## Bitácora

### Día 1
- Hice el esqueleto de la página: idioma, título de la pestaña y conexión con el CSS.

### Día 2
- Hice el encabezado con mi foto, mi nombre y mi carrera.
- La foto sale enorme; se arregla con CSS en la Etapa 2.
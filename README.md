# Escuela de Desarrollo Web by Platzi - Job Listings Challenge

![Design preview for the Job Listings coding challenge](./design/desktop-preview.jpg)

## Bienvenida/o 👋

Los retos que encontarás semana a semana permiten mejorar tus habilidades en un flujo de trabajo de la vida real.

Estás lista/o?

**Para realizar este reto, necesita un conocimiento básico de HTML, CSS y un poco de JavaScript, recomendamos el Curso Definitivo de HTML y CSS**

## El reto

Tu reto es construir esta página inicial de una e-commerce y lograr que se parezca lo más posible al diseño.

Los usuarios deberían poder:

- Ver el diseño óptimo para el sitio según el tamaño de pantalla de su dispositivo (Mobile First es requerido)
- Ver el efecto hover para todos los elementos interactivos de la página
- Filtrar la lista de trabajos basado en las categorias.

### Filtos

#### Opción 1

Filtrar listados de trabajo según las categorías usando el HTML `data-` attribute. En esta opción, usaría el contenido codificado que ya existe en el archivo [index.html](./index.html).

Las categorías son:

- Rol: Frontend, Backend, Fullstack
- Nivel: Junior, Midweight, Senior
- Idiomas: Python, Ruby, JavaScript, HTML, CSS
- Skills: React, Sass, Vue, Django, RoR (Ruby on Rails)

Entonces, si una lista de trabajo tiene las siguientes categorías `Frontend, Junior, JavaScript, React` tu HTML `data attributes` se vería así `data-role="frontend" data-level="junior" data-languages="javascript" data-tools="react"`.

#### Opción 2

Usa el archivo de [data.json](./data.json) para extraer los datos y luego agregar dinámicamente el contenido. Esto sería perfecto si está buscando practicar una library/framework de JS como React, Vue, o Svelte.

Para agregar un filtro, el usuario debe hacer clic en las tabletas en el lado derecho de la lista en el escritorio o en la parte inferior en el móvil. Para cada filtro agregado, solo se deben devolver los listados que contengan todos los filtros seleccionados.

## ¿Donde encontrar todo?

Tu tarea es realizar el reto con los diseños dentro de la carpeta `/design`. Ahí encontrará una versión móvil y de escritorio del diseño a trabajar.

Los diseños están en formato estático JPG. Esto significa que deberá utilizar su mejor criterio para estilos como `font-size`, `padding` y `margin`. Esto debería ayudar a entrenar su ojo para percibir las diferencias en los espacios y tamaños.

Encontrará todos los assets necesarios en la carpeta de `/images`. Los assets ya están optimiza.

También hay un archivo de `style-guide.md`, que contiene la información necesaria, como la paleta de colores y fuentes.

## Construyendo tu proyecto

No dudes en utilizar cualquier flujo de trabajo con el que te sienta más cómoda/o. A continuación te muestro el proceso sugerido, pero toma esto como sugerencia y no regla:

1. Clona éste repo en un repo público desde tu [GitHub](https://github.com/). Esto hará que sea más fácil compartir tu código con la comunidad si necesita ayuda. Si no está seguro de cómo hacer esto,, [Lee este recurso - Prueba Git](https://try.github.io/).
2. Puedes configurar tu repositorio para utilizar GitHub Pages. Esto también será útil si necesita ayuda durante el reto, ya que puede compartir la URL de tu proyecto con la URL de tu repositorio. Hay varias formas de hacer esto, pero recomendamos usar [GitHub Pages](https://pages.github.com/).
3. Mira los diseños para comenzar a planificar cómo abordará el proyecto. Este paso es crucial para ayudarte a pensar en las clases de CSS que podría crear para hacer estilos reutilizables.
4. Antes de agregar cualquier estilo, estructura tu contenido con HTML. Crear la arquitectura de tu HTML primero puede ayudarte a centrar tu atención en la estructura de tu contenido.
5. Escriba los estilos base para tu proyecto, incluidos los estilos de contenido general, como `font-family` y `font-size`.

## Compartenos tu resultado

1. Asegurate de tener tu reto terminado en GitHub y GitHub Pages.
2. Deja el enlace a tu repo en este hilo.
3. Compartenos en el grupo de Telegram de Escuela de Desarrollo Web el número del reto junto con la URL de tu reto del foro.
4. Lanza un tweet a [Platzi](https://twitter.com/platzi) y [@degranda10](https://twitter.com/degranda10) con el hashtag #PlatziWebChallange mencionandonos la URL de tu hilo para que nosotros y toda la comunidad de Platzi podamos verlo y celebrar contigo.

**Diviértete y disfruta creando éste reto!** 🚀

## Créditos por el diseño y reto.

Este reto pertenece a la lista de retos de [Frontend Mentor](https://www.frontendmentor.io/dashboard)

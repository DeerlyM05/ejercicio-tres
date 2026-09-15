# Layout Ejercicio Tres - Tema Estudio de Arquitectura

La estructura de la página ocupa el **100% de ancho** y **100vh de alto**. Ahora está maquetada **exclusivamente usando Flexbox y Box Model**.

## Medidas y Proporciones:

- **Contenedor Principal (body):**
  - Ancho: `100%`
  - Alto: `100vh`
  - Comportamiento: `display: flex; flex-direction: row;` (divide la pantalla en izquierda y derecha)

- **Columna Izquierda (`aside.visual-side`):**
  - Ancho: `50%`
  - Alto: `100%` (equivale a `100vh`)
  - *Composición interna (en columna):*
    - **Fotografía Principal**: Alto: `60%` (equivale a `60vh`)
    - **Caja de Marca (Logo y eslogan)**: Alto: `40%` (equivale a `40vh`)

- **Columna Derecha (`main.content-side`):**
  - Ancho: `50%`
  - Alto: `100%` (equivale a `100vh`)
  - *Composición interna (en columna):*
    - **Header (Navegación)**: Alto: `15%` (equivale a `15vh`)
    - **Sección Central (Proyectos)**: Alto: `70%` (equivale a `70vh`). Contiene dos artículos distribuidos en Flexbox horizontal (cada uno ocupa el `50%` del espacio de esta sección). Cada artículo posee una imagen que ocupa exactamente el `60%` del alto de dicho artículo.
    - **Footer**: Alto: `15%` (equivale a `15vh`)

# 📦 Grid Basic Practice

## 🚀 This is a practice to learn Grid and all the necessary concepts to master in amazing projects.

---

### 🤔 ¿Qué es CSS Grid?

Es una especificación de CSS que nació por la necesidad de hacer layouts mucho más dinámicos.

CSS Grid introdujo un sistema de grilla que es una cuadricula. Lo que hacemos es usar los ejes y espacios para ubicar elementos.

---

### 🛠 Conceptos para comenzar

**Contenedor**: Es el elemento que se va a convertir en una grilla.

**Item:** Son los elementos que están dentro del contenedor y todos se convertirán en grid-items.

**Líneas:** Son los elementos que limitan o dividen las filas y columnas de una grilla.

**Celda**: Es la unidad mínima que nosotros podemos tener dentro de una grilla y está delimitada por 4 líneas y solo ocupa una fila y una columna.

**Grupos de Celdas**:

- Tracks: Son aquellos que están en una misma fila o en una misma columna.
- Área: pueden usar varias filas y varias columnas a la vez.

---

### 📥 Propiedades del contenedor

Algunas son:

- Display grid
- Grid-template
- Gaps
- Grid-auto

---

### 📐 Propiedades de alineación

Esto nos sirve para alinear nuestros elementos o nuestra grilla en el espacio en el que están viviendo.

**Propiedades de alineación de los ítems**

Estas propiedades son las que declaramos en el contenedor y nos ayudan a alinear todos los ítems que viven dentro de ese contenedor.

- Justify-items
- Align-items
- Place-items

**Propiedades de alineación del contenedor**

Estas propiedades son las que ajustan la grilla completa al espacio en el que ella vive. Es la grilla alineándose completa como un bloque.

- Justify-content
- Align-content
- Place-content

**Propiedades de alineación del ítem**

Se les dan a los hijos de la grilla. Se le dan a cada uno de los elementos de nuestra grilla.

- Justify-self
- Align-self
- Place-self

---

### 👁️‍🗨️ Propiedades de ubicación

Podemos modificar la ubicación de los elementos para que cubran más espacio que una celda o para que estén en una celda diferente a la que deberían estar.

**Para las columnas**

- grid-column-start
- grid-column-end
- grid-column

**Para las filas**

- grid-row-start
- grid-row-end
- gird-row

**grid-area**

Lo que se hace es declarar de una sola vez donde va a comenzar tanto en columna como en fila y donde va a terminar. También podemos darle nombres a ciertos espacios, areas o tracks de nuestra grilla, para que solo le digamos al elemento que espacio va a llenar.

---

### 🕵 Funciones especiales

- **minmax** Esta función nos ayuda a declarar un tamaño mínimo y máximo para el ancho o alto de una celda. Podemos cambiar su tamaño sin depender del contenido que tienen.
- **repeat** Si todas las columnas o filas tienen el mismo ancho con esta función podemos darles el tamaño a las celdas en una solar declaración

---

### 📣 Keywords especiales

- **fr** o fracción, es una nueva unidad que se usa en CSS grid para darle alto y ancho en filas y columnas. 1fr es una fracción de la grilla. Lo usamos declarando la cantidad de fracciones que va a ocupar una columna o fila.
- **min-content** Ajusta el ancho de la celda para que tengamos la celda lo más fina que se pueda sin romper el contenido de la columna.
- **max-content** esto hace lo contrario a min-content, lo que hace es hacer más anchas las columnas para que el contenido se vea lo más estirado posible.
- **auto-fill/auto-fit** Estas dos propiedades nos ayudan a que nuestra grilla ocupe el 100% del espacio que tiene.
  - Auto-fill agrega columnas "fantasma" que van rellenando el espacio
  - auto-fit hace más anchas las columnas que ya tenemos para que ocupen el 100%

# HTML + CSS — Clases 2 y 3

Repositorio de ejercicios prácticos del curso de formación inicial en HTML y CSS.

---

## Clase 2 — HTML para la Presentación y Recolección de Información

### Ejercicio 1: Tabla de horarios académicos
Tabla HTML que organiza días, horarios, responsables y temas académicos. La columna de temas incluye listas no ordenadas `<ul>` dentro de cada celda `<td>`.

**Etiquetas usadas:** `<table>`, `<tr>`, `<th>`, `<td>`, `<ul>`, `<li>`, `<hr>`

### Ejercicio 2: Formulario básico de registro
Formulario HTML para recolectar datos de participantes con campos variados y etiquetas `<label>` para cada uno.

**Tipos de input usados:** `text`, `email`, `tel`, `date`, `radio`, `checkbox`, `submit`

### Reto: Página de inscripción académica
Página completa que integra la tabla de horarios, listas de temas y un formulario de inscripción con mínimo seis campos y cinco tipos de input diferentes.

---

## Clase 3 — Introducción, Cascada y Estilos Visuales con CSS

### Ejercicio 1: Tarjeta visual de perfil
Tarjeta de presentación personal construida con CSS externo. Se aplicaron colores, herencia de estilos desde `body`, gradiente lineal e imagen de fondo.

**Propiedades usadas:** `background-image`, `linear-gradient()`, `background-size`, `background-position`, `background-repeat`, `padding`, `border-radius`

### Ejercicio 2: Laboratorio de cascada, variables y opacidad
Laboratorio con cinco bloques `div` para experimentar conflictos de cascada, variables CSS y diferencias entre `opacity` y fondos con canal alfa `rgba()`.

**Conceptos aplicados:**
- Especificidad: `.box` vs `.featured` vs `.box.featured`
- Variables CSS con `:root` y `var()`
- Diferencia entre `opacity` y `rgba()` para transparencia

### Reto: Landing page con CSS externo
Landing page de un curso con tres secciones: hero, beneficios y llamado a la acción. Integra todos los conceptos de la clase.

**Incluye:**
- Mínimo 3 variables CSS en `:root`
- `linear-gradient()` en hero y CTA
- `background-size`, `background-position`, `background-repeat`
- Caso comentado donde una regla CSS sobrescribe otra
- Ejemplo de `opacity` y ejemplo de fondo con canal alfa `rgba()`

---

## Estructura del repositorio
├── ACTIVIDAD-2/

│   ├── tabla-horarios-academicos/

│   │   └── index.html

│   ├── formulario-registro/

│   │   └── index.html

│   └── reto/

│       └── index.html

├── ACTIVIDAD-3/

│   ├── clase-3-css/

│   │   ├── index.html

│   │   ├── styles.css

│   │   ├── laboratorio.html

│   │   └── css/

│   │       └── laboratorio.css

│   └── reto-landing-css/

│       ├── index.html

│       └── styles.css
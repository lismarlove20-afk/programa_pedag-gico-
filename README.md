# Bitácora de Estudio · Matemáticas 8° (Saber ICFES)

Página web estática de una sola pieza (`index.html`, sin dependencias de build) con el programa de 4 semanas sobre **lenguaje algebraico** y **congruencia de triángulos**, para preparación de las Pruebas Saber en grado octavo.

## Cómo usarla

- Ábrela directamente en el navegador (doble clic sobre `index.html`), o
- Publícala con **GitHub Pages**: Settings → Pages → Deploy from branch → selecciona la rama y la carpeta raíz (`/`). Quedará disponible en `https://tu-usuario.github.io/tu-repo/`.

No requiere Node, ni build, ni backend. Todo el HTML, CSS y JavaScript está en un solo archivo.

## Qué incluye

- Pestaña **Inicio** con el cronograma general de las 4 semanas.
- Una pestaña por semana, y dentro de cada una, 4 sub-pestañas: **Conceptos clave**, **Ejemplos aplicados**, **Ejercicios** y **Reto ICFES**.
- 24 ejercicios de práctica (con pista opcional) marcables con casilla de verificación.
- 13 preguntas tipo ICFES interactivas: al responder, se resalta la opción correcta/incorrecta y se revela la justificación.
- Barra de avance general y por semana. El progreso se guarda en `localStorage` del navegador (no se envía a ningún servidor).
- Botón "Reiniciar avance" en el pie de página.

## Personalizar contenido

Todo el contenido (conceptos, ejemplos, ejercicios y preguntas ICFES) vive en el arreglo `WEEKS` dentro del `<script>` al final de `index.html`. Puedes editar textos, añadir ejercicios o semanas nuevas modificando ese arreglo; el resto de la página (pestañas, checkboxes, quiz, progreso) se genera automáticamente a partir de esos datos.

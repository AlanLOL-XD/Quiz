# ¿Qué tanto me conoces? — Alan

Quiz personalizado de amistad, en español, con estética nocturna/indie y colores neón suaves. Es una página estática: no necesita servidor, base de datos ni instalación.

## Publicarlo en GitHub Pages

1. Crea un repositorio nuevo en GitHub, por ejemplo `quiz-alan`.
2. Sube `index.html` y `README.md` a la raíz del repositorio.
3. Abre **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`, guarda.
6. Espera a que GitHub Pages publique el sitio. La URL aparecerá en esa misma sección.

## Personalizar las respuestas

Abre `index.html` y busca `const questions`. Cada pregunta tiene esta forma:

`["Pregunta", ["Opción A", "Opción B", "Opción C", "Opción D"], 0, 0]`

- El número después de las opciones es el índice de la respuesta correcta: `0` es la primera opción, `1` la segunda, etc.
- El último número es la sección: `0` gustos, `1` personalidad, `2` lado personal, `3` amistad, `4` preguntas importantes.

**Importante:** varias respuestas se basan en cosas que Alan ha contado y otras son interpretaciones para convertirlas en un juego. Revísalas y cámbialas para que el puntaje coincida exactamente con tus respuestas. No se guardan respuestas ni se envían datos a ningún servidor.

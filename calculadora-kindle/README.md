# Calculadora de Páginas Kindle

Este es un pequeño proyecto en HTML, CSS y JavaScript que permite **calcular tu progreso de lectura** en un libro de Kindle y, opcionalmente, **compararlo** con el número real de páginas de la versión física del libro.

## ¿Cómo funciona?

- Introduces la **posición final** del libro Kindle.
- Introduces tres **posiciones intermedias** (para estimar tu ritmo de lectura).
- (Opcional) Introduces el **número real de páginas** si deseas ver la equivalencia con un libro físico.
- El programa calcula:
  - Porcentaje leído.
  - Número de páginas Kindle leídas y restantes.
  - Equivalencia en páginas reales (si has introducido ese dato).

## Estilo

- Diseño sencillo y responsivo.
- Los datos de equivalencia con el libro físico se muestran en **color azul** para diferenciarlos.

## Archivos

- Todo el proyecto está contenido en un solo archivo HTML, con el CSS embebido, para fácil uso y transporte.

## Uso

1. Abre el archivo `index.html` en cualquier navegador moderno.
2. Rellena los datos solicitados en el formulario.
3. Pulsa **Calcular** para ver los resultados.
4. Puedes pulsar **Borrar** para limpiar los campos y empezar de nuevo.

## Notas

- El cálculo se basa en un ajuste automático dependiendo del ritmo de avance.
- El número de páginas estimadas puede variar ligeramente debido al tamaño de fuente y formato de Kindle.
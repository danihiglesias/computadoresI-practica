# Computadores I · Material de prácticas

Abre `index.html` para acceder al índice general. El sitio funciona directamente en el navegador, sin instalación.

## Organización

- `index.html`: portada de la asignatura.
- `assets/img/`: imágenes compartidas entre sesiones.
- `sesiones/`: una carpeta por sesión, numerada con dos dígitos.

- `sesiones/01-introduccion/` — pendiente.
- `sesiones/02-operaciones-con-bits/` — pendiente.
- `sesiones/03-puertas-logicas/` — pendiente.
- `sesiones/04-modulos/` — pendiente.
- `sesiones/05-encaminadores-sumadores/` — publicada.
- `sesiones/06-biestables/` — pendiente.
- `sesiones/07-registros/` — pendiente.
- `sesiones/08-contadores/` — pendiente.
- `sesiones/09-alu/` — pendiente.

## Incorporar una sesión

1. Coloca los materiales en la carpeta correspondiente. Usa `index.html` como portada de la sesión y nombres descriptivos para sus páginas.
2. Enlaza las páginas de la misma sesión con rutas relativas, por ejemplo `ejercicio.html`; para volver a su portada, usa `index.html`.
3. El enlace al índice general desde una sesión es `../../index.html`. Las imágenes compartidas se referencian como `../../assets/img/nombre.svg`.
4. Guarda imágenes, descargas u otros materiales propios en subcarpetas de la sesión, cuando se necesiten.
5. En el índice general, convierte la tarjeta pendiente en un enlace con las clases `tarjeta disponible` y la ruta `sesiones/NN-nombre/index.html`. Actualiza su descripción, estado y los contadores de sesiones y recursos disponibles.
6. Conserva el pie de autoría y la estética de la sesión 5, que sirve como referencia.

Las carpetas pendientes se dejan vacías hasta incorporar su contenido. Las rutas sin espacios ni tildes facilitan la publicación del sitio.

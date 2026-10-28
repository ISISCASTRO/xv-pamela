# XV Pamela

Invitación y pases digitales para el 21 de noviembre de 2026.

## Datos actualizados

La lista contiene 123 invitados principales, 43 acompañantes y 166 accesos.

- PAME-116: ABRIL MARISOL AQUINO CARRASCO, sin acompañantes (1 acceso).
- PAME-117: SABEL ZARATE, 2 acompañantes (3 accesos).
- PAME-118: XIMENA ZOE RUIZ SANCHEZ, sin acompañantes (1 acceso).
- PAME-079: LIZBETH ACEVEDO, 1 acompañante (2 accesos).
- PAME-073: ARMANDO LORANCA ALEMAN, 2 acompañantes (3 accesos).

La lista protegida, los archivos de enlaces y `netlify/functions/guests.json` están conciliados por folio. Las claves existentes se conservan para mantener los enlaces distribuidos. Las confirmaciones existentes se conservan y los pases generados no registran asistencia.

## Despliegue

El código del sitio se encuentra en `xv-pamela-netlify-source.zip`. La configuración de Netlify en la raíz extrae ese archivo en `site/`, instala las dependencias y genera `site/public/`. Esto permite desplegar exactamente la versión empaquetada. Si se extrae el ZIP para trabajar con el código directamente, su propia configuración ejecuta `node tools/build-public.mjs` y publica `public/`. Las funciones se empaquetan con esbuild e importan los datos de invitados directamente, evitando la carga mediante `import.meta.url` que producía el error 502.

La búsqueda de pases utiliza el nombre completo para admitir nombres compuestos y registros con un solo nombre. Al abrir un pase guardado, sus datos se consultan de nuevo en el servidor para mostrar los acompañantes vigentes. Los enlaces personalizados usan el dominio de producción; para probarlos en un Deploy Preview se conserva la ruta y los parámetros y se cambia únicamente el dominio.

El ZIP contiene el código, los activos, el Excel protegido, los enlaces actualizados y los pases añadidos o corregidos. El Excel conserva su contraseña de apertura y la columna de confirmación original.

## Altas del 27 de octubre de 2026

- PAME-119: MATEO BRAVO HERNÁNDEZ, 0 acompañantes (1 accesos).
- PAME-120: ROGER MORALES MARTINEZ, 0 acompañantes (1 accesos).
- PAME-121: ERICK GOMEZ, 1 acompañantes (2 accesos).
- PAME-122: EDILBERTO SAUCEDO, 1 acompañantes (2 accesos).
- PAME-123: CAROLINA CORDOVA, 1 acompañantes (2 accesos).

# KONNECT Seguimiento V17

Repositorio listo para GitHub y Vercel.

## Novedades V17

- Cierres prioritarios del mes actual detectados desde `MES PARA CIERRE`.
- Nueva diapositiva para los cierres del mes siguiente.
- Ambas vistas usan tablas visibles, encabezado fijo, scroll morado y estatus por color.
- Al cargar el archivo comercial, ambas tablas se actualizan automáticamente.

## Subir a GitHub

Sube el contenido de esta carpeta directamente a la raíz del repositorio. Deben verse:

- `dist/`
- `src/`
- `index.html`
- `package.json`
- `package-lock.json`
- `vercel.json`

No subas `node_modules`.

## Vercel

- Framework Preset: Other
- Root Directory: `./`

El archivo `vercel.json` publica la carpeta `dist` ya compilada.

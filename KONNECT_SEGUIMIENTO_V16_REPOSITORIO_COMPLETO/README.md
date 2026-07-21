# KONNECT Seguimiento V16

Repositorio listo para GitHub y Vercel.

## Subir a GitHub

Sube el contenido de esta carpeta a la raíz del repositorio. Deben verse directamente:

- `dist/`
- `src/`
- `index.html`
- `package.json`
- `package-lock.json`
- `vercel.json`

No subas `node_modules`.

## Configuración en Vercel

- Framework Preset: Other
- Root Directory: `./`

El archivo `vercel.json` ya indica a Vercel que publique la carpeta `dist` sin ejecutar `npm install` ni recompilar el proyecto.

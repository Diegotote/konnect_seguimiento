# KONNECT Dashboard V16

Versión Vercel/Vite del Centro de Seguimiento KONNECT.

## Desarrollo local

```bash
npm install
npm run dev
```

## Producción

```bash
npm run build
```

La actualización de Excel se procesa en el navegador. Los datos normalizados se guardan en `localStorage` para conservar el último archivo cargado en el mismo navegador.

La persistencia global con Vercel Blob se conectará como siguiente capa sin modificar el diseño.

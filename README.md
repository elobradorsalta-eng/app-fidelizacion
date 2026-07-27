# App de Fidelización · Catalina's Café + El Obrador

Proyecto Vite + React + Tailwind CSS. Prototipo funcional con las 22 pantallas del cliente y de la app de caja, con los logos reales embebidos.

## Correr en local
```bash
npm install
npm run dev
```
Abre la URL que muestra la consola (por defecto http://localhost:5173).

## Build de producción
```bash
npm run build      # genera la carpeta dist/
npm run preview    # previsualiza el build
```

## Desplegar en Vercel
1. Subí esta carpeta a un repositorio de GitHub (o importá el ZIP).
2. En Vercel: "Add New… → Project", elegí el repo.
3. Vercel detecta Vite automáticamente (Build: `vite build`, Output: `dist`). Deploy.

No requiere configuración extra: `vercel.json` ya deja fijados el build command y el output.

## Notas
- Tailwind está configurado por PostCSS (`tailwind.config.js`, `postcss.config.js`), listo para producción.
- Los íconos (Tabler) y la tipografía (Playfair Display) se cargan por CDN desde `index.html`.
- Es un prototipo de diseño y flujo: datos de ejemplo, sin backend. La lógica de negocio está en el documento de especificación que acompaña al proyecto.

# Proyecto corregido para Vercel

Sube esta carpeta completa a GitHub/Vercel.

- Node corregido a 24.x.
- Sin package-lock para evitar conflictos.
- Vercel instala dependencias automáticamente con npm install.
- Panel en public/index.html.
- API en api/datos.js.
- MongoDB ya está dentro del código y también acepta MONGODB_URI si deseas ponerlo en Vercel.

Importante: cuando Vercel muestra `Installing dependencies...` NO es error; es instalación normal.

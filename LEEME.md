# Notas – cuadernos digitales (app independiente)

No necesita Claude ni internet. Todo está en `index.html`. Tus cuadernos se guardan en el almacenamiento del navegador/app de ese equipo.

## Opción 1 – Lenovo con Windows: app de escritorio (.exe)
1. Instala Node.js (https://nodejs.org).
2. En esta carpeta, abre una terminal y ejecuta:
   npm install
   npm start          (para probarla)
   npm run build      (genera el instalador en la carpeta dist/)
3. Instala el .exe generado.

## Opción 2 – Cualquier Lenovo (Android o Windows): instalar como app (PWA)
1. Sube esta carpeta a un hosting gratis con https (Netlify Drop: https://app.netlify.com/drop, GitHub Pages o Cloudflare Pages). Basta arrastrar la carpeta.
2. Abre la dirección en Chrome o Edge y elige "Instalar app" / "Agregar a pantalla de inicio".
3. Funciona sin conexión y se abre en su propia ventana, sin barra del navegador.

## Opción 3 – Tablet Lenovo con Android: APK
Con la dirección de la Opción 2, entra a https://www.pwabuilder.com, pega la URL y descarga el paquete Android (APK).

## Prueba rápida sin instalar nada
Abre `index.html` con doble clic en Chrome o Edge. Funciona, pero no se puede "instalar" desde un archivo local.

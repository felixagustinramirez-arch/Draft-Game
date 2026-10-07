# Draft FC (PWA)

Juego de draft de fútbol: eliges formación, tiras los dados, armas tu equipo de 23 y juegas 38 jornadas contra clubes reales de FC 27.

## Archivos
- `index.html`: toda la app (juego, datos y estilos).
- `manifest.webmanifest`: nombre, colores e iconos para instalarla.
- `sw.js`: permite que funcione sin conexión.
- `icons/`: iconos de la app.

## Publicar gratis en GitHub Pages (5 pasos)
1. Entra a github.com y crea un repositorio nuevo, por ejemplo `draft-fc`. Debe ser público.
2. Pulsa "Add file" > "Upload files" y sube **el contenido** de esta carpeta (index.html, manifest.webmanifest, sw.js y la carpeta icons), no la carpeta entera.
3. Pulsa "Commit changes".
4. Ve a Settings > Pages. En "Branch" elige `main` y la carpeta `/ (root)`. Pulsa Save.
5. Espera 1 o 2 minutos. Tu app quedará en `https://TU-USUARIO.github.io/draft-fc/`.

Funciona igual en Netlify, Vercel o Cloudflare Pages: sube la carpeta y listo. Necesita HTTPS (todos lo dan).

## Instalarla en el celular
- **iPhone (Safari):** abre el enlace, pulsa Compartir > "Añadir a pantalla de inicio".
- **Android (Chrome):** abre el enlace, pulsa los tres puntos > "Instalar aplicación".

Después de abrirla una vez con internet, funciona sin conexión. La partida se guarda sola en el dispositivo.

## Actualizar la app
Cuando cambies `index.html`, cambia también `draft-fc-v1` por `draft-fc-v2` en la primera línea de `sw.js`. Así los celulares descargan la versión nueva.

## Aviso
Los datos de jugadores y clubes vienen de FC 27 (fcratings.com). Es un proyecto de fans, sin relación con EA Sports, FIFA ni los clubes. Si lo vas a publicar de forma abierta, revisa que el uso de nombres y datos reales sea aceptable para ti.

# PetZone PWA

## Probarla en iPhone
1. Sube el contenido de esta carpeta a un repositorio de GitHub.
2. En GitHub, abre **Settings → Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**.
4. Selecciona la rama `main` y la carpeta `/(root)`, y guarda.
5. Espera a que GitHub Pages publique la web y abre la URL HTTPS que te muestre.
6. En tu iPhone, abre esa URL con **Safari**.
7. Pulsa **Compartir** → **Añadir a pantalla de inicio** → **Añadir**.
8. Abre PetZone desde el icono nuevo de la pantalla de inicio.

## Archivos
- `index.html`: juego.
- `manifest.webmanifest`: nombre, icono y modo de aplicación.
- `service-worker.js`: caché básica para volver a abrirla sin conexión.
- `icon.svg`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`: iconos.

Nota: para instalar una PWA en iPhone debe estar publicada en una dirección HTTPS. Abrir el archivo HTML directamente no basta. El progreso se guarda localmente en el navegador/dispositivo; no se sincroniza entre dispositivos.

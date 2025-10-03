PWA Lista para desplegar

Archivos:
- index.html (tu app con registro del Service Worker)
- manifest.json (metadatos de la PWA)
- service-worker.js (cache-first)
- icons/icon-192.png, icons/icon-512.png (iconos PWA)

Cómo desplegar (GitHub Pages):
1) Crea un repositorio y sube el contenido de esta carpeta al root del repo.
2) Settings > Pages > Branch: main, folder: /(root).
3) Abre https://<usuario>.github.io/<repo>/ en Safari (iOS/iPadOS).
4) Compartir > Añadir a pantalla de inicio.

Notas iOS:
- La primera carga necesita conexión para cachear las librerías CDN (Tailwind, XLSX, jsPDF...).
- Posteriormente funcionará offline (según lo cacheado).
- Exportar/guardar archivos abrirá el panel de 'Compartir' de iOS.

# Saval Agency · Landing

Landing page de Saval Agency: marca, TikToks y landing pages para negocios locales en Colombia.

- En línea: https://saval-agency.netlify.app
- Contacto: WhatsApp 313 699 2754 · Instagram @saval.agency

## Archivos

- `index.html`: la página completa (HTML, CSS y JS en un solo archivo).
- `img/`: imágenes. Las de servicios (`gen-*.webp`) fueron generadas con IA; el resto son fotos libres de Wikimedia Commons, con sus créditos en el pie de la página y en `creditos-fotos.json`.

## Cambiar el número de WhatsApp

En `index.html`, busca `var WA_NUMBER` y pon el número con código de país, sin "+" (ej. `573136992754`).

## Publicar cambios

```
netlify deploy --prod --dir .
```

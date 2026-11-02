# Lautaro Mecánica – Web

Sitio estático del taller (mecánica general y cajas automáticas, Gonnet, La Plata).
Publicado en Netlify: https://lautaromecanica.netlify.app

## Estructura
- `index.html`: página completa (HTML + CSS + JS). Los datos del taller (teléfono, redes, horarios, reseñas) están en el bloque `<script id="state">`.
- `assets/`: logo, fotos y video.
- `robots.txt`, `sitemap.xml`: SEO. Si cambia el dominio, actualizar la URL en ambos y en `index.html` (canonical y og:).

## Cómo cambiar algo
1. Editar el archivo en GitHub (lápiz) o en local.
2. Hacer commit a `main`.
3. Netlify publica solo en unos segundos.

## Datos que más se cambian
Dentro de `<script id="state">`: `taller.whatsapp`, `instagram`, `tiktok`, `facebook`, `horarios`, `resenas`.

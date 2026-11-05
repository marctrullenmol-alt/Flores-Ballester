# Talleres Flores Ballester S.L. — Landing page

Landing page del taller mecánico multimarca Talleres Flores Ballester, en Almassora (Castellón).

Todo está en un único archivo, `index.html` (HTML + Tailwind + Three.js + GSAP por CDN), sin dependencias que instalar.

## Ver en local
Abre `index.html` en el navegador.

## Publicar con GitHub Pages
Settings → Pages → Source: *Deploy from a branch* → rama `main`, carpeta `/ (root)`.

## Antes de publicar
Edita el objeto `CONFIG` al principio del último `<script>` de `index.html`:
- Teléfono, email y dirección reales.
- Años de experiencia, vehículos reparados y horario (ahora son valores de ejemplo).
- `formEndpoint` (p. ej. Formspree) o `whatsapp` para que el formulario envíe las citas.
- Enlaces a Aviso legal, Privacidad y Cookies.

Cambia también el teléfono y la dirección del bloque JSON-LD del `<head>`.

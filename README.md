# Huachumascota — Tienda demo (Apizaco, Tlaxcala)

-----------


### Descripción

-----

Sitio estático de catálogo para venta por WhatsApp. Proyecto demo/portafolio — listo para GitHub Pages.

Contacto / Soporte
Soporte: PLACEHOLDER_SUPPORT_EMAIL
WhatsApp: +52 2464473034

Estructura
index.html — Frontend público
data/products.json — Catálogo consumido por la UI
repo/imgs/ — Imágenes de producto
tools/generate-products.js — Script para generar products.json
.github/workflows/ — CI: generar y publicar
Despliegue rápido (GitHub Pages)
Subir todo al repo https://github.com/PLACEHOLDER_ORG/PLACEHOLDER_REPO
(Opcional) Crear secret DEPLOY_TOKEN con un PAT si usas commit automático.
Activar Pages en Settings → Pages (branch main, root) o dejar que el workflow oficial publique.
Cómo actualizar productos
Añade imágenes a repo/imgs/ (subcarpetas opcionales por categoría).
Push a main. El workflow ejecutará tools/generate-products.js y actualizará data/products.json.
Notas legales / licencia
Este repo usa la licencia MIT: LICENSE (reemplaza el autor en la licencia).
No subir datos personales sensibles al repo público.

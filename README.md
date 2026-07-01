# Medical Fitness Nutrition — Dra. Jeremy Moreno

Landing page estática (un solo archivo `index.html`) para consultas, seguimiento y guía de péptidos.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (puede ser público o privado con GitHub Pro).
2. Sube estos archivos a la raíz del repositorio:
   - `index.html`
   - carpeta `images/` completa (con las 3 fotos)
3. Ve a **Settings → Pages** del repositorio.
4. En "Source", selecciona la rama `main` y la carpeta `/ (root)`.
5. Guarda. En 1–2 minutos tu página estará disponible en:
   `https://tu-usuario.github.io/nombre-del-repo/`

## Editar contenido

Todo el sitio está en `index.html` (HTML + CSS + JS en un solo archivo, sin dependencias externas salvo la tipografía de Google Fonts). Para editar:

- **Textos**: busca la sección correspondiente por su comentario (`<!-- HERO -->`, `<!-- GUIA -->`, etc.) y edita el texto directamente.
- **Número de WhatsApp**: aparece varias veces como `https://wa.me/50769836478`. Si cambia, hay que reemplazarlo en todas las ocurrencias.
- **Fotos**: reemplaza los archivos en `images/` manteniendo el mismo nombre, o cambia la ruta en el HTML.
- **Catálogo de péptidos**: cada tarjeta está en su propio bloque `<div class="pep fade">...</div>` dentro de `<!-- GUIDE -->`. No se muestran precios ni dosis públicamente por decisión de marca — solo se listan péptido, categoría, beneficio y efectos visibles, con botón de WhatsApp para consultar.

## Notas de diseño

- Paleta y tipografía siguen la guía de marca (azul profundo `#0E3A5B`, turquesa `#16C4B5`, esmeralda `#12A76A` solo para CTAs, tipografía Space Grotesk / Inter).
- Las 3 fotos de la Dra. Moreno se aplicaron con un tratamiento duotono azul para unificar con la paleta de marca (las fotos originales tenían fondos rojos/genéricos que no correspondían a la identidad visual).
- No se incluyeron dosis, frecuencia ni vías de aplicación del catálogo de péptidos en la versión pública — esa información queda reservada para consulta directa, tanto por posicionamiento de marca ("no vendemos péptidos, vendemos resultados") como por precaución regulatoria.

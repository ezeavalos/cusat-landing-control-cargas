
# CUSAT — Landing "Sistema de Gestión de Cargas"

Este paquete contiene una landing estática (HTML/CSS) sin costos mensuales, pensada para publicar bajo tu dominio con Cloudflare Pages o GitHub Pages.

## Estructura
- `index.html` — página principal
- `styles.css` — estilos
- (Opcional) agrega imágenes en `./img` y actualízalas en `index.html`

## SEO/Ads
- Meta y Open Graph incluidos.
- `schema.org` para Organization y Service.
- Bloque del **LinkedIn Insight Tag** listo (reemplaza `REEMPLAZAR_PARTNER_ID` por tu ID).

## Publicar en Cloudflare Pages (0 USD)
1. Crear un repo en GitHub y subir estos archivos.
2. En Cloudflare → **Pages** → **Create Project** → conectar el repo.
3. Build: **None** (sitio estático) · Directorio: raíz.
4. Al finalizar, en **Custom Domains** agrega `landing.cusat.com.py` (o el que prefieras).
5. CNAME apuntando al subdominio que te indica Cloudflare. SSL automático.

## Publicar en GitHub Pages (0 USD)
1. Subir archivos a un repo.
2. Configurar en **Settings → Pages** → **Branch: main / root**.
3. Para **custom domain**, agregar el dominio y crear CNAME.

## Formulario
Por defecto el form usa `mailto:`. Alternativas gratuitas:
- **Embed de HubSpot** (recomendado para LinkedIn Ads): pega el script del formulario y listo.
- **Formspree/StaticForms** (free tiers con límites).

## Paleta CUSAT
- Azul: #0c5ba8
- Naranja: #f39433
- Gris: #706f6f


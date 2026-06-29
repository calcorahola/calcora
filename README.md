# Calcora Sitio estatico profesional listo para publicar en Netlify o Vercel. ## Configuracion central La marca y datos principales estan centralizados en `assets/js/data.js` como `CalcoraConfig`. Antes de publicar, cambia `https://calcora.es` por el dominio real en la configuracion y regenera o reemplaza las URLs canonicas del HTML, sitemap y robots. ## SEO incluido - Metadatos unicos por pagina.
- Breadcrumbs visibles y Schema.org.
- JSON-LD para WebSite, Organization, FAQPage, BreadcrumbList, Article y SoftwareApplication.
- Sitemap completo y robots.txt.
- Blog inicial con articulos relacionados.
- Espacios preparados para Google AdSense sin insertar anuncios. ## Estructura - `index.html`: portada.
- `blog/`: articulos SEO.
- `herramientas/<slug>/index.html`: pagina individual de cada herramienta.
- `assets/js/tools/`: logica independiente por herramienta.

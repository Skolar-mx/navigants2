# navigants.com.mx

Sitio estático (React, prerenderizado) de Navigants. La carpeta `public/` es el sitio ya compilado:
cada página tiene su propio HTML con título, descripción, imagen para redes y datos estructurados.
Incluye `sitemap.xml`, `robots.txt` y `llms.txt`.

## Despliegue
1. Sube los cambios a GitHub.
2. En cPanel → Git Version Control → navigants → Pull or Deploy → **Deploy HEAD Commit**.
3. `.cpanel.yml` copia `public/` a `/home/r0sel1/public_html/navigants.com.mx/`.

No edites archivos directamente en el servidor: el siguiente Deploy los sobrescribe.

Desarrollado por [Skolar.mx](https://www.skolar.mx/)

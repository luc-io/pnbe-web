# Web — Club Peña Náutica Bajada España

Sitio estático (HTML + CSS, sin build).

## Publicar en GitHub Pages
1. Crear un repo (ej. `pnbe-web`) y subir el contenido de esta carpeta.
2. En el repo: Settings → Pages → Source: "Deploy from a branch" → `main` / `(root)`.
3. Queda en `https://<usuario>.github.io/pnbe-web/`.
4. Dominio propio (ej. pnbe.com.ar): crear un archivo `CNAME` con el dominio y apuntar el DNS a GitHub Pages.

## Cargar fotos
Las fotos son placeholders `<figure class="photo" data-label="...">`.
Para reemplazar: poner la imagen en `img/` y meter un `<img>` adentro de la figura:

```html
<figure class="photo"><img src="img/muelle.jpg" alt="Atardecer en el muelle"></figure>
```

El logo provisorio está en `img/logo.svg`: reemplazarlo por el oficial.

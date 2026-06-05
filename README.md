# Centro Psicológico MAD — Sitio web

Sitio web de una sola página para el Centro Psicológico MAD, listo para publicar en **GitHub Pages**.

## Contenido

```
MAD-sitio/
├── index.html          ← la página (ábrela en el navegador para previsualizar)
├── .nojekyll           ← evita que GitHub procese la carpeta con Jekyll
└── assets/
    ├── logo-indigo.png ← logo para fondos claros
    ├── logo-white.png  ← logo para fondos oscuros
    ├── hero.webp       ← imagen del hero
    └── about.webp      ← imagen de la sección "Nosotros"
```

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `mad-web`).
2. Sube **todo el contenido de esta carpeta** (`index.html`, `.nojekyll` y la carpeta `assets/`) a la raíz del repositorio.
   - Puedes arrastrar los archivos en la web de GitHub (**Add file → Upload files**), o usar git:
     ```bash
     git init
     git add .
     git commit -m "Sitio web MAD"
     git branch -M main
     git remote add origin https://github.com/TU-USUARIO/mad-web.git
     git push -u origin main
     ```
3. En el repositorio ve a **Settings → Pages**.
4. En **Source** elige la rama `main` y la carpeta `/ (root)`. Guarda.
5. Espera 1–2 minutos. Tu sitio quedará publicado en:
   `https://TU-USUARIO.github.io/mad-web/`

## Enlaces configurados (ya funcionan)

- **WhatsApp:** https://wa.me/593999295186
- **Llamar:** +593 98 280 1304 · +593 99 929 5186
- **Correo:** angie.carrera@madmente.com
- **Facebook / Instagram:** enlaces oficiales del centro
- **Mapa:** Google Maps embebido de la Sede Sur

## Cómo editar el contenido

- **Textos:** abre `index.html` y edita directamente el texto entre las etiquetas.
- **Imágenes:** reemplaza `assets/hero.webp` y `assets/about.webp` por otras (mismo nombre) para cambiarlas.
- **Testimonios:** son de ejemplo. Búscalos en `index.html` (sección "Historias que nos inspiran") y reemplázalos con reseñas reales.
- **Colores:** están definidos como variables al inicio del `<style>` (busca `:root`). Cambiando esos valores cambia toda la paleta.

---
Hecho con cariño · paleta periwinkle · fuentes Montserrat + Poppins.

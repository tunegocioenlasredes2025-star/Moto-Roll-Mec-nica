# Motos Roll Mecánica — Sitio web

Sitio web oficial de **Motos Roll Mecánica**, taller de motos en Ituzaingó, zona oeste del Gran Buenos Aires.

Landing page premium, mobile-first, de una sola página, con foco en la conversión hacia WhatsApp.

## Stack

- HTML5 + CSS3 + JavaScript vanilla (sin dependencias, sin build)
- Tipografías: Oswald (títulos) + Barlow (texto) vía Google Fonts
- Imágenes optimizadas en WebP
- SEO local: meta tags, Open Graph, Schema `MotorcycleRepair`, `sitemap.xml`, `robots.txt`

## Estructura

```
.
├── index.html            Página principal
├── styles.css            Sistema visual (negro + naranja #FF6501 + cromo)
├── script.js             Nav, animaciones al scroll, menú móvil
├── site.webmanifest      PWA / iconos
├── robots.txt
├── sitemap.xml
├── vercel.json           Config de deploy (cache, headers, clean URLs)
└── assets/
    ├── img/              Logo, fotos del taller y trabajos, OG image
    └── fav-*.png         Favicons
```

## Deploy en Vercel

Es un sitio estático: no requiere build.

1. Importar este repositorio en [Vercel](https://vercel.com/new).
2. Framework Preset: **Other** (Vercel lo detecta como estático).
3. Build Command: *(vacío)* · Output Directory: `.` (raíz).
4. Deploy.

Para el dominio final, actualizar la URL canónica y de Open Graph en `index.html`
(actualmente `https://motosroll.com.ar/`).

## Datos del negocio

- **Dirección:** General Fernández de la Cruz 896, Ituzaingó, Buenos Aires
- **WhatsApp:** 11 3471-0637
- **Instagram:** [@motos.roll](https://www.instagram.com/motos.roll)

---

Desarrollado por [Tu Negocio En Las Redes](https://www.tunegocioenlasredes.com.ar).

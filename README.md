# La Lomitería Web

Sitio web de **La Lomitería** — Güemes 773, Campana, Buenos Aires.

Pensado para GitHub Pages, sin frameworks ni build step: HTML, CSS y JS plano.

---

## Estructura

```
la-lomiteria-web/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── assets/
│   ├── images/
│   └── icons/
├── README.md
└── .gitignore
```

## Estado

El sitio está completo con datos e imágenes reales: carta, precios, logo, fotos del local y de los lomitos, WhatsApp, Instagram y horarios. Lo único pendiente es una decisión tuya (no técnica): si publicar o no las fotos con clientes/banda tocando.

- [x] Número de WhatsApp real cargado en `negocio.whatsapp` (`js/script.js`).
- [x] Carta real cargada en `menuData` (`js/script.js`): 6 variantes, precios por 100/200/300gr.
- [x] Fotos de 5 de los 6 lomitos cargadas en `assets/images/` (falta "Radical").
- [x] Horario real (miércoles a lunes, 20 a 23:30) en hero y contacto.
- [x] Foto de "Radical" cargada.
- [x] Logo real cargado (fondo negro removido, PNG transparente en `assets/images/logo.png`).
- [x] Fotos del local (barra, salón, pared de ladrillo) y de la fachada de noche cargadas en `assets/images/`.
- [x] Música en vivo confirmada: viernes y sábado (el flyer de "domingo" era un evento puntual, no la agenda fija).
- [ ] Fotos con clientes/banda tocando (las que mandaste tienen caras identificables) — no las subí sin que lo confirmes explícitamente. Si querés usarlas igual, avisá.

## Publicación (GitHub Pages)

Settings → Pages → Deploy from branch → `main` → `/root`

## Funciones actuales (v2.0)

- Diseño responsive, mobile-first
- Menú generado dinámicamente desde un array de datos (`menuData`), con precios por gramaje
- Pedido por WhatsApp con mensaje armado, incluyendo el nombre del producto cuando se pide desde el menú
- Animación de aparición al hacer scroll con fallback: si JS no carga, el contenido queda visible igual
- Accesibilidad básica: skip-link, foco visible, `prefers-reduced-motion` respetado

## Próximas mejoras

### Versión 3.0
- Sistema propio de pedidos (más allá de WhatsApp)
- Gestión de promociones y eventos desde un archivo de datos
- Integración con Instagram
- Panel administrativo simple para editar menú y precios sin tocar código

---

**La Lomitería** — Campana, Buenos Aires 🇦🇷

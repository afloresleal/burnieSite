# Burnie Site

Landing page y páginas legales de **Burnie**, la app iOS de fitness con coach "spicy".

## Archivos principales

- `index.html` - Landing principal en inglés
- `index-es.html` - Landing principal en español
- `privacy.html` - Política de privacidad (EN)
- `privacidad.html` - Política de privacidad (ES)
- `styles.css` - Estilos globales
- `assets/` - Screenshots y favicon de la app (versiones EN/ES)

## Assets incluidos

Los screenshots en `assets/` tienen versión en inglés y español para cada pantalla:
- `screen-hero`, `home_counter`, `calendar`, `calendar-grade`, `effort`, `hall`, `reminder`, `avatar`

## Dev local

No requiere instalación. Abre directamente en el navegador o levanta un servidor estático:

```bash
cd burnie-site
python3 -m http.server 8080
# http://localhost:8080/index.html     (EN)
# http://localhost:8080/index-es.html  (ES)
```

## Dependencias externas

- Google Fonts: Fredoka (400–700)
- Google Analytics: `G-070WCB5ZHL`

## Deploy

Sitio estático. Se puede publicar en GitHub Pages, Vercel, o cualquier hosting estático.

## Notas

- Si actualizas copy o estructura, mantén ambos idiomas en paridad.
- Las rutas de assets son relativas, no requieren configuración adicional.

**Repository:** [github.com/afloresleal/burnieSite](https://github.com/afloresleal/burnieSite)

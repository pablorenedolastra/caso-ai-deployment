# Caso práctico — AI Deployment Director

Material de defensa del caso, publicado como web estática para poder repasarlo desde el móvil
y compartir un único enlace con los entrevistadores.

**Enlace:** https://pablorenedolastra.github.io/caso-ai-deployment/

## Contenido

| Pieza | Ruta | Qué es |
|---|---|---|
| Executive Deck | [`/deck/`](deck/) | Presentación 16:9 de defensa. Se navega con ← →. |
| AP Fase 1 | [`/documento/`](documento/) | Documento largo: business case, plan de las primeras semanas, criterios y el *ask*. |

El índice ([`index.html`](index.html)) enlaza a las dos.

## Notas técnicas

- Cada pieza es un **HTML autocontenido**: todas las imágenes van embebidas en base64, así que
  una vez cargada la página funciona sin conexión. La única dependencia externa es Google Fonts
  (DM Sans), con fallback a Helvetica/Arial.
- El repo es público porque GitHub Pages no sirve repos privados en el plan gratuito, pero las
  páginas llevan `<meta name="robots" content="noindex,nofollow,noarchive">` y hay un
  `robots.txt` con `Disallow: /`, de modo que no se indexan en buscadores.
- `.nojekyll` evita que GitHub Pages procese los archivos con Jekyll.

---

Pablo Renedo

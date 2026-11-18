# Bios y datos (estilo FNF)

- `index.html` → la página.
- `data/index.json` → lista de categorías y entradas.
- `txt/<categoría>/*.txt` → el contenido. Si el .txt no existe, la entrada sale bloqueada (silueta glitcheada).
- `.github/workflows/pages.yml` → publica la página en GitHub Pages en cada push a `main`.

## Activar
Repositorio → Settings → Pages → Source: **GitHub Actions**.

## Añadir personaje
1. Añade una línea en `data/index.json` (categoría `personajes`).
2. Sube su `.txt` a la ruta indicada en `archivo` → se desbloquea.

## Anuncios
Solo quien tiene permiso de escritura en el repo (tú) puede publicar: sube un `.txt` a `txt/anuncios/` y añade una entrada con `fecha` en `data/index.json`. Mantén el repo sin colaboradores.

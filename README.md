# VAT_Baker Landing Page

Landing page de VAT_Baker optimizada para GitHub Pages.

## Estructura

```text
WEB/
|-- index.html
|-- package.json
|-- .gitignore
`-- assets/
```

## Publicar en GitHub Pages

Este repositorio ya viene configurado para deploy automatico con GitHub Actions.

- Workflow: `.github/workflows/deploy-pages.yml`
- Archivo `.nojekyll` incluido para evitar problemas de procesamiento en Pages

Pasos:

1. Sube este repo a GitHub en la rama `main`.
2. Ve a `Settings > Pages`.
3. En `Source`, selecciona `GitHub Actions`.
4. Haz push a `main` (o ejecuta el workflow en `Actions`).
5. Tu sitio quedara publicado en:
   `https://TU-USUARIO.github.io/TU-REPO/`

## Nota sobre YouTube en local

Si abres `index.html` con `file://`, YouTube puede mostrar Error 153.
Para probar embeds localmente, usa un servidor HTTP local (por ejemplo Live Server o `python -m http.server 5500`).

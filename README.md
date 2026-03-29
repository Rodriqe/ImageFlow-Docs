# FlowImage Documentation Website

Este directorio contiene el sitio web publico de FlowImage, publicado en GitHub Pages desde el repositorio `FlowImage-Docs`.

## URL Publica

Sitio en vivo: https://rodriqe.github.io/FlowImage-Docs/docs/

## Archivos

| Archivo | Descripcion | URL |
|---|---|---|
| `docs/index.html` | Landing page principal | https://rodriqe.github.io/FlowImage-Docs/docs/index.html |
| `docs/privacy.html` | Privacy Policy (App Store) | https://rodriqe.github.io/FlowImage-Docs/docs/privacy.html |
| `docs/support.html` | Soporte publico para App Store Connect | https://rodriqe.github.io/FlowImage-Docs/docs/support.html |

## Proposito

- `privacy.html`: URL oficial de Privacy Policy para App Store Connect
- `support.html`: URL oficial de soporte para App Store Connect
- `index.html`: Landing page publica del proyecto

## Publicacion

Este sitio se publica automaticamente via GitHub Pages cuando se hace push al repositorio `FlowImage-Docs` en la rama `main`.

### Configuracion recomendada

1. Repositorio -> Settings -> Pages
2. Source: Deploy from a branch
3. Branch: `main` -> `/docs`

### Actualizar contenido

```bash
# Editar archivos en docs/
# Luego subirlos al repo publico FlowImage-Docs:
git add docs/
git commit -m "Update documentation website"
git push origin main
```

## Checklist GitHub Pages

- [x] Directorio `/docs` creado
- [x] `index.html` creado
- [x] `privacy.html` creado
- [x] `support.html` creado
- [ ] GitHub Pages habilitado (Settings -> Pages)
- [ ] Sitio verificado: https://rodriqe.github.io/FlowImage-Docs/docs/
- [ ] Privacy Policy URL anadida a App Store Connect
- [ ] Support URL anadida a App Store Connect

## Enlaces importantes

- Privacy Policy: https://rodriqe.github.io/FlowImage-Docs/docs/privacy.html
- Support: https://rodriqe.github.io/FlowImage-Docs/docs/support.html
- GitHub Repo: https://github.com/Rodriqe/FlowImage-Docs
- App principal: https://github.com/Rodriqe/FlowImage

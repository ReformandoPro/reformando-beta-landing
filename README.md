# Reformando beta landing (GitHub Pages)

Landing pública estática para `https://beta.reformando.pro/`.

## Contenido
- `index.html`
- `styles.css`
- `CNAME` (dominio custom)
- `.github/workflows/pages.yml` (deploy automático a GitHub Pages en cada push a `main`)

## Deploy
1. Push a `main`
2. GitHub Actions ejecuta **Deploy GitHub Pages**
3. Publica la raíz del repo en GitHub Pages

## Dominio
Este repo incluye `CNAME` con:

- `beta.reformando.pro`

> No cambiar DNS en OVH hasta que la Pages URL temporal funcione y el workflow esté en verde.

## DNS (cuando toque)
Cambiar en OVH:
- Actual: `beta.reformando.pro` → `A 2.24.11.119`
- Nuevo recomendado: `beta` → `CNAME reformandopro.github.io`

## CTA
El CTA usa:
- `mailto:hola@reformando.pro?subject=Acceso%20beta%20Reformando`

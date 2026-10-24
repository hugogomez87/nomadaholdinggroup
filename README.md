# Nomada Arquitectura

Sitio estático (HTML). Sin build.

## Flujo
1. Editar archivos (Claude Code).
2. `git add -A && git commit -m "cambio" && git push`
3. GitHub Pages publica automáticamente desde `main` (carpeta raíz).

## GitHub Pages
- Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)`
- URL: https://hugogomez87.github.io/nomadaholdinggroup/

## Dominio propio (GoDaddy)
1. Crear archivo `CNAME` en la raíz con el dominio (una línea).
2. DNS en GoDaddy:
   - Apex: 4 registros `A` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `www`: `CNAME` → `hugogomez87.github.io`
3. Settings → Pages → Custom domain y activar Enforce HTTPS.

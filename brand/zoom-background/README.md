# Fundo de reunião (Zoom / Meet / Teams)

- `tratto-zoom-bg-dark.png` e `tratto-zoom-bg-light.png` — 1920×1080, prontos pra usar.
- `background.html` — fonte editável. Cores ficam nas variáveis `:root` (tema escuro) e `html[data-theme="light"]`.
- `render.mjs` — gera os PNGs: `node render.mjs` (precisa de Playwright + Chromium).

Pra trocar tagline ou site, adicione no `background.html` antes de `</body>`:

```html
<div class="tag">Sua tagline</div>
<div class="corner">seusite.com.br</div>
```

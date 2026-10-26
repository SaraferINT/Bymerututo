# Landing ES — Abrir en navegador

Landing que se enseña desde el bio de TikTok. Detecta si el usuario está dentro de la app y, si no lo está, redirige automáticamente al artículo del blog.

## Estructura

```
.
├── index.html
└── videos/
    └── tutorial.mp4   (muted, autoplay, loop, playsinline)
```

## Editar destino

En `index.html`, línea del script superior:

```js
var target="https://trulu22gg.esbine.com/category/robux/";
```

La misma URL aparece también en el enlace del fallback `.redir-box` (`<a href="…">Continuar</a>`): cámbiala en los dos sitios si quieres apuntar a otra parte.

## Deploy

Settings → Pages → Source: `main` / root. URL: `https://usuario.github.io/<repo>/`.

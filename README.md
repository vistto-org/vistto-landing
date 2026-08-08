# vistto-landing

Landing pública de Vistto — `https://vistto.store`.

Página única de presencia de marca: identidad, tagline y los dos canales de
contacto (Instagram y WhatsApp). **Sin datos internos**: es el único sitio de
Vistto que no lleva autenticación.

## Deploy

Cloudflare Pages, proyecto `vistto-landing`, cuenta Abreurjg.

```bash
CLOUDFLARE_API_TOKEN=<token> npx wrangler pages deploy . --project-name=vistto-landing
```

Las tipografías de marca van empotradas en el HTML, así que la página no
depende de ningún CDN externo y se ve igual sin conexión a Google Fonts.

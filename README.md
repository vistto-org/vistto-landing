# vistto-landing

Landing pública de **Vistto** — bisutería fina y accesorios de moda.

<https://vistto.store>

Página única de presencia de marca: identidad, tagline y canales de contacto.
Las tipografías van empotradas en el HTML, así que no depende de ningún CDN.

## Estructura

```
public/index.html   lo único que se publica
```

Sólo se despliega `public/`. Nota: en Cloudflare Pages los archivos servidos una
vez quedan accesibles aunque un deploy posterior los excluya, así que fuera de
`public/` no debe ponerse nada que no pueda ser público.

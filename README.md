# IA para Pymes v1
Sitio estático sin dependencias. `node build.js` → genera `dist/`.
Mantener (agente): editar `data/tools.csv` (id|nombre|url|categoría|descripción|plan gratis si/no), datos verificados en `data/tools-verificadas.json` (clave = id) (precio, espanol, tarjetaAR, afiliado, actualizado), `data/casos.json`, `data/comparativas.json`, `data/categories.json`.
Newsletter: `config.json > newsletter.action` (endpoint Beehiiv/Buttondown/ConvertKit). Destacado: `config.json > destacado = {name,url,text}`.

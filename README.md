# nrcosta.com

Site institucional da NR Costa Tecnologia, publicado pelo GitHub Pages (branch `main`, raiz; domínio em `CNAME`). Todo merge na `main` publica o site em poucos minutos.

## Estrutura
- `index.html` — página única em HTML estático, com o CSS no próprio arquivo. Sem JavaScript.
- `assets/fonts/` — Manrope, Space Grotesk e JetBrains Mono (woff2, por subconjunto de caracteres).
- `assets/logo.png` (para fundo claro) e `assets/logo-claro.png` (para fundo escuro).
- `favicon.ico`, `favicon.png`, `icon-32.png`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` — monograma "NR" sobre azul-marinho (#27364D).
- `og-image.png` — imagem de prévia ao compartilhar o link (1200×630).
- `404.html`, `robots.txt`, `sitemap.xml`.

## Convenções
- Cores: fundo `#F6F3EC`, azul-marinho `#27364D`, verde `#4EB088`.
- Ao mudar a URL ou o título, atualizar também as tags `og:*`, `twitter:*`, `canonical` e o JSON-LD no `<head>` do `index.html`, e a data em `sitemap.xml`.
- Ícones e `og-image.png` são derivados do logo; se o logo mudar, gerar de novo.

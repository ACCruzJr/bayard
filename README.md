# Bayard — Site estático (pronto para publicar)

## Como publicar rápido
**Opção 1 — Netlify (1 clique)**
1. Acesse https://app.netlify.com/drop e *arraste* a pasta `bayard_site/` (ou o zip).
2. Copie a URL gerada. Depois, em **Site settings → Domain management**, conecte seu domínio.

**Opção 2 — Vercel**
1. Crie um projeto **Static** e faça upload da pasta. Não precisa build.
2. Aponte seu domínio.

**Opção 3 — GitHub Pages**
1. Envie esta pasta para um repositório.
2. Em **Settings → Pages**, selecione o branch e a pasta raiz `/`.

> O formulário já vem com suporte a **Netlify Forms** (sem backend). No Netlify, os envios aparecerão em *Forms* automaticamente.

## Estrutura
- `index.html` — página única com seções (Hero, Serviços, Sobre, Diferenciais, Contato).
- `styles.css` — visual neutro, minimalista e responsivo.
- `script.js` — menu mobile e rolagem suave.
- `assets/bayard_mark.svg` — símbolo vetorial (libélula).
- `assets/bayard_lockup_dark.svg` — lockup/hero vetorial.
- `robots.txt` e `sitemap.xml` — SEO básico.

## Personalizações rápidas
- **E-mail do botão** (Contato via e-mail): edite o `mailto:` no `index.html`.
- **Domínio do sitemap**: altere a URL em `robots.txt` e `sitemap.xml`.
- **Paleta**: ajuste variáveis em `:root` no `styles.css`.

## Dicas
- Para favicon, você pode usar o `assets/bayard_mark.svg` (já apontado em `<link rel="icon">`).
- Se a gráfica precisar de PDFs, exporte o SVG em PDF diretamente pelo Figma/Illustrator.

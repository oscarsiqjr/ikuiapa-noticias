# Ikuiapá Notícias — site estático

Export do design (Claude Design) pronto pra servir como site estático,
por exemplo no GitHub Pages.

## Como publicar no GitHub Pages

1. Suba TODO o conteúdo desta pasta pra raiz do repositório (substitua o
   que já está lá: o `Main-html.zip` solto e os arquivos soltos antigos
   podem ser removidos).
2. No GitHub, vá em **Settings → Pages**.
3. Em "Build and deployment", escolha **Source: Deploy from a branch**,
   branch **main**, pasta **/ (root)**.
4. Salve. Em um ou dois minutos o site fica no ar em
   `https://oscarsiqjr.github.io/ikuiapa-noticias/`.

## Arquivos

- `index.html` — a página (cópia de `Main.dc.html`, pra servir na raiz).
- `Main.dc.html` — o artboard original do Claude Design (mantido por
  referência).
- `assets/` — os ícones (Instagram, WhatsApp, e-mail).
- `support.js`, `vendor/` — runtime que renderiza a página.
- `.nojekyll` — avisa o GitHub Pages pra não processar o site com Jekyll
  (senão alguns arquivos podem ser ignorados).

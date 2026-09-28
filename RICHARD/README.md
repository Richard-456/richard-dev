# Richard.dev — site de apresentação

Landing page de uma página só para os serviços de desenvolvimento web freelancer
(Cambuí-MG). HTML e CSS puros, sem build e sem dependências.

## Arquivos

- `index.html` — o site inteiro: estrutura, estilos (a maioria inline, em
  `style="…"`) e um pequeno script para o menu mobile.
- `img/` — prints dos projetos do portfólio.
- `favicon.svg` — ícone da aba do navegador.
- `og-image.png` — imagem de prévia (1200×630) quando o link é compartilhado.
  Depois de publicar, troque `og:image` no `index.html` pela URL completa.

As imagens do design original ficam fora desta pasta, em `../Richard-design/`,
para não serem publicadas junto com o site.

## Seções

Header · Hero · Serviços · Como funciona · Portfólio · Preços (3 planos +
faixa de manutenção) · FAQ · Contato · Rodapé

## Responsividade

- até 1280px: margens laterais menores
- até 900px: menu vira hambúrguer, títulos diminuem
- até 640px: faixa de manutenção empilha texto e botão
- até 480px / 380px: cabeçalho compacto para celulares pequenos

## Visualizar

Abra `index.html` direto no navegador. Para publicar, basta subir o
`index.html` em qualquer hospedagem estática (GitHub Pages, Netlify, Vercel).

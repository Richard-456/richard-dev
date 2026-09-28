# Richard.dev — site de apresentação

Landing page de uma página só para os serviços de desenvolvimento web freelancer.
HTML e CSS puros, sem build e sem dependências.

## Estrutura

```
index.html            o site inteiro (estrutura, estilos e o script do menu mobile)
assets/
  favicon.svg         ícone da aba do navegador
  og-image.png        prévia (1200×630) quando o link é compartilhado
  img/                prints dos projetos do portfólio
design/               mockup original do design (não é publicado)
.vercelignore         deixa design/ e este README fora do deploy
```

## Seções

Header · Hero · Serviços · Como funciona · Portfólio · Preços (3 planos +
faixa de manutenção) · FAQ · Contato · Rodapé

## Responsividade

- até 1280px: margens laterais menores
- até 1040px: menu vira hambúrguer
- até 900px: títulos diminuem
- até 640px: faixa de manutenção empilha texto e botão
- até 480px / 380px: cabeçalho compacto para celulares pequenos

## Visualizar e publicar

Abra `index.html` direto no navegador. Na Vercel, importe o repositório sem
configuração de build — a raiz já é o site.

Depois de publicar, troque o `og:image` no `index.html` pela URL completa
(ex.: `https://seu-site.vercel.app/assets/og-image.png`) para a prévia
aparecer no WhatsApp.

# A Seção Restrita - Acervo Digital

Modelagem de Sites Básicos

## Autores

Alan Campos Macena

## Como abrir a página

1. Baixe o ZIP e extraia em uma pasta.
2. Abra a pasta e dê dois cliques em `index.html`.

## Como foi feito

- **Pastas:** `index.html` é a página, `css/style.css` guarda os estilos, `img/` guarda as capas e o fundo, e `capturas/` guarda os prints do computador e do celular.
- **HTML:** usei tags semânticas (`header`, `nav`, `main`, `section`, `article` e `footer`). A página tem cabeçalho com menu, destaque, busca com categorias, catálogo com 8 obras e rodapé.
- **CSS:** os estilos ficam em um arquivo externo, com as cores e as fontes definidas em variáveis. O Flexbox organiza o menu e o catálogo, e os cards passam para a próxima linha quando a tela diminui.
- **Celular:** uma media query deixa 2 cards por linha em telas pequenas. Testei em 1366 px e 390 px, sem rolagem horizontal.
- **Botões:** a página não usa JavaScript. Os botões e os filtros são só visuais, e os links do menu levam às seções da própria página.

## Fontes das imagens

- Capas das 8 obras (pasta `img/`): geradas com IA (Claude, da Anthropic), sem uso de capas oficiais.
- Imagem de fundo da estante (`img/fundo-estante.jpg`): gerada com IA (Claude, da Anthropic).

# Página de captura — modelo (HTML/CSS)

Recriação fiel da estrutura de uma landing page de captura (feita originalmente em Elementor/WordPress), em HTML e CSS puros, com textos genéricos e placeholders no lugar das imagens.

- `index.html` — página completa (desktop e mobile), um único arquivo.
- Paleta dourada sobre fundo escuro, cards com acabamento *liquid glass*.
- Ícones inline do [Lucide](https://lucide.dev) (ISC) e WhatsApp do [Simple Icons](https://simpleicons.org) (CC0).
- Scroll suave com [Lenis](https://lenis.dev).
- Fonte: Inter (Google Fonts). O modelo original usa Neue Haas Grotesk; basta trocar em `--font`.

## Imagens

As áreas tracejadas são placeholders com as medidas de exportação. Para o hero e a seção de entregas, a arte é o fundo inteiro da seção e os textos ficam em HTML por cima. No CSS há comentários indicando onde apontar as imagens (`background:url(...)`).

## Rodar

Abra o `index.html` no navegador ou sirva a pasta com qualquer servidor estático:

```bash
python3 -m http.server 8765
```

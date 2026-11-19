# Liquid Glass Logo Studio

Versão estática para GitHub Pages, baseada no componente Liquid Glass de StarKnightt (licença MIT): https://github.com/StarKnightt/liquid-glass

## Recursos
- Efeito WebGL2 com refração, ampliação, aberração cromática, brilho e ondulações.
- Fundo claro com luz ambiente e cores pastéis em movimento.
- Envio de logo em PNG, JPG, WebP ou SVG.
- Alternância entre lente circular e quadrado arredondado.
- Exportação PNG com transparência fora da silhueta selecionada.
- Manifesto PWA e service worker para instalação na tela inicial.

## Publicar no GitHub Pages
1. Extraia o ZIP.
2. Envie todos os arquivos e pastas para a raiz de um repositório público.
3. Em Settings → Pages, selecione Deploy from a branch, branch `main` e pasta `/ (root)`.
4. Abra o endereço HTTPS publicado.
5. No iPhone, Safari → Compartilhar → Adicionar à Tela de Início.

Observação: o efeito requer WebGL2. A exportação PNG recorta a composição renderizada na silhueta escolhida; o arquivo mantém transparência ao redor do ícone. A imagem exportada usa a resolução atual do canvas (até 2x o pixel ratio do dispositivo).

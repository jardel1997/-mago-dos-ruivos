MAGOS DOS RUIVOS — PROJETO WEBSITE

Arquivo principal:
- index.html

Este é um site estático de página única. As imagens do projeto estão embutidas no HTML.
O site usa recursos externos via CDN para GSAP, ScrollTrigger, Three.js e fontes Google.
Portanto, para a experiência completa, é necessária conexão à internet.

Para publicar no Cloudflare Pages:
1. Descompacte este arquivo ZIP.
2. Envie a pasta do projeto ou o index.html para o Cloudflare Pages (upload direto de assets estáticos).
3. Se for usar o método de upload de arquivos, mantenha index.html na raiz.

ATUALIZAÇÃO (Premium UI Motion Engine):
- prefers-reduced-motion agora funciona de verdade (CSS e JS); quem pede menos movimento recebe a versão estática.
- Animações só com opacity/transform, easing de desaceleração e durações curtas em elementos de UI.
- Faixas de tons sem animar layout; hover só em dispositivos com mouse; toque ativa a faixa no celular.
- Feedback de pressão nos botões, revelação ao rolar, FAQ/serviços com fade de entrada.
- Galeria pausa fora da tela e usa delta-time (mesma velocidade em 60/120 Hz).
- Menu mobile mais rápido e com trava de rolagem.
- Pendente: preencher CONFIG (whatsapp, instagram, facebook, tiktok) no script, senão os botões ficam desativados.

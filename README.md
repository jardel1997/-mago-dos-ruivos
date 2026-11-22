# Maggo dos Ruivos

Site do **Mago dos Ruivos — Nilson Gonçalves**, especialista em cabelos ruivos nos Jardins, São Paulo.

- Rua Estados Unidos, 273 — Jardins, São Paulo/SP
- Instagram: [@nilsongoncalvezz](https://www.instagram.com/nilsongoncalvezz)
- TikTok: [@nilsongoncalvezz](https://www.tiktok.com/@nilsongoncalvezz)

## Estrutura

```
index.html   → o site inteiro (HTML, CSS, JS e imagens em um único arquivo)
.nojekyll    → faz o GitHub Pages servir o arquivo como está
.gitignore   → arquivos ignorados pelo Git
```

## Como publicar

**Cloudflare Pages:** Workers & Pages → Create → Pages → Connect to Git → escolha este repositório.
Deixe o comando de build vazio e o diretório de saída como `/` (raiz).

**GitHub Pages:** Settings → Pages → Branch `main` → pasta `/ (root)` → Save.

## Como atualizar

Troque o `index.html` por um novo e faça o commit. A publicação é automática.

## Configurações

No fim do `index.html`, procure por `CONFIG` para alterar WhatsApp, Instagram, TikTok e Facebook.

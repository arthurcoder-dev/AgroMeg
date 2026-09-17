# Agro Meg — Site (multi-página, com pastas)

Site institucional responsivo para a Agro Meg, dividido em páginas
reais (sem `href="#"`), agora organizadas em pastas por seção.

## Estrutura

```
index.html                 → página inicial
categorias/index.html      → categorias de produtos
sobre/index.html           → sobre a loja
galeria/index.html         → galeria de fotos (com zoom/lightbox)
localizacao/index.html     → endereço, horários, contato e mapa
style.css                  → estilos (compartilhado por todas as páginas)
script.js                  → menu mobile e galeria ampliável (compartilhado)
assets/                    → fotos, logo e favicon
```

Cada página interna fica em sua própria pasta com o nome da seção
(ex.: `categorias/index.html`), então a URL final fica limpa, por
exemplo `seusite.com/categorias/` em vez de `seusite.com/categorias.html`.
Só a página inicial continua como `index.html` na raiz.

## Identidade visual

- Logo: `assets/logo.png` (usado no cabeçalho e no rodapé de todas as páginas)
- Favicon: `assets/favicon.png` (32×32), com versões extras em
  `assets/favicon-512.png` e `assets/apple-touch-icon.png` (180×180)
  para ícones de tela inicial em celulares.

## Navegação

O menu do cabeçalho e o rodapé apontam para os arquivos reais dentro
das pastas (`../categorias/index.html`, `../sobre/index.html`, etc.,
quando o link parte de dentro de uma subpasta). Nenhum link usa mais
`href="#secao"`.

## Como abrir

1. Abra esta pasta no VS Code (ou extraia o .zip).
2. Abra `index.html` no navegador ou use o Live Server.
3. Para publicar, a pasta pode ser enviada para GitHub Pages, Netlify,
   Vercel ou outro serviço de hospedagem estática — a estrutura de
   pastas já funciona como URLs limpas nesses serviços.

## Informações usadas

- Nome: Agro Meg
- Endereço: Rua 18, Quadra 26, Lote 33 — Lojas 1 e 2, Jardim Oriente, Valparaíso de Goiás — GO, 72870-261
- Telefone/WhatsApp: (61) 99809-1799
- Horários apresentados no site: conforme dados disponíveis no perfil da empresa consultado em 16/09/2026.

## Observação

Os preços e a disponibilidade de produtos não foram colocados no site,
porque podem mudar. O botão do WhatsApp direciona o cliente para
confirmar disponibilidade e informações antes da visita.

# Marca Sankler

O símbolo é o **Canhoto**: o bloco do talão de ordem de serviço, destacado no picote, com o S vazado. O nome é **Sankler**, com a primeira letra maiúscula. Todos os arquivos estão em contornos e não dependem de fonte instalada.

## Arquivos

| Arquivo | Uso |
|---|---|
| `sankler-logo-fundo-escuro.svg` | Logo com o nome, sobre fundo escuro (o padrão) |
| `sankler-logo-fundo-claro.svg` | Logo com o nome, sobre fundo claro (documentos, PDFs, impressos) |
| `sankler-logo-branco.svg` / `sankler-logo-preto.svg` | Uma cor só: branco sobre azul ou foto; preto para impressão em uma cor |
| `sankler-logo-reduzido-*.svg` | As mesmas quatro versões com o símbolo reduzido, para logos com menos de 305 px de largura: documentos, assinatura de e-mail, rodapés |
| `sankler-simbolo.svg` | Símbolo a partir de 48 px |
| `sankler-simbolo-reduzido.svg` | Símbolo abaixo de 48 px (favicon, cabeçalho): 3 picotes maiores e S maior |
| `sankler-simbolo-branco.svg` / `sankler-simbolo-preto.svg` | Símbolo em uma cor só |
| `sankler-avatar-1024.png` | Foto de perfil (GitHub, LinkedIn, WhatsApp, e-mail): símbolo reduzido a 66%, cabe no recorte redondo |
| `icon-192.png`, `icon-512.png`, `icon-maskable-512.png` | Ícone de app e PWA; a versão maskable já tem a margem de segurança do Android |

O favicon do site (`/favicon.svg` e `/favicon.ico`) usa o símbolo reduzido. O `/apple-touch-icon.png` (180 px) usa o símbolo principal.

## Cores

| Nome | Hex | Uso |
|---|---|---|
| Azul caneta | `#3a63ff` | Símbolo, botão principal, linhas da grade |
| Azul de texto | `#6382ff` | Texto azul sobre o preto (rótulos, números, links) |
| Preto | `#0b0c10` | Fundo padrão |
| Branco | `#f2f3f7` | Texto principal e carimbos sobre o preto |
| Branco puro | `#ffffff` | Texto sobre o azul caneta (botões) e as versões brancas do logo |
| Cinza | `#a6abbb` | Texto de apoio sobre o preto |

O tema escuro é o padrão. O azul caneta tem contraste 4,1:1 sobre o preto e 4,8:1 com o branco puro por cima (o branco `#f2f3f7` sobre o azul fica em 4,3:1 e não serve para texto pequeno). Para texto azul pequeno sobre o preto, use o azul de texto (5,7:1).

O S do símbolo é vazado: mostra o fundo que estiver atrás (preto no site, branco num documento claro).

## Tipografia

Archivo (licença OFL, `../fonts/`).

- Nome e títulos: peso 800, largura 118%, espaçamento -0,01em.
- Rótulos: maiúsculas, peso 650, largura 75%, espaçamento 0,09em, no azul de texto.
- Texto corrido: peso 400, largura 100%, entrelinha 1,6.

## Regras de uso

- Deixe em volta do logo um espaço livre de pelo menos 1/4 da largura do símbolo.
- Use o símbolo principal a partir de 48 px. Abaixo disso, e em logos com o nome com menos de 305 px de largura (ou 80 mm impressos), use as versões reduzidas.
- Tamanho mínimo do logo reduzido com o nome: 100 px de largura na tela ou 25 mm impresso.
- Não gire, não estique, não troque as cores, não aplique contorno, sombra ou degradê, e não reescreva o nome em outra fonte.
- Sobre foto ou sobre o azul, use a versão branca.

## Produtos: assinatura "por Sankler"

Cada produto mantém o próprio nome, símbolo e cores. A marca Sankler entra como assinatura, nunca no lugar da identidade do produto.

- **Onde:** no rodapé do produto (web e PWA), na tela "Sobre" do app e no README do repositório.
- **Onde não:** no conteúdo do usuário. Nada de assinatura em PDFs, exportações, notas ou mensagens que o produto gera para o cliente.
- **Forma:** a palavra "por" no texto do próprio produto, seguida do logo reduzido (`sankler-logo-reduzido-*.svg`) com 16 a 20 px de altura, com link para https://sankler.com.br. Para leitores de tela, o conjunto se chama "por Sankler".
- **Versão do arquivo:** `fundo-claro` em tema claro, `fundo-escuro` em tema escuro, `branco` ou `preto` sobre a cor do produto. Não pinte o logo com a cor do produto.
- **Arquivo local:** copie o SVG para dentro do repositório do produto e sirva do próprio domínio. Não carregue o logo de sankler.com.br, porque produtos offline e com CSP restrita (`img-src 'self'`) precisam do arquivo local, e assim a assinatura não faz nenhuma requisição a terceiros.

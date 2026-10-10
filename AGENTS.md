# sankler.com.br: instruções do projeto

Os padrões gerais (stack, versionamento e marca) estão em `C:/Users/sbtec/Documents/Github/padroes/PADROES.md`. Aqui fica só o que é deste site.

- Site estático em HTML e CSS, publicado pelo GitHub Pages: tudo o que está no repositório vai ao ar. Arquivos de ferramenta (`PRODUCT.md`, `DESIGN.md`, `.impeccable/`, notas `*.webp.json`) ficam fora do Git pelo `.gitignore`.
- Português em `/` e inglês em `/en/`. Toda mudança vale para as duas páginas.
- O site é sempre escuro. A marca Sankler mora em `assets/brand/`; este é o kit oficial e os outros projetos copiam os arquivos daqui.
- O único script é o snippet do Cloudflare Web Analytics. Sem cookies; o rodapé diz que as visitas são contadas, então não prometa "sem rastreadores".
- Versão: semver, conforme os padrões. Ela aparece no rodapé das duas páginas (`.version`) e ganha tag `vX.Y.Z` e release no GitHub. Mudança só de documentação não sobe versão.
- Publicar é fazer push na `main` (o Pages atualiza em cerca de um minuto). Confirme com o dono antes.

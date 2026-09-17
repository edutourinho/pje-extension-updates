# PJe Extension Updates

Infraestrutura pública de distribuição e atualização automática das extensões PJe.

Este repositório **não é o repositório de desenvolvimento**. Ele deve conter apenas arquivos públicos necessários à distribuição: manifests de atualização, página estática e pacotes XPI assinados pela Mozilla.

## Endpoints planejados

Depois que o GitHub Pages estiver habilitado para publicar a branch `main` a partir da raiz (`/`):

- OJ: `https://edutourinho.github.io/pje-extension-updates/oj/updates.json`
- Vara: `https://edutourinho.github.io/pje-extension-updates/vara/updates.json`

Os arquivos `updates.json` começam com a lista `updates` vazia. Portanto, publicar esta estrutura **não ativa nenhuma atualização**. Eles só devem apontar para um XPI depois que o arquivo estiver assinado pela Mozilla, disponível por HTTPS e testado.

## Habilitação inicial do GitHub Pages

No GitHub, abra **Settings → Pages** e, em **Build and deployment**, escolha **Deploy from a branch**, branch **main**, pasta **/(root)**. Como o conteúdo é estático, esse modo é mais simples do que manter um workflow específico de deployment.

## Estrutura

- `oj/updates.json` — manifesto público de atualizações da extensão dos OJs.
- `oj/releases/` — XPIs assinados destinados à extensão dos OJs.
- `vara/updates.json` — manifesto público de atualizações da extensão da Vara.
- `vara/releases/` — XPIs assinados destinados à extensão da Vara.
- `index.html` — página pública informativa.

## Segurança

Não publicar aqui código de backend, scripts de dados, HARs, logs, credenciais, cookies, tokens ou dados pessoais. O código-fonte de desenvolvimento fica no repositório privado `edutourinho/pje-browser-extensions`.

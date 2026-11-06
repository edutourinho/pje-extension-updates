# Política de Privacidade — Abridor de Processos PJe TRT1

**Última atualização:** 6 de novembro de 2026

O **Abridor de Processos — PJe TRT1** é uma extensão independente para Google Chrome que permite abrir, em lotes, URLs de processos judiciais fornecidas pelo próprio usuário em um arquivo CSV.

## Dados e funcionamento

O usuário escolhe um arquivo CSV armazenado no seu computador. A extensão lê localmente as linhas desse arquivo e utiliza as URLs válidas para solicitar ao Chrome a abertura de novas abas no domínio `pje.trt1.jus.br`.

As URLs são mantidas temporariamente na memória do painel durante a utilização. A extensão não mantém um banco de dados externo, não envia a lista a servidores do desenvolvedor e não incorpora serviços de publicidade ou análise de uso. Ao abrir uma URL, o Chrome se comunica normalmente com o site do PJe, sujeito às políticas do próprio serviço.

As URLs podem conter números de processos e identificadores de documentos. Por isso, recomenda-se utilizar apenas arquivos e endereços a que o usuário tenha acesso legítimo.

## Autenticação

O login no PJe é feito diretamente pelo usuário no navegador. A extensão não solicita nem lê senhas, certificados digitais, cookies ou tokens de autenticação. As abas abertas utilizam o funcionamento normal da sessão do Chrome.

## Permissões

A permissão **tabs** é utilizada para criar abas com os endereços escolhidos pelo usuário e para localizar ou reativar o painel da própria extensão. A extensão não extrai o conteúdo dos processos nem monitora a navegação fora dessa funcionalidade.

## Compartilhamento, venda e finalidades

O desenvolvedor não vende os dados dos usuários, não os compartilha com anunciantes e não os utiliza para publicidade, avaliação de crédito ou outras finalidades estranhas à abertura controlada de abas. Não há transmissão dos dados do CSV a servidores operados pelo desenvolvedor.

## Armazenamento e conservação

O arquivo CSV original permanece no computador do usuário. A lista carregada fica na memória da página da extensão enquanto o painel estiver aberto e não é gravada em armazenamento persistente pela extensão. As abas e o histórico de navegação seguem o comportamento normal do Chrome.

## Crianças e alterações

A extensão não é direcionada a crianças. Caso o funcionamento ou as práticas de tratamento de dados mudem, esta política será atualizada.

## Independência

Esta ferramenta não é um produto oficial nem é mantida pelo Tribunal Regional do Trabalho da 1ª Região. O PJe é um sistema de terceiros, com regras e políticas próprias.

## Contato

Questões sobre esta política podem ser encaminhadas ao mantenedor por meio do [repositório público de atualizações](https://github.com/edutourinho/pje-extension-updates/issues).

# curso-frontend

# Linguagem MD (Markdown)

Utilizado para criar documentação do seu projeto de forma rápida. Ao utilizar o MD o Git vai exibir o texto formatado.

# GIT

## Versionamento

- Histórico
- Controle de versão
- Quem alterou
- O que alterou
- Quando alterou
- Todos os arquivos
- Evolução contínua

Arquivo A | Versão 1
Arquivo B | Versão 2

## Instalação do Git

No linux: (apt-get): sudo apt-get install git
No Mac: (brew): brew install git
No Windows, linux e mac, pode baixar no site: https://git-scm.com/downloads

## Criar conta no GitHub

https://github.com
criar um repositório: curso-frontend

## Clonar o projeto

git clone https://github.com/elisangelarocha78/curso-frontend.git

## Commits

Informação de alteração

- após testado todo seu código
- git add \*
- git commit -m "mensagem"
- git push (enviar alterações para o repositório)
- git pull (trazer alterações do GitHub para sua maquina local)

## GitFlow

Fluxo do Git

## Branches

São ramificações / versões paralelas

- main / master (vai para produção quando o projeto é publicado)
- DOO - Definition of done (critérios de aceite)
- versionamento 1.0.0

Criar uma nova branche: dev

- git checkout -b dev (cria uma copia da branche "main" para nova branche "dev")

Siga os comandos:

- $ git status
- $ git add \*
- $ git commit -m "atualiza descricao com git flow"
- Antes de subir o código para branche master (main), verificar se tem alguma atualização nela:
- $ git fetch --all
- $ git merge main (Mescla de Branches)
- $ git merge push

Para trocar de Branche:

- $ git checkout main (para mudar de branche)
- $ git merge push (Se der msg de erro ele vai sugerir o código seguinte:)
- $ git push --set-upstream origin dev

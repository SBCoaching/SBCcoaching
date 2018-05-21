# SBCcoaching
Guia de utilização do GitHub SBCoaching

# SBCoaching - Guia básico de versionamento

[![N|Solid](https://d3ams2lk3yn2fs.cloudfront.net/img/sbcoaching.png)](https://www.sbcoaching.com.br)

Guia básico para versionamento e gestão de repositórios do GitHub.

  ***Criado por:** Fernando J Santos - fernando.santos@sbcoaching.com.br*

## Clonar repositório

Para clonar um novo repositório apenas digite os códigos abaixo:    

``
git clone [url-do-repositorio]
``
## Submeter alterações de arquivos

Para submeter as alterações dos arquivos, alguns passos precisarão serem seguidos:

1. Alterar arquivos
2. Adicionar alterações ao ***commit***
    - `git add --all`
3. Submeter alterações através comando ***commit*** 
    - `git commit -m "[mensagem-para-documentar-o-commit]"`
4. Sincronizar com arquivos publicados online
    - `git pull origin [nome-da-branch]`
5. Publicar alterações através do comando ***push***
    - `git push origin [nome-da-branch]`
6. Insira suas credenciais de acesso **(usuário e senha)** 

## Criar nova branch local

Para criar uma nova branch local siga os passos descritos abaixo:

`git checkout -b [nome-da-nova-branch]`

## Criar nova branch remota à partir de uma local

Para criar uma nova branch remota siga os passos descritos abaixo:

1. Crie uma nova branch local
    - `git checkout -b **[nome-da-nova-branch]**`
2. Altere os arquivos
3. Crie a nova branch remota com o comando abaixo
    - `git push origin **[nome-da-branch]**`

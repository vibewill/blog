+++
title = "Usando git"
date = 2021-01-21

[taxonomies]
categories = ["git"]
tags = ["Como usar o git"]
authors = ["Willian Ricardo"]
+++

Para passar a monitorar um novo arquivo, use o comando git add.  
> git add .  

A principal ferramenta utilizada para determinar quais arquivos estão em quais estados é o comando:  
>   git status  

<!-- more -->  
Armazena o conteúdo atual do índice em um novo commit, juntamente com uma mensagem de registro do usuário que descreve as mudanças.
Se usa o commit depois de já ter feito o git add, para fazer o commit:
> git commit -m "Mensagem"  

O git push é o comando em que você transfere commits a partir do seu repositório local para um repositório remoto. É a contrapartida do git fetch, que busca importações e comprometem as agências locais, utilizando o git push as exportações comprometem as filiais remotas. Para fazer isso, você executa git push [nome_do_repositório_remoto] [nome_da_sua_branch_local], que vai tentar fazer que o [nome_do_repositório_remoto] receba a sua branch [nome_da_sua_branch_local] contendo todos seus commits com alterações. Por exemplo:  
> git push origin master  

Salva usuario e senha permanente:  
> git config credential.helper store

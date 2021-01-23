+++
title = "Como remover uma entrada de boot UEFI obsoleta no Linux?"
date = 2021-01-23

[taxonomies]
categories = ["linux"]
tags = ["remover uma entrada de boot UEFI obsoleta"]
authors = ["Willian Ricardo"]
+++

Primeiramente vamos listar as opções que temos:  
> efibootmgr  

![Remover entrada uefi obsoleta](https://4fasters.com.br/wp-content/uploads/2017/10/image2-4.png)  
Veja que, a opção que eu quero deletar é a CentOS Linux, número 0000:  
<!-- more -->
> efibootmgr -b 0000 -B  

A opção -B informa que vamos deletar a opção definida pelo -b.


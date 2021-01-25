+++
title = "Resolver problemas de programas que pede autentificacão no wm"
date = 2021-01-25

[taxonomies]
categories = ["linux"]
tags = ["Autentificacão wm"]
authors = ["Willian Ricardo"]
+++

Parece que isso ocorre porque o agente de autenticação não está em execução.  
> sudo apt install policykit-1-gnome  

No caso do bspwm e so colocar esse comando no arquivo bspwmrc.  
> /usr/lib/policykit-1-gnome/polkit-gnome-authentication-agent-1  
<!-- more -->  

No i3wm no arquivo config.  
> exec /usr/lib/policykit-1-gnome/polkit-gnome-authentication-agent-1

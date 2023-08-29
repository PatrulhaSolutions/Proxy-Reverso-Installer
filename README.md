<h1 align="center">Gerador de Proxy Reverso | PSolutions</h1>

<div align="center">

[![Patrulha Solutions](https://img.shields.io/badge/site-psolutions-orange)](https://patrulhasolutions.com.br/) 
[![License](https://img.shields.io/badge/license-GPL--3.0-orange)](./LICENSE)


</div>
  
<div align="center"><img src="https://patrulhasolutions.com.br/wp-content/uploads/2022/04/cropped-logo-1.png"></div>

## Criando conteúdo necessário

1 - Crie o subdominio e aponte para o IP de sua VPS (ex. seudominio.com ->154.358.12.105).

2 - Em seu terminal, clone o reopsitório do Gitub:

    git clone https://github.com/PatrulhaSolutions/Proxy-Reverso-Installer.git

3 - no terminal coloque o comando a baixo:
    
    cd Proxy-Reverso-Installer/GerProxyPSolutions && chmod +x git-gerador_proxy_reverso.sh && ./git-gerador_proxy_reverso.sh

4 - O instalador irá pedir:

    4-1 - O domínio que você apontou para sua VPS: (seudominio.com)

    4-2 - O E-mail para a instalação do SSL: (precisa ser um email válido!)

    4-3 - Um nome para a o domínio: (somente letras minúsculas e sem espaços - Ex. nomeescolhido)
    
    4-4 - A porta para o apontamento: (ex. 8000)

## SSL

To install the SSL certificate, follow the **[instructions](https://certbot.eff.org/instructions?ws=other&os=ubuntufocal)** below.


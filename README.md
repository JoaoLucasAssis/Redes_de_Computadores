# Redes de Computadores I

Este repositório foi criado para armazenar as anotações do curso Redes de Computadores I - Introduction to Networks, da plataforma NetAcad da Cisco, cursado na disciplina de Redes de Computadores I, na Universidade Vila Velha. 

Nele estão registradas as notas sobre os módulos ensinados em sala de aula, bem como sobre os módulos adicionais que, embora não abordados diretamente no semestre, foram estudados para o exame final e a obtenção do certificado de conclusão. 

As anotações incluem pontos-chave dos temas discutidos, destacando partes importantes e grifando palavras-chave essenciais para facilitar o estudo e a revisão.

# Sumário

<details>
 <summary>Introdução às Redes</summary>
<ul>
    <li><a href="#componentes-de-rede">Componentes de rede</a>
        <ul>
            <li><a href="#host">Host</a></li>
            <li><a href="#dispositivos-finais">Dispositivos finais</a></li>
            <li><a href="#dispositivos-intermediários">Dispositivos intermediários</a></li>
            <li><a href="#meios-de-rede">Meios de rede</a></li>
        </ul>
    </li>
    <li><a href="#representações-e-topologias-de-rede">Representações e topologia de rede</a>
        <ul>
            <li><a href="#representações-de-rede">Representações de rede</a></li>
            <li><a href="#diagrama-de-topologia">Diagrama de topologia</a></li>
        </ul>
    </li>
    <li><a href="#tipos-comuns-de-rede">Tipos comuns de rede</a>
        <ul>
            <li><a href="#lan">LAN</a></li>
            <li><a href="#wan">WAN</a></li>
        </ul>
    </li>
</ul>
</details>

<details>
<summary>Switch Básico</summary>
<ul>
    <li><a href="#sistema-operacional">Sistema operacional</a>
        <ul>
            <li><a href="#métodos-de-acesso">Métodos de acesso</a></li>
        </ul>
    </li>
    <li><a href="#comandos-primários">Comandos básicos</a>
        <ul>
            <li><a href="#modo-de-configuração">Modo de configuração</a></li>
            <li><a href="#navegação-entre-os-modos-do-ios">Navegação entre os modos do IOS</a></li>
            <li><a href="#resumo">Resumo</a></li>
        </ul>
    </li>
    <li><a href="#configuração-básica-de-dispositivos">Configuração básica de dispositivos</a>
        <ul>
            <li><a href="#nomes-de-dispositivo">Nomes de dispositivos</a></li>
            <li><a href="#configurar-senhas">Configurar senhas</a></li>
            <li><a href="#criptografar-senhas">Criptografar senhas</a></li>
            <li><a href="#mensagens-de-banner">Mensagens de banner</a></li>
            <li><a href="#arquivos-de-configuração">Arquivos de configuração</a></li>
        </ul>
    </li>
    <li><a href="#endereço-ip">Endereço IP</a></li>
    <li><a href="#interfaces-e-portas">Interfaces e portas</a>
        <ul>
            <li><a href="#configuração-manual-de-ip">Configuração manual de IP</a></li>
            <li><a href="#configuração-automática-de-ip">Configuração automática de IP</a></li>
        </ul>
    </li>
    <li><a href="#configuração-da-interface-virtual-do-switch">Configuração da interface virtual do Switch</a></li>
</ul>
</details>

<details>
<summary>Protocolos e Modelos</summary>
<ul>
    <li><a href="#as-regras">As regras</a>
        <ul>
            <li><a href="#codificação-de-mensagens">Codificação de mensagens</a></li>
            <li><a href="#formatação-e-encapsulamento-de-mensagens">Formatação e encapsulamento de mensagens</a></li>
            <li><a href="#tamanho-da-mensagem">Tamanho da mensagem</a></li>
            <li><a href="#temporização-da-mensagem">Temporização da mensagem</a></li>
            <li><a href="#opções-de-envio-de-mensagem">Opções de envio de mensagem</a></li>
        </ul>
    </li>
    <li><a href="#protocolos">Protocolos</a>
        <ul>
            <li><a href="#funções-de-protocolos">Funções de protocolos</a></li>
            <li><a href="#conjunto-de-protocolos">Conjunto de protocolos</a></li>
        </ul>
    </li>
    <li><a href="#modelos-de-camadas">Modelos de camadas</a>
        <ul>
            <li><a href="#osi">OSI</a></li>
            <li><a href="#tcpip">TCP/IP</a></li>
            <li><a href="#comparações">Comparações</a></li>
        </ul>
    </li>
    <li><a href="#encapsulamento-de-dados">Encapsulamento de dados</a>
        <ul>
            <li><a href="#segmentação">Segmentação</a></li>
            <li><a href="#sequenciamento">Sequenciamento</a></li>
        </ul>
    </li>
</ul>
</details>

<details>
<summary>Camada Física</summary>
<ul>
    <li><a href="#visão-geral">Visão geral</a>
        <ul>
            <li><a href="#componentes-físicos">Componentes físicos</a></li>
            <li><a href="#codificação">Codificação</a></li>
            <li><a href="#sinalização">Sinalização</a></li>
        </ul>
    </li>
    <li><a href="#largura-de-banda">Largura de banda</a></li>
</ul>
</details>

<details>
<summary>Camada de Enlace de Dados</summary>
<ul>
    <li><a href="#conceitos-gerais">Conceitos gerais</a></li>
    <li><a href="#subcamadas">Subcamadas</a>
        <ul>
            <li><a href="#llc">LLC</a></li>
            <li><a href="#mac">MAC</a></li>
        </ul>
    </li>
    <li><a href="#topologias">Topologias</a>
        <ul>
            <li><a href="#ponto-a-ponto">Ponto a ponto</a></li>
            <li><a href="#barramento">Barramento</a></li>
            <li><a href="#estrela">Estrela</a></li>
            <li><a href="#anel">Anel</a></li>
            <li><a href="#malha">Malha</a></li>
            <li><a href="#árvore">Árvore</a></li>
            <li><a href="#híbrida">Híbrida</a></li>
        </ul>
    </li>
    <li><a href="#comunicação">Comunicação</a>
        <ul>
            <li><a href="#half-duplex">Half-duplex</a></li>
            <li><a href="#full-duplex">Full-duplex</a></li>
        </ul>
    </li>
    <li><a href="#métodos-de-controle-de-acesso">Métodos de controle de acesso</a>
        <ul>
            <li><a href="#acesso-baseado-em-controle">Acesso baseado em controle</a></li>
            <li><a href="#acesso-baseado-em-contenção">Acesso baseado em contenção</a></li>
        </ul>
    </li>
    <li><a href="#quadros">Quadros</a>
        <ul>
            <li><a href="#detecção-de-erros">Detecção de erros</a></li>
            <li><a href="#endereços-mac">Endereços MAC</a></li>
        </ul>
    </li>
</ul>
</details>

<details>
<summary>Switching Ethernet</summary>
<ul>
    <li><a href="#definição">Definição</a></li>
    <li><a href="#quadro-ethernet">Quadro Ethernet</a>
        <ul>
            <li><a href="#processamento-de-quadros-ethernet">Processamento de quadros Ethernet</a></li>
        </ul>
    </li>
    <li><a href="#endereço-mac">Endereço MAC</a>
        <ul>
            <li><a href="#endereço-mac-unicast">Endereço MAC unicast</a></li>
            <li><a href="#endereço-mac-multicast">Endereço MAC multicast</a></li>
            <li><a href="#endereço-mac-broadcast">Endereço MAC broadcast</a></li>
        </ul>
    </li>
    <li><a href="#tabela-de-endereçamentos-mac">Tabela de endereçamentos MAC</a>
        <ul>
            <li><a href="#aprendizado">Aprendizado</a></li>
            <li><a href="#encaminhamento">Encaminhamento</a></li>
        </ul>
    </li>
</ul>
</details>

<details>
<summary>Camada de Rede</summary>
<ul>
    <li><a href="#fundamentos">Fundamentos</a></li>
    <li><a href="#endereçamento">Endereçamento</a></li>
    <li><a href="#encapsulamento">Encapsulamento</a></li>
    <li><a href="#ip">IP</a>
        <ul>
            <li><a href="#ipv4">IPv4</a></li>
            <li><a href="#ipv6">IPv6</a></li>
        </ul>
    </li>
    <li><a href="#roteamento">Roteamento</a>
        <ul>
            <li><a href="#gateway-padrão">Gateway padrão</a></li>
            <li><a href="#tabela-de-roteamento">Tabela de roteamento</a></li>
            <li><a href="#roteamento-estático">Roteamento estático</a></li>
            <li><a href="#roteamento-dinâmico">Roteamento dinâmico</a></li>
        </ul>
    </li>
</ul>
</details>

<details>
 <summary>Roteador básico</summary>
<ul>
    <li><a href="#comandos-básicos">Comandos primários</a>
        <ul>
            <li><a href="#modo-de-configuração">Modo de configuração</a></li>
            <li><a href="#navegação-entre-os-modos-do-ios">Navegação entre os modos do IOS</a></li>
            <li><a href="#resumo">Resumo</a></li>
        </ul>
    </li>
    <li><a href="#configuração-primária-do-roteador">Configuração primária do roteador</a>
        <ul>
            <li><a href="#nome-do-roteador">Nome do roteador</a></li>
            <li><a href="#configurar-senhas-do-roteador">Configurar senhas do roteador</a></li>
            <li><a href="#criptografar-senhas-do-roteador">Criptografar senhas do roteador</a></li>
            <li><a href="#mensagens-de-banner-do-roteador">Mensagens de banner do roteador</a></li>
        </ul>
    </li>
    <li><a href="#configuração-das-interfaces-do-roteador">Configuração das interfaces do roteador</a>
        <ul>
            <li><a href="#verificação-da-configuração">Verificação da configuração</a></li>
        </ul>
    </li>
    <li><a href="#configuração-do-gateway-padrão-do-roteador">Configuração do gateway padrão do roteador</a>
        <ul>
            <li><a href="#gateway-padrão-em-um-switch">Gateway padrão em um switch</a></li>
        </ul>
    </li>
</ul>
</details>

<details>
    <summary>Endereçamento IPv4</summary>
    <ul>
        <li><a href="#estrutura">Estrutura</a></li>
        <li><a href="#máscara-de-sub-rede">Máscara de sub-rede</a></li>
        <li><a href="#comprimento-do-prefixo">Comprimento do prefixo</a></li>
        <li><a href="#tipos-de-endereços-ipv4">Tipos de endereço IPv4</a>
            <ul>
                <li><a href="#ipv4-privados-e-públicos">IPv4 públicos e privados</a></li>
                <li><a href="#endereços-de-loopback">Endereços de loopback</a></li>
            </ul>
        </li>
        <li><a href="#nat">NAT</a></li>
        <li><a href="#segmentação-de-rede">Segmentação de rede</a>
            <ul>
                <li><a href="#sub-redes-ipv4">Sub-redes IPv4</a></li>
                <li><a href="#vlsm">VLSM</a></li>
            </ul>
        </li>
        <li><a href="#limitações">Limitações</a></li>
    </ul>
</details>

<details>
 <summary>Endereçamento IPv6</summary>
<ul>
    <li><a href="#formato">Formato</a>
        <ul>
            <li><a href="#omitir-zeros-à-esquerda">Omitir zeros à esquerda</a></li>
            <li><a href="#dois-pontos-duplos">Dois pontos duplos</a></li>
        </ul>
    </li>
    <li><a href="#comprimento-do-prefixo">Comprimento do prefixo</a></li>
    <li><a href="#tipos-de-endereço-ipv6">Tipos de endereço IPv6</a>
        <ul>
            <li><a href="#unicast">Unicast</a></li>
            <li><a href="#multicast">Multicast</a></li>
        </ul>
    </li>
    <li><a href="#slaac">SLAAC</a></li>
    <li><a href="#sub-redes-ipv6">Sub-redes IPv6</a></li>
</ul>
</details>

<details>
 <summary>Camada de Transporte</summary>
<ul>
    <li><a href="#propósito">Propósito</a></li>
    <li><a href="#tcp">TCP</a>
        <ul>
            <li><a href="#recursos-tcp">Recursos</a></li>
            <li><a href="#cabeçalho-tcp">Cabeçalho</a></li>
            <li><a href="#remontagem-tcp">Transmissão</a></li>
            <li><a href="#handshake">Handshake</a></li>
            <li><a href="#controle-de-fluxo">Controle de fluxo</a></li>
        </ul>
    </li>
    <li><a href="#udp">UDP</a>
        <ul>
            <li><a href="#recursos-udp">Recursos</a></li>
            <li><a href="#cabeçalho-udp">Cabeçalho</a></li>
            <li><a href="#remontagem-udp">Transmissão</a></li>
        </ul>
    </li>
    <li><a href="#portas">Portas</a>
        <ul>
            <li><a href="#socket">Socket</a></li>
        </ul>
    </li>
</ul>
</details>

# Componentes de rede

As redes de computadores são compostas por vários elementos que permitem a comunicação e a troca de dados entre dispositivos. Os principais componentes de uma rede incluem hosts, dispositivos finais, dispositivos intermediários e meios de rede. 

Esses elementos trabalham juntos para assegurar a conectividade e o fluxo eficiente de informações.

## Host

Se você quiser fazer parte de uma comunidade on-line global, seu computador, tablet ou smartphone deve primeiro estar conectado a uma rede e essa rede deve estar conectada à Internet.

Todos os computadores que estão conectados a uma rede e participam diretamente da comunicação em rede são classificados como `hosts`.

Os `hosts` podem ser chamados de dispositivos finais. Alguns hosts também são chamados de **clients**. No entanto, o termo hosts refere-se especificamente a dispositivos na rede que recebem um **número** para fins de comunicação.

Este **número** identifica o host dentro de uma rede específica. Este número é chamado de endereço `IP`. 

Um endereço `IP` identifica o host e a rede à qual o host está conectado.

### Servidores e clients

`Servidores` são computadores com softwares que lhes permitem fornecer informações, como e-mail ou páginas da Web, para outros dispositivos finais na rede.

Cada serviço ofericido exige um **software de servidor** separado (Apache, MySQL, Microsoft Exchange). Um servidor com software de servidor pode fornecer serviços simultaneamente a muitos **clients** diferentes.

Os **clients** são um tipo de host. Eles possuem softwares para solicitar e exibir as informações obtidas do `servidor`.

Um exemplo de **software cliente** é um navegador, como Chrome ou FireFox. Um único computador pode também executar vários tipos de software cliente.

### Redes ponto a ponto

O **software cliente** e o **servidor** geralmente são executados em computadores separados, mas também é possível que um computador seja usado para ambas as funções ao mesmo tempo. 

Em pequenas empresas e em casas, muitos computadores funcionam como `servidores` e `clients` na rede.

Esse tipo de rede é chamado de `rede ponto a ponto`.

## Dispositivos finais

OS `dispositivos finais` são os dispositivos que os usuários utilizam diretamente para interagir com a rede. Eles são chamados de "finais" porque representam o ponto final na comunicação dentro da rede, ou seja, onde a comunicação começa ou termina.

Para distinguir um dispositivo final de outro, cada dispositivo final em uma rede tem um **endereço**. O endereço `IP` é o tipo de endereço mais comum que os dispositivos finais usam em redes baseadas na internet.

Quando um dispositivo final inicia a comunicação, ele usa o endereço `IP` do **dispositivo final de destino** para especificar onde entregar a mensagem. Um dispositivo final é a **origem** ou o **destino** de uma mensagem transmitida pela rede.

## Dispositivos intermediários

Os `dispositivos intermediários` são equipamentos na rede que têm a função de conectar dispositivos finais entre si e de conectar diferentes redes. Eles oferecem conectividade e asseguram que os dados fluam pela rede, viajando de um dispositivo final à outro.

Esses `dispositivos intermediários` usam o endereço `IP` do **dispositivo final de destino**, em conjunto com as informações sobre as **interconexões de rede**, para determinar o caminho que as mensagens devem percorrer na rede.

## Meios de rede

A comunicação transmite através de uma rede na `mídia`. A `mídia` fornece os canais físicos ou sem fio que permitem a transmissão de dados entre dispositivos em uma rede.

As redes modernas usam principalmente três tipos de `mídia` para interconectar dispositivos.

|Mídias|Descrição|
|:---:|:---|
|Fios de metal dentro de cabos|Os dados são codificados em impulsos elétricos|
|Cabo de fibra óptica|Os dados são codificados em pulsos de luz|
|Transmissão sem fio|Os dados são codificados através da modulação de frequências específicas de ondas eletromagnéticas|

# Representações e topologias de rede

## Representações de rede

Arquitetos e administradores de rede devem ser capazes de mostrar como suas redes serão. Eles precisam ser capazes de ver facilmente **quais componentes se conectam a outros componentes**, **onde eles serão localizados** e **como eles serão conectados**.

Um `diagrama` fornece uma maneira fácil de entender como os dispositivos se conectam em uma rede grande.

A capacidade de reconhecer as representações lógicas dos componentes físicos de rede é crucial para se permitir visualizar a organização e a operação de uma rede.

## Diagrama de topologia

Os `diagramas de topologia` são documentação obrigatória para qualquer pessoa que trabalhe com uma rede. Eles fornecem um mapa visual de como a rede está conectada.

# Tipos comuns de rede

Existem redes de vários tamanhos. Eles variam de redes simples compostas por dois computadores a redes que conectam milhões de dispositivos.

As redes domésticas simples permitem que você compartilhe recursos, como impressoras, documentos, imagens e música, entre alguns dispositivos finais locais.

As redes de pequeno escritório e escritório doméstico permitem que as pessoas trabalhem em casa ou em um escritório remoto.

Empresas e grandes organizações usam redes para fornecer consolidação, armazenamento e acesso a informações em servidores de rede. Muitas organizações usam a conexão de sua rede à Internet para fornecer produtos e serviços aos clientes.

A internet é a maior rede existente. Na verdade, o termo Internet significa uma “rede de redes”. É uma coleção de redes públicas e privadas interconectadas.

## LAN 

Uma `LAN` (Local Area Network) é uma infraestrutura de rede que cobre uma **área geograficamente limitada**, como uma casa, um escritório, um prédio, ou um campus universitário.

As LANs conectam dispositivos como computadores, impressoras, e servidores dentro dessa área restrita para permitir a comunicação e o compartilhamento de recursos.

Elas são geralmente privadas e controladas pela organização ou pelo indivíduo que as criou.

<p align="center">
  <img src="https://networkencyclopedia.com/wp-content/uploads/2019/09/local-area-network-LAN-1024x488.jpg" width="500px" height="300px">
</p>

## WAN

Uma `WAN` (Wide Area Network) é uma infraestrutura de rede que cobre uma **área geográfica muito ampla**, podendo se estender por cidades, países ou até continentes.

As WANs conectam várias LANs e outros tipos de redes, permitindo que dispositivos em locais diferentes possam se comunicar entre si.

As WANs geralmente são gerenciadas por provedores de serviços (SPs) ou provedores de serviços de Internet (ISPs).

A internet é a maior WAN do mundo, conectando redes de todos os lugares do planeta.

<p align="center">
  <img src="https://www.fttxsolution.com/uploads/202015220/i202011131053434075358.jpg" width="500px" height="300px">
</p>

















<br><br><br><br><hr>
<div align="center">
    <p><strong>Módulo Anterior:</strong> Introdução às Redes</p>
    <p><strong>Próximo Módulo:</strong> Switch Básico</p>
    <a href="#redes-de-computadores-i">Voltar ao topo &#8593;</a>
</div>
<hr><br><br><br><br>

















# Sistema operacional

Todos os dispositivos finais precisam de um `sistema operacional` para funcionar. O SO é o software básico que **gerencia o hardware do dispositivo** e permite que outros programas sejam executados.

<p align="center">
<img src="https://lh6.googleusercontent.com/u3PcFMD6j6Z87RAsb7kD7fExxgIsocZVa8mQYtyNTUDk98K_tWFBksUb1a7NbBSsKuuHvcqGLkpNuEMiPQeGez8wFwTV6SOw4b5B31Wpn7dl4tVP_JzRF63Kkadzz5ZAI5z334ST7fXQHpzKR-eUDwWYPORRjj4wGd7M85xYRzdd1SRHX3z4iL65_w" width="450px" height="300px">
</p>

- `Kernel`: É a parte central do sistema operacional que interage diretamente com o hardware do dispositivo. Ele gerencia recursos como memória, processador, e dispositivos de entrada e saída.

- `Shell`: É a parte do sistema operacional que interage com o usuário e com as aplicações. O shell atua como uma interface entre o kernel e o usuário, permitindo que o usuário envie comandos e receba respostas do sistema. Existem dois tipos principais de shells, o CLI e o GUI.

|Shells|Descrição|
|:---:|:---|
|CLI|Ambiente baseado em texto onde o usuário digita comandos em um prompt de comando. A CLI oferece uma maneira direta e precisa de interagir com o sistema, mas requer que o usuário conheça os comandos específicos e a sintaxe correta|
|GUI|Ambiente baseado em gráficos onde o usuário interage com o sistema através de ícones, janelas, e menus. A GUI é mais intuitiva e amigável para a maioria dos usuários, pois não exige conhecimento de comandos específicos, mas utiliza mais recursos do sistema|

Os sistemas operacionais de rede são semelhantes a um sistema operacional de PCs.

## Métodos de acesso

Os métodos de acesso permitem que você se conecte e gerencie dispositivos de rede, como switches e roteadores.

|Métodos|Descrição|
|:---:|:---|
|Console|O acesso via console é um método de gerenciamento físico que usa uma porta de console para se conectar diretamente a um dispositivo Cisco. O acesso é feito por meio de um canal separado que é utilizado exclusivamente para a manutenção do dispositivo|
|SSH|O SSH é um método seguro para acessar dispositivos remotamente através de uma conexão criptografada. É utilizado para estabelecer uma conexão CLI segura|
|Telnet|O Telnet é um método para acessar dispositivos remotamente através de uma conexão de CLI não segura. Não oferece criptografia, o que significa que os dados, comandos e senhas são transmitidos como texto simples e podem ser facilmente interceptados|

# Comandos primários

Um dispositivo Cisco IOS é compatível com muitos comandos. Cada comando do IOS possui um formato ou sintaxe específica e pode ser executado apenas no modo apropriado.

<p align="center">
<img src="https://www.ccna.network/wp-content/uploads/2020/09/ESTRUTURA-DE-COMANDO-IOS-BASICA.png" width="450px" height="300px">
</p>

A sintaxe fornece o padrão, ou formato, que deve ser usado ao inserir um comando.

Um comando pode exigir um ou mais argumentos. Para determinar as palavras-chave e os argumentos necessários para um comando, consulte a sintaxe de comando. 

## Modo de configuração

Como recurso de segurança, o software Cisco IOS separa o acesso de gerenciamento nestes dois modos de comando.

- `EXEC de usuário` - Ele permite apenas um número limitado de comandos de monitoramento básicos, mas não permite a execução de nenhum comando que possa alterar a configuração do dispositivo. **Identificado pelo prompt que termina com o símbolo '>'**.
- `EXEC privilegiado` - Ele permite executar comandos de configuração mais altos e permite acesso à outros modos de configuração. **Identificado pelo prompt que termina com o símbolo '#'**.

Para configurar o dispositivo, o usuário deve entrar no modo de configuração global. O Modo de Configuração Global é o nível mais alto de configuração. Permite a configuração de aspectos gerais do dispositivo, como o nome do dispositivo, a senha, e as interfaces.

O modo de configuração global é **identificado por um prompt que termina com "(config)#"** após após o nome do dispositivo.

No modo de configuração global, o usuário pode inserir diferentes modos de subconfiguração. Cada um desses modos permite a configuração de uma parte particular ou função do dispositivo IOS.

- `Modo de configuração de linha` - Usado para configurar o acesso ao console, SSH, Telnet ou AUX.
- `Modo de configuração da interface` - Usado para configurar uma porta de switch ou interface de rede do roteador.

Quando a CLI é usada, o modo é identificado pelo prompt da linha de comandos exclusivo para esse modo. O prompt padrão para o `modo de configuração de linha`a é **Switch(config-line)#** e o prompt padrão para o `modo de configuração da interface` é **Switch(config-if)#**.

## Navegação entre os modos do IOS

Para configurar dispositivos Cisco, é necessário entender a navegação entre diferentes modos de configuração na CLI.

Para passar do modo EXEC do usuário para o modo EXEC privilegiado, use o comando **enable**. Use o comando **disable** do modo EXEC privilegiado para retornar ao modo EXEC do usuário.

Para entrar no modo de configuração global, use o comando **configure terminal**, estando no modo EXEC privilegiado. Para retornar ao modo EXEC privilegiado, digite o comando **exit**.

Para entrar no modo de subconfiguração de linha, use o comando **line** seguido pelo **tipo** e **número da linha de gerenciamento** que deseja acessar. Use o comando **exit** para sair de um modo de subconfiguração e retornar ao modo de configuração global.

```txt
Switch(config)# line console 0
Switch(config-line)# exit
Switch(config)#
```

Para entrar no modo de subconfiguração de interface, use o comando **interface** seguido pelo **nome da interface** que deseja acessar. Use o comando **exit** para sair de um modo de subconfiguração e retornar ao modo de configuração global.

```txt
Switch(config-line)# interface FastEthernet 0/1
Switch(config-if)#
```

Para passar de qualquer modo de subconfiguração para o modo EXEC privilegiado, insira o comando **end**.

## Resumo

|Modo|Prompt|Comando para Entrar|
|:---|:---|:---|
|EXEC do usuário|**Switch>**||
|EXEC privilegiado|**Switch#**|`enable`|
|Configuração global|**Switch(config)#**|`configure terminal`|
|Configuração de linha|**Switch(config-line)#**|`line [tipo] [número]`|
|Configuração da interface|**Switch(config-if)#**|`interface [nome]`|

# Configuração básica de dispositivos

## Nomes de dispositivo

Por padrão, todos os dispositivos recebem um nome padrão de fábrica. Por exemplo, um switch Cisco IOS é “Switch“.

Uma organização deve escolher uma convenção de nomenclatura que torne fácil e intuitivo identificar um dispositivo específico.

No modo de configuração global, digite o comando **hostname** seguido pelo **nome do host**.

```txt
Switch# configure terminal
Switch(config)# hostname Switch
Switch(config)#
```

## Configurar senhas

Quando você se conecta inicialmente a um dispositivo, você está no modo EXEC do usuário. Este modo é protegido usando o console.

No modo de configuração de linha, digite o comando **password [senha]** para configurar uma senha para o modo EXEC do usuário. Por fim, digite **login** habilitar a autenticação de senha.

O acesso ao console agora exigirá uma senha antes de permitir o acesso ao modo EXEC do usuário.

```txt
Switch# configure terminal
Switch(config)# line console 0
Switch(config-line)# password cisco
Switch(config-line)# login
Switch(config-line)# end
Switch#
```

Para proteger o acesso EXEC privilegiado, use o comando **enable secret [senha]** no modo de configuração global.

```txt
Switch# configure terminal
Switch(config)# enable secret class
Switch(config)# exit
Switch#
```

## Criptografar senhas

Os arquivos `startup-config` e `running-config` exibem a maioria das senhas em texto simples. Esta é uma ameaça à segurança, porque qualquer pessoa pode descobrir as senhas se tiver acesso a esses arquivos.

Para criptografar todas as senhas de texto simples, use o comando **service password-encryption**.

O comando aplica criptografia fraca a todas as senhas não criptografadas.

O propósito deste comando é proibir que indivíduos não autorizados vejam as senhas no arquivo de configuração.

```txt
Switch# configure terminal
Switch(config)# service password-encryption
Switch(config)#
```

## Mensagens de banner

Embora a exigência de senhas seja uma maneira de manter pessoal não autorizado fora da rede, é vital fornecer um método para declarar que apenas pessoal autorizado deve tentar acessar o dispositivo.

Banners podem ser uma parte importante do processo legal caso alguém seja processado por invadir um dispositivo. 

Para criar uma mensagem de banner, use o comando de configuração global **banner motd #[mensagem]#**.

O '#' na sintaxe do comando é denominado caractere de delimitação. Ele é inserido antes e depois da mensagem.

```txt
Switch# configure terminal
Switch(config)# banner motd #acesso autorizado apenas com senha#
```

## Arquivos de configuração

Há dois arquivos de sistema que armazenam a configuração do dispositivo:

- `startup-config` - Este é o arquivo de configuração salvo armazenado na NVRAM. Ele contém todos os comandos que serão usados pelo dispositivo na inicialização ou reinicialização.
- `running-config` - Isto é armazenado na memória de acesso aleatório (RAM). Ele reflete a configuração atual.

O comando **show running-config** do modo EXEC privilegiado é usado para visualizar a configuração em execução.

Para visualizar o arquivo de configuração de inicialização, use o comando EXEC privilegiado **show startup-config**.

Para salvar as alterações feitas na configuração em execução no arquivo de configuração de inicialização, use o comando do modo EXEC privilegiado **copy running-config startup-config**.

# Endereço IP

O uso de endereços `IP` é o principal meio de permitir que os dispositivos **se localizem** e **estabeleçam comunicação ponto a ponto** na Internet. Cada dispositivo final em uma rede deve ser configurado com um endereço IP.

A estrutura de um endereço IPv4 é chamada notação decimal com ponto e é representada por **quatro números decimais entre 0 e 255**. Os endereços IPv4 são atribuídos individualmente a dispositivos conectados a uma rede.

Com o endereço IPv4, uma máscara de sub-rede também é necessária. Uma máscara de sub-rede IPv4 é um **valor de 32 bits** que diferencia a parte da rede do endereço da parte do host.

<p align="center">
<img src="https://www.hardware.com.br/static/00000000/img-bcc95885.png" width="450px" height="300px">
</p>

Juntamente com o endereço IPv4, a máscara de sub-rede determina a qual sub-rede o dispositivo é membro.

# Interfaces e portas

A comunicação em rede depende de interfaces de dispositivos e portas físicas, que conectam os dispositivos entre si e permitem a transmissão de dados.

Uma interface é um ponto de conexão entre um dispositivo de rede e outro dispositivo ou rede. Ela pode ser física ou virtual.

|Conexões|Descrição|
|:---:|:---|
|Física|Refere-se a conexões tangíveis, como uma interface Ethernet em um switch, que se conecta a um cabo de rede|
|Virtual|Refere-se a conexões que não correspondem a portas físicas, como uma interface SVI ou uma interface loopback|

Cada interface física é regida por especificações ou padrões que determinam o tipo de cabo que pode ser conectado a ela.

A escolha da mídia de rede (cabo) deve levar em consideração essas especificações ou padrões, pois nem todas as mídias (cabos) são adequadas para todos os propósitos.

Uma porta é uma entrada ou saída física em um dispositivo de rede onde um cabo pode ser conectado. As portas permitem a conexão física de cabos que transmitem os dados. Cada porta está associada a uma interface física correspondente.

## Configuração manual de IP

A configuração manual de `IP` é quando o endereço IP de um dispositivo é atribuído manualmente por um administrador de rede. O administrador define um endereço `IP` específico, juntamente com outros parâmetros como **máscara de sub-rede**, **gateway padrão** e **servidores DNS**.

Para configurar manualmente um endereço IPv4 em um host do Windows, siga os seguintes passos:

1. Acesse o **Painel de Controle** > **Central de Rede e Compartilhamento**.
2. Clique em **Alterar configurações do adaptador**.
3. Clique com o botão direito na sua conexão de rede e selecione **Propriedades**.
4. Selecione **Protocolo IP Versão 4** e clique em **Propriedades**.
5. Selecione **Usar** o seguinte endereço IP e insira o endereço `IP`, `máscara de sub-rede`, `gateway padrão`, e `servidores DNS`.

## Configuração automática de IP

A configuração automática de IP usa o `protocolo DHCP` para atribuir endereços IP automaticamente aos dispositivos na rede. Quando um dispositivo se conecta à rede, ele **solicita um IP a um servidor DHCP**. O servidor DHCP então **atribui um endereço IP disponível** e outros parâmetros, como **máscara de sub-rede** e **DNS**.

Para configurar manualmente um endereço IPv4 em um host do Windows, siga os seguintes passos:

1. Acesse o **Painel de Controle** > **Central de Rede e Compartilhamento**.
2. Clique em **Alterar configurações do adaptador**.
3. Clique com o botão direito na sua conexão de rede e selecione **Propriedades**.
4. Selecione **Protocolo IP Versão 4** e clique em **Propriedades**.
5. Escolha a opção **Obter um endereço IP automaticamente**.

# Configuração da interface virtual do Switch

Para acessar o switch remotamente, um endereço **IP** e uma **máscara de sub-rede** devem ser configurados na SVI.

Para configurar um SVI em um switch, use o comando **interface vlan 1** de configuração global. Em seguida, atribua um endereço IPv4 usando o comando **ip address [ip] [máscara]**. Por fim, ative a interface virtual usando o comando **no shutdown** de configuração da interface.

Após a configuração desses comandos, o switch terá todos os elementos IPv4 prontos para comunicação pela rede.

```txt
Switch# configure terminal
Switch(config)# interface vlan 1
Switch(config-if)# ip address 192.168.1.20 255.255.255.0
Switch(config-if)# no shutdown
Switch(config-if)# exit
Switch(config)# ip default-gateway 192.168.1.1
```












           
<br><br><br><br><hr>
<div align="center">
    <p><strong>Módulo Anterior:</strong> Switch Básico</p>
    <p><strong>Próximo Módulo:</strong> Protocolos e modelos</p>
    <a href="#redes-de-computadores-i">Voltar ao topo &#8593;</a>
</div>
<hr><br><br><br><br>















# As regras

O envio de uma mensagem, seja por comunicação presencial ou por rede, é regido por regras chamadas protocolos. Esses protocolos são específicos ao tipo de método de comunicação que está sendo usado.

Os protocolos devem ter em conta os seguintes requisitos para entregar com êxito uma mensagem compreendida pelo receptor:

- Um emissor e um receptor identificados.
- Língua e gramática comum.
- Velocidade e ritmo de transmissão.
- Requisitos de confirmação ou recepção.

Além de identificar a origem e o destino, os protocolos de computadores e de redes definem os detalhes sobre como uma mensagem é transmitida por uma rede.

## Codificação de mensagens

Uma das primeiras etapas para enviar uma mensagem é codificá-la. A `codificação` é o processo de conversão de informações em outra forma aceitável para a transmissão.

A `decodificação` reverte esse processo para interpretar as informações.

A codificação assegura que os dados possam ser transmitidos de maneira eficiente e compreendida pelo receptor. Ajuda a prevenir erros de interpretação e garante que os dados sejam adequadamente preparados para a transmissão.

As mensagens enviadas pela rede **são convertidas** primeiramente **em bits** pelo host emissor. Cada bit é codificado em um padrão de tensões em fios de cobre, luz infravermelha em fibras ópticas ou microondas para sistemas sem fio. O host de destino recebe e decodifica os sinais para interpretar a mensagem.

## Formatação e encapsulamento de mensagens

Quando uma mensagem é enviada da origem para o destino, deve usar um formato ou uma estrutura específica. Os formatos da mensagem **dependem do tipo de mensagem** e do **canal usado** para entregá-la.

Envolvem organizar os dados em pacotes ou quadros que podem ser transmitidos pela rede.

A formatação ajuda a garantir que o receptor possa interpretar e processar os dados corretamente, enquanto o encapsulamento permite que a mensagem seja dividida em partes gerenciáveis.

## Tamanho da mensagem

Quando uma mensagem longa é enviada de um host a outro em uma rede, é necessário dividir a mensagem em partes menores. As regras que regem o tamanho das partes, ou quadros, transmitidos pela rede são muito rígidas.

As restrições de tamanho dos quadros exigem que o host origem **divida uma mensagem longa em pedaços individuais** que atendam aos requisitos de tamanho mínimo e máximo. A mensagem longa *será enviada em quadros separados*, e cada um contém uma parte da mensagem original. Cada quadro também terá suas próprias informações de endereço. 

No host destino, as partes individuais da mensagem **são reconstruídas na mensagem original.**

## Temporização da mensagem

O tempo de mensagens também é muito importante nas comunicações de rede. A temporização da mensagem inclui o seguinte:

|Processos|Descrição|
|:---:|:---|
|Controle de Fluxo|O controle de fluxo define quanta informação pode ser enviada e a velocidade com que pode ser entregue (taxa de transmissão)|
|Tempo limite da resposta|Os hosts da rede usam protocolos de rede que especificam quanto tempo esperar pelas respostas e que ação executar se ocorrer um tempo limite de resposta|
|Método de acesso|Determinar quando alguém pode enviar uma mensagem|

## Opções de envio de mensagem

Uma mensagem pode ser entregue de diferentes maneiras. As comunicações em rede têm opções de entrega semelhantes para se comunicar.

|Tipos|Descrição|
|:---:|:---|
|Unicast|As informações estão sendo transmitidas **para um único** dispositivo final|
|Multicast|Informações estão sendo transmitidas **para um ou mais** dispositivos finais|
|Broadcast|Informações estão sendo transmitidas **para todos** os dispositivos finais|

# Protocolos

Os `protocolos` de rede definem um formato comum e um conjunto de regras para a troca de mensagens entre dispositivos. Os protocolos são implementados por dispositivos finais e dispositivos intermediários em software, hardware ou ambos. Cada protocolo de rede tem sua própria função, formato e regras para comunicações.

## Funções de protocolos

Computadores e dispositivos de rede usam protocolos acordados para se comunicar. A tabela lista as `funções` desses protocolos.

|Função|Descrição|
|:---:|:---|
|Endereçamento|Esse protocolo identifica o remetente e o destinatário pretendido da mensagem usando um esquema de endereçamento definido|
|Confiabilidade|Esse protocolo fornece mecanismos de entrega garantidos em caso de mensagens são perdidos ou corrompidos em trânsito|
|Controle de fluxo|Esse protocolo garante que os fluxos de dados a uma taxa eficiente entre dois dispositivos de comunicação|
|Sequenciamento|Esse protocolo rotula exclusivamente cada segmento de dados transmitido. Ele usa as informações de sequenciamento para remontar o informações corretamente|
|Detecção de erros|Esse protocolo é usado para determinar se os dados foram corrompidos durante transmissão|
|Interface de aplicação|Esse protocolo contém informações usadas para processo a processo comunicações entre aplicações de rede. Por exemplo, ao acessar uma página da Web, protocolos HTTP ou HTTPS são usados para se comunicar entre o processos da Web do cliente e do servidor|

## Conjunto de protocolos

Uma mensagem enviada através de uma rede de computadores normalmente **requer o uso de vários protocolos**, cada um com suas próprias funções e formato.

Os protocolos são visualizados em termos de camadas, com cada serviço de nível superior, dependendo da funcionalidade definida pelos protocolos mostrados nos níveis inferiores. As camadas inferiores estão relacionadas com a movimentação de dados pela rede e o fornecimento de serviços às camadas superiores, que se concentram no conteúdo da mensagem que está sendo enviada.

A estrutura de camadas foi criada para organizar e facilitar o entendimento dos protocolos de rede. Essa abordagem em camadas permite que diferentes protocolos sejam agrupados de acordo com suas funções, criando uma separação lógica entre as tarefas que precisam ser realizadas para a comunicação entre dispositivos.

<p align="center">
<img src="https://ccnadesdecero.es/wp-content/uploads/2017/11/Evoluci%C3%B3n-de-suites-de-protocolo.png" width="450px" height="300px">
</p>

Um conjunto(suíte) de protocolos é um **grupo de protocolos inter-relacionados**, de várias camadas, que trabalham juntos para **permitir a comunicação completa entre dispositivos**. Esses protocolos são organizados em diferentes camadas de um modelo de rede e cada camada lida com uma parte específica do processo de comunicação.

Conjuntos de protocolos proporcionam um padrão comum para a comunicação de dados, permitindo que diferentes sistemas e dispositivos se conectem e compartilhem informações.

# Modelos de camadas

O `modelo de camadas` é uma forma de organizar a comunicação em redes de computadores, **dividindo o processo de troca de dados em diferentes camadas**, cada uma com responsabilidades específicas. Essa abordagem facilita o desenvolvimento, padronização e entendimento dos protocolos e tecnologias de rede.

<p align="center">
<img src="https://www.dltec.com.br/blog/wp-content/uploads/2019/02/osi-tcp-ip.png" width="450px" height="300px">
</p>

## OSI

O modelo `OSI` pode ser considerado a linguagem universal da rede de computadores. Ele se baseia no conceito de dividir um sistema de comunicação em sete camadas abstratas, empilhadas umas sobre as outras.

Cada camada do modelo OSI lida com uma tarefa específica e se comunica com as camadas acima e abaixo dela.

Como o modelo OSI separa a camada de enlace de dados da camada física, geralmente é usado para referenciar as camadas inferiores.

|Camadas|Número|Descrição|
|:---:|:---:|:---|
|Física|1|Transmissão de bits através do meio físico (cabos, sinais)|
|Enlace de Dados|2|Transferência confiável de dados (quadros) entre dispositivos na mesma rede|
|Rede|3|Roteamento e endereçamento de pacotes entre redes diferentes|
|Transporte|4|Garantia de entrega dos dados com controle de fluxo e erros|
|Sessão|5|Gerenciamento de conexões e sessões entre dispositivos|
|Apresentação|6|Tradução, criptografia e compressão de dados|
|Aplicação|7|Interface com aplicativos de usuário, como e-mail e web|

### Camada física

A primeira camada OSI é a `camada física`. A camada física compreenderia ao **caminho que os pacotes percorrem para chegar ao destino**. Nesta camada são **especificados os equipamentos físicos** envolvidos na transferência de dados, como cabos e switchs.

Essa também é a camada em que os **dados são convertidos em um fluxo de bits**, que é uma sequência de 1s e 0s. A camada física de ambos os dispositivos também precisa aceitar, de comum acordo, uma convenção de sinais para que se possa distinguir os 1s dos 0s em ambos os dispositivos.

<p align="center">
<img src="https://cf-assets.www.cloudflare.com/slt3lc6tev37/1HQ1W5P4XAinIdM37DTu4U/900ccdceda346baf03ce8b9f977d2974/osi_model_physical_layer_1.png" width="550px" height="300px">
</p>

Os dados são transmitidos por esses meios e processados na próxima camada.

### Camada de enlace de dados

A camada de enlace de dados facilita a transferência de dados entre dois dispositivos na mesma rede. 

A `camada de enlace de dados` pega os pacotes da camada de rede e os **divide em pedaços menores denominados** "quadros".

Nesta camada, os dados recebidos do meio físico são **verificados para ver se possuem algum erro** e, caso possuam, ele pode ser corrigido. Dessa forma, as camadas superiores podem assumir uma transmissão praticamente sem erros.

Esta camada também **controla o fluxo que os dados são transmitidos**.

Também é nela que dispositivos como os `switches` funcionam.

### Camada de rede

A `camada de rede` é responsável por facilitar a transferência de dados entre duas redes diferentes. Se os dois dispositivos que estão se comunicando estiverem na mesma rede, a camada de rede será desnecessária. 

A camada de rede **divide os segmentos** da camada de transporte **em unidades menores** denominadas pacotes **no dispositivo remetente** e **remonta esses pacotes no dispositivo receptor**. 

A camada de rede também **encontra o melhor caminho físico** para que os dados cheguem ao seu destino, o que é conhecido como `roteamento`.

Os protocolos da camada de rede incluem o `IP`, o `ICMP` e o conjunto `IPsec`.

### Camada de transporte

A camada 4 é responsável pela **comunicação de ponta a ponta entre os dois dispositivos**. Isso inclui pegar os dados da camada de sessão e dividi-los em porções chamadas segmentos antes de enviá-los para a camada 3. 

A camada de transporte no dispositivo receptor é responsável por remontar os segmentos em dados que a camada de sessão possa consumir.

<p align="center">
<img src="https://cf-assets.www.cloudflare.com/slt3lc6tev37/3OlO75NcADGL3SmEADFDqd/723b8c7639c4e2e6b4febcbe7fd36e0e/osi_model_transport_layer_4.png" width="550px" height="300px">
</p>

A `camada de transporte` também é responsável pelo **controle de fluxo e pelo controle de erros**. O `controle de fluxo` determina uma velocidade de transmissão ideal para garantir que um remetente não sobrecarregue um receptor. A camada de transporte executa o `controle de erros` no lado do receptor, garantindo que os dados recebidos estejam completos e solicitando uma retransmissão caso não estejam.

Os protocolos da camada de transporte incluem o `TCP` e o `UDP`.

### Camada de sessão

Essa é a camada responsável pela **abertura e fechamento da comunicação entre os dois dispositivos**. O tempo decorrido entre o momento em que a comunicação é aberta e fechada é conhecido como "sessão". 

A `camada de sessão` garante que a sessão permaneça aberta pelo tempo necessário para transferir todos os dados que estão sendo trocados e, em seguida, fecha imediatamente a sessão para evitar o desperdício de recursos.

### Camada de apresentação

Essa camada é a principal responsável pela **preparação dos dados** para que possam ser usados pela camada de aplicação. A `camada de apresentação` é responsável pela **tradução**, **criptografia** e **compactação** dos dados.

<p align="center">
<img src="https://cf-assets.www.cloudflare.com/slt3lc6tev37/19L86neKKT8srUkOSe4rf7/ff4c91c94a1790651df7b48433913f59/osi_model_presentation_layer_6.png" width="550px" height="300px">
</p>

Nesta camada temos a **conversão de códigos para caracteres**, a conversão e compactação dos dados, além da criptografia desses dados, caso necessite.

Depois de tratados, esses dados estão prontos para serem usados na próxima camada.

### Camada de aplicação

Essa é a única camada que **interage diretamente com os dados do usuário**. Os softwares aplicativos, dependem da `camada de aplicação` para iniciar as comunicações.

<p align="center">
<img src="https://cf-assets.www.cloudflare.com/slt3lc6tev37/2rcDKpr4WLqoyAZ7GDKkyJ/7cab96402de7ac5465b86e617da3da4e/osi_model_application_layer_7.png" width="550px" height="300px">
</p>

É nesta camada que temos os protocolos mais conhecidos como o `Sz`, `FTP`, além de serviços como o `DNS`.

## TCP/IP

O modelo de camadas `TCP/IP` possui suas funções divididas em camada da mesma forma que o OSI. A diferença principal nestas estruturas é o número de camadas encontradas em cada modelo.

Os protocolos que compõem a suíte de protocolos TCP/IP também podem ser descritos em termos do modelo de referência OSI.

|Camadas|Número|Descrição|
|:---:|:---:|:---|
|Acesso à rede|1|Controla os dispositivos de hardware e o meio físico que formam a rede|
|Internet|2|Determina o melhor caminho pela rede|
|Transporte|3|Permite a comunicação entre vários dispositivos diferentes em redes distintas|
|Aplicação|4|Representa dados para o usuário, além do controle de codificação e de diálogo|

### Camada de acesso à rede

Esta é a camada de base da arquitetura TCP/IP, correspondente às camadas de enlace de dados e física do OSI.

A `camada de acesso à rede`, também conhecida como camada de link de dados, lida com a infraestrutura física que permite que os computadores se comuniquem entre si pela internet. Isso abrange **cabos de ethernet**, **redes sem fio**, **placas de interface de rede**, drivers de dispositivos no computador, etc.

A camada de acesso à rede também inclui a infraestrutura técnica, como o código que **converte dados digitais em sinais transmissíveis**, o que torna a conexão de rede possível.

### Camada de internet

A camada de internet, também conhecida como camada de rede, controla o fluxo e o roteamento do tráfego para garantir que os dados sejam enviados com rapidez e precisão. Essa camada também é responsável por remontar o pacote de dados no destino. 

### Camada de transporte

A camada de transporte oferece uma conexão de dados confiável entre dois dispositivos de comunicação. 

A `camada de transporte` **divide os dados em pacotes**, reconhece os pacotes que recebeu do remetente e garante que o destinatário reconheça os pacotes que receber.

### Camada de aplicação

Essa é a única camada que **interage diretamente com os dados do usuário**. Os softwares aplicativos, dependem da `camada de aplicação` para iniciar as comunicações.

## Comparações

Os protocolos que compõem o modelo TCP/IP também podem ser descritos em termos do modelo OSI.

Na camada de acesso à rede, o modelo TCP/IP não especifica que protocolos usar ao transmitir por um meio físico. As Camadas 1 e 2 do modelo OSI discutem os procedimentos necessários para acessar a mídia e o meio físico para enviar dados por uma rede.

A Camada OSI 3, a camada de rede, é mapeada diretamente para a camada de Internet TCP/IP. Essa camada é usada para descrever os protocolos que endereçam e encaminham mensagens em uma rede interconectada.

A Camada OSI 4, a camada de transporte, mapeia diretamente para a camada de transporte TCP/IP. Essa camada descreve os serviços e as funções gerais que fornecem uma entrega ordenada e confiável de dados entre os hosts origem e destino.

A camada de aplicação TCP/IP inclui vários protocolos que fornecem funcionalidade específica para uma variedade de aplicativos do usuário final. As camadas 5, 6 e 7 do modelo OSI são usadas como referências para desenvolvedores e fornecedores de software de aplicação para produzir aplicações que operam em redes.

# Encapsulamento de dados

## Segmentação

`Segmentação` é o processo de **dividir um fluxo de dados em unidades menores** para transmissões através da rede. A segmentação é necessária porque as redes de dados usam o conjunto de protocolos TCP/IP enviar dados em pacotes IP individuais.

Cada `pacote` é enviado separadamente. Pacotes que contêm segmentos para o mesmo destino podem ser enviados por caminhos diferentes.

Isso leva à segmentação de mensagens com dois benefícios principais:

- **Aumenta a velocidade** - Como um fluxo de dados grande é segmentado em pacotes, grandes quantidades de dados podem ser enviadas pela rede sem amarrar um link de comunicação. Isso permite que muitas conversas diferentes sejam intercaladas na rede chamada multiplexação.
- **Aumenta a eficiência** - Se um único segmento não conseguir alcançar seu destino devido a uma falha na rede ou no congestionamento da rede, somente esse segmento precisa ser retransmitido em vez de reenviar todo o fluxo de dados.

## Sequenciamento

`Sequenciamento` é o processo de garantir que os segmentos de dados sejam entregues ao destino e remontados na **ordem correta**.

No processo de segmentação, cada segmento recebe um **número de sequência**. Quando os segmentos são recebidos pelo dispositivo de destino, a `camada de transporte` usa esses números para reorganizar os dados na ordem correta.

Protocolos como `TCP` garantem que os dados sejam remontados corretamente, mesmo que os segmentos cheguem fora de ordem.

## Unidades de dados de protocolo

À medida que os dados da aplicação são passados pela **pilha de protocolos** em seu caminho para serem transmitidos pelo meio físico de rede, várias **informações de protocolos são adicionadas em cada nível**. Isso é conhecido como o processo de `encapsulamento`.

As `unidades de dados de protocolo (PDU)` são os *formatos que os dados assumem* em cada camada do modelo de rede **à medida que são transmitidos** pela pilha de protocolos. Cada camada, ao processar os dados, os encapsula adicionando informações específicas chamadas `cabeçalhos`. Esses cabeçalhos servem para **controlar** como os dados serão transmitidos e interpretados pela **camada correspondente** no dispositivo receptor.

As `PDUs` são chamadas de forma diferente em cada camada para refletir as suas novas funções, e isso pode variar dependendo do modelo de rede. No caso do conjunto de protocolos TCP/IP, o nome da PDU muda à medida que os dados passam por cada camada:

|Nomeclatura|Camada|Descrição|
|:---:|:---:|:---|
|Dados|Aplicação|Os dados originais gerados pela aplicação|
|Segmento|Transporte|Os dados são divididos em segmentos, e são adicionadas informações sobre controle de fluxo, confiabilidade e integridade|
|Pacote|Rede|Os segmentos são encapsulados em pacotes, que contém os endereços IP de origem e destino|
|Quadro|Enlace de dados|Os pacotes são encapsulados em quadros, que incluem endereços MAC e outras informações|
|Bits|Física|Os quadros são convertidos em uma sequência de bits|

> Obs: Se o cabeçalho de transporte for UDP, então é um datagrama.


















<br><br><br><br><hr>
<div align="center">
    <p><strong>Módulo Anterior:</strong> Protocolos e modelos</p>
    <p><strong>Próximo Módulo:</strong> Camada física</p>
    <a href="#redes-de-computadores-i">Voltar ao topo &#8593;</a>
</div>
<hr><br><br><br><br>




















# Visão geral

A `camada física` do modelo `OSI` fornece os **meios para transportar os bits** que formam um quadro da camada de enlace de dados no meio físico de rede. 

Essa camada **aceita um quadro** completo da `camada de enlace de dados` e o **codifica** como uma série de sinais que são **transmitidos** à mídia local. Os bits codificados que formam um quadro são recebidos por um dispositivo final ou por um dispositivo intermediário.

Os padrões da camada física abordam três áreas funcionais:

- Componentes Físicos
- Codificação
- Sinalização

## Componentes físicos

Os `componentes físicos` são os dispositivos de hardware eletrônico, mídia e outros conectores que transmitem os sinais que representam os bits (NICs, conectores, cabos, portas e interfaces).

## Codificação

A `codificação` é um método para converter um fluxo de bits de dados em um "código” predefinido. Os códigos são **agrupamentos de bits** usados para fornecer um padrão previsível que **pode ser reconhecido** tanto pelo emissor quanto pelo receptor.

## Sinalização

A `sinalização` é a maneira como os bits são representados no meio físico. Os padrões de camada física devem **definir** que tipo de sinal representa o valor “1” e que tipo de sinal representa o valor “0”.

# Largura de banda

Meios físicos diferentes aceitam a **transferência de bits** a taxas diferentes. A transferência de dados é geralmente discutida em termos de largura de banda. 

`Largura de banda` é a capacidade na qual um meio pode transportar dados. A largura de banda digital mede a **quantidade de dados que podem ser transmitidos** de um lugar para outro durante um **determinado tempo**. A largura de banda é normalmente medida em kilobits/megabits/gigabits por segundo. 

Uma combinação de fatores determina a largura de banda prática de uma rede:

- As propriedades do meio físico
- As tecnologias escolhidas para sinalização e detecção de sinais de rede

Os termos usados para medir a qualidade da largura de banda incluem:

|Termos|Descrição|
|:---:|:---|
|Latência|**Tempo necessário para os dados viajarem** de um ponto a outro, incluindo atrasos|
|Taxa de transferência|**Medida da transferência de bits através da mídia** durante um determinado período|
|Goodput|**Medida de dados usáveis transferidos** em um determinado período|














<br><br><br><br><hr>
<div align="center">
    <p><strong>Módulo Anterior:</strong> Camada física</p>
    <p><strong>Próximo Módulo:</strong> Camada de enlace de dados</p>
    <a href="#redes-de-computadores-i">Voltar ao topo &#8593;</a>
</div>
<hr><br><br><br><br>

















# Conceitos gerais

A `camada de enlace` de dados do modelo `OSI` serve para **garantir a transmissão** correta e confiável de dados entre dispositivos **em uma rede local**. Ela opera diretamente sobre a camada física, lidando com a comunicação entre dispositivos conectados à mesma rede.

A camada de enlace de dados faz o seguinte:

- Recebe os pacotes de Camada 3 e os encapsula em quadros da Camada 2
- Controla como os dados são colocados e recebidos na mídia
- Troca quadros entre pontos dispositivos finais através da mídia de rede
- Executa a detecção de erros e rejeita qualquer quadro corrompido

# Subcamadas

A `camada de enlace de dados` no modelo OSI é **dividida em duas subcamadas** principais, cada uma com funções específicas que garantem uma comunicação entre dispositivos na mesma rede. Essas subcamadas são a subcamada de `controle de enlace lógico (LLC)` e a subcamada de `controle de acesso ao meio (MAC)`.

## LLC

Esta subcamada **comunica** entre o **software** de rede nas camadas superiores e o **hardware** do dispositivo nas camadas inferiores. Ela coloca a informação no quadro que identifica qual protocolo de camada de rede está sendo usado para o quadro. Essas informações permitem que vários protocolos da camada 3, como IPv4 e IPv6, usem a mesma interface de rede e mídia.

A subcamada de `controle de enlace lógico (LLC)` é responsável por fornecer uma interface para a camada de rede e **gerenciar a comunicação** de dados entre o **sistema operacional** e o **hardware**.

Ela oferece serviços de controle de erro e controle de fluxo, além de suportar diferentes protocolos de rede. 

Ela também permite que vários protocolos de rede utilizem a mesma interface física sem interferência mútua.

## MAC

A subcamada de `controle de acesso ao meio (MAC)` lida com a forma como os dados são realmente **transmitidos no meio físico**. 

Ela é responsável por **endereçar** e **identificar dispositivos** na rede local através de endereços `MAC`.

Além disso, a MAC **define o formato dos quadros** e realiza a detecção e correção de erros durante a transmissão, garantindo que os dados cheguem corretamente ao destino.

Delimitação de quadros - O processo de enquadramento fornece delimitadores importantes para identificar campos dentro de um quadro. Esses bits de delimitação promovem a sincronização entre os nós de transmissão e de recepção.
Endereçamento - Fornece endereçamento de origem e destino para transportar o quadro da Camada 2 entre dispositivos na mesma mídia compartilhada.
Detecção de erro - Inclui um trailer usado para detectar erros de transmissão.

A subcamada MAC também  gerencia o **acesso ao meio físico**, permitindo que vários dispositivos se comuniquem através de uma mídia compartilhada (half-duplex). As comunicações full-duplex não exigem controle de acesso. Para evitar colisões na mídia compartilhada, a subcamada MAC implementa protocolos como o CSMA/CD para redes Ethernet, que ajuda a coordenar o uso do meio e minimizar conflitos.

# Topologias

As `topologias` de rede **descrevem a estrutura física ou lógica** de como os dispositivos de uma rede estão **interconectados**. Cada topologia possui características distintas que afetam a eficiência, a escalabilidade e a manutenção da rede.

Existem dois tipos de topologias usadas ao descrever redes LAN e WAN:

|Tipos|Descrição|
|:---:|:---|
|Física|Identifica as **conexões físicas** e como os dispositivos `finais` e `intermediários` são interconectados|
|Lógica|Identifica **conexões virtuais**, referindo-se à maneira como uma rede **transfere quadros** de um nó para o próximo|

<p align="center">
<img src="https://wiki.sj.ifsc.edu.br/images/d/dc/PJI3-etapa1.jpg" width="650px" height="300px">
</p>

A `camada de enlace de dados` “vê” a topologia lógica da rede quando **controla o acesso de dados ao meio físico**, pela subcamada `MAC`.

## Ponto a ponto

A `topologia ponto a ponto`, comum em redes `LAN` e `WAN`, **conecta dois dispositivos diretamente** por meio de um link dedicado, sem a necessidade de intermediários, como switches ou hubs.

<p align="center">
<img src="https://blog.xpeducacao.com.br/wp-content/uploads/2022/09/topologia-de-rede-ponto-a-ponto-1024x459.jpg" width="550px" height="300px">
</p>

Cada dispositivo na rede se comunica **exclusivamente** com o outro através dessa **conexão direta**.

A simplicidade da topologia torna sua implementação prática, especialmente em redes pequenas ou para estabelecer comunicação direta entre dois dispositivos.

## Barramento

Na `topologia em barramento`, comum em redes `LAN`, todos os dispositivos estão conectados a um **único cabo de comunicação**, conhecido como barramento.

<p align="center">
<img src="https://blog.xpeducacao.com.br/wp-content/uploads/2022/09/topologia-de-rede-barramento-1024x508.jpg" width="550px" height="300px">
</p>

Os dados enviados por um dispositivo são recebidos por **todos** os outros dispositivos na rede. 

Esta topologia é simples e econômica, mas pode ser problemático se o cabo principal falhar, pois toda a rede fica comprometida. Além disso, o desempenho pode diminuir com o aumento do número de dispositivos.

## Estrela

Na `topologia em estrela`, comum em redes `LAN`, todos os dispositivos são **conectados a um dispositivo central**, como um switch ou um hub. 

<p align="center">
<img src="https://blog.xpeducacao.com.br/wp-content/uploads/2022/09/topologia-de-rede-estrela-1024x717.jpg" width="550px" height="300px">
</p>

Cada dispositivo tem um cabo dedicado que se **conecta ao centralizador**. Isso facilita a detecção e solução de problemas, pois a falha de um cabo ou dispositivo não afeta o restante da rede. No entanto, a falha no dispositivo central pode paralisar toda a rede.

## Anel

Na `topologia em anel`, comum em redes `LAN`, os dispositivos são conectados em um **círculo fechado**, com cada dispositivo **conectado a outros dois dispositivos**, formando um **anel** contínuo. 

<p align="center">
<img src="https://blog.xpeducacao.com.br/wp-content/uploads/2022/09/topologia-de-rede-anel-1024x837.jpg" width="550px" height="300px">
</p>

Os dados circulam em uma direção (ou em ambas as direções, se a topologia for de anel duplo). Essa estrutura pode ser eficiente para redes de alta velocidade, mas a falha em qualquer ponto do anel pode interromper a comunicação em toda a rede.

O controle de acesso utiliza o método chamado `Token Passing`. O Token Passing é uma técnica onde um **"token"** circula continuamente pela rede. Somente o dispositivo que **possui o token** pode enviar dados, o que elimina a possibilidade de colisão, tornando essa topologia eficiente para o controle de acesso.

## Malha

Na `topologia em malha`, comum em redes `WAN`, cada dispositivo está conectado a **todos os outros dispositivos** da rede.

<p align="center">
<img src="https://blog.xpeducacao.com.br/wp-content/uploads/2022/09/topologia-de-rede-malha-1024x697.jpg" width="550px" height="300px">
</p>

Essa topologia oferece **alta redundância** e **confiabilidade**, pois se um link falhar, há caminhos alternativos disponíveis para a comunicação. 

A complexidade e o custo de implementação são altos devido ao grande número de conexões necessárias.

## Árvore

A `topologia em árvore`, comum em redes `LAN` e `WAN`, **combina características** das topologias em `barramento` e `estrela`. 

<p align="center">
<img src="https://blog.xpeducacao.com.br/wp-content/uploads/2022/09/topologia-de-rede-arvore-1024x639.jpg" width="550px" height="300px">
</p>

Ela organiza os dispositivos em uma **estrutura hierárquica**, com vários hubs ou switches conectados a um dispositivo central, formando uma **árvore de redes**. 

Essa topologia é escalável e facilita a adição de novos dispositivos, mas a falha no dispositivo central pode afetar grandes partes da rede.

## Híbrida

A `topologia híbrida`, comum em redes `LAN` e `WAN`, combina **duas ou mais topologias diferentes** em uma única rede.

<p align="center">
<img src="https://blog.xpeducacao.com.br/wp-content/uploads/2022/09/topologia-de-rede-hibrida-1024x585.jpg" width="550px" height="300px">
</p>

Por exemplo, uma rede pode ter uma topologia em estrela para a parte central e uma topologia em barramento para a parte periférica. 

Esta abordagem permite aproveitar as vantagens de cada topologia e adaptar a rede às necessidades específicas da organização.

# Comunicação

A `comunicação` em redes de computadores refere-se à **troca de dados** entre dispositivos por meio de canais de transmissão, como cabos ou ondas de rádio. 

Existem dois modos principais de comunicação: `half-duplex` e `full-duplex`, que definem **como os dados podem ser enviados e recebidos** entre os dispositivos.

## Half-duplex

No modo `half-duplex`, a comunicação ocorre em ambas as direções, mas não ao mesmo tempo, restringindo a troca de dados a uma direção de cada vez.

Isso significa que um dispositivo pode enviar ou receber dados, mas **não pode fazer ambos simultaneamente**. 

`WLANs` e `topologias de barramento` herdadas com hubs Ethernet usam o modo half-duplex.

## Full-duplex

No modo `full-duplex`, a comunicação acontece em ambas as direções ao mesmo tempo, permitindo que os dispositivos **enviem e recebam dados simultaneamente**. 

Esse modo é muito mais eficiente e é usado em redes de maior desempenho, como em comunicações Ethernet modernas e conexões telefônicas. 

Os `switchs` Ethernet operam no modo full-duplex por padrão, mas podem operar no modo half-duplex se estiverem conectados a um dispositivo como um hub Ethernet.

# Métodos de controle de acesso

`LANs` Ethernet e `WLANs` são exemplos de redes multiacesso. Uma rede multiacesso é uma rede que pode ter **dois ou mais** dispositivos finais tentando acessar a rede **simultaneamente**.

Algumas redes multiacesso requerem **regras para controlar** como os dispositivos compartilham a mídia física. Existem dois métodos básicos de controle de acesso para meio físico compartilhado.

## Acesso baseado em controle

Em uma rede multiacesso controlada, cada nó tem seu próprio **tempo para usar o meio**. Isso significa que a rede segue um esquema de controle que **organiza e coordena o acesso ao meio** de transmissão para evitar colisões e conflitos.

## Acesso baseado em contenção 

Em redes multiacesso baseadas em contenção, todos os nós estão operando em `half-duplex`, competindo pelo uso do meio. No entanto, **apenas um dispositivo** pode enviar por vez.

Para **controlar o acesso a esse meio** compartilhado e minimizar colisões, existem dois principais métodos: `CSMA/CD` e `CSMA/CA`.

Exemplos de redes de acesso baseadas em contenção incluem o seguinte:

- LAN sem fio (usa CSMA/CA)
- LAN Ethernet de topologia de barramento legado (usa CSMA/CD)
- LAN Ethernet herdada usando um hub (usa CSMA/CD)

### CSMA/CD 

No `CSMA/CD` (Carrier Sense Multiple Access with Collision Detection), utilizado em redes Ethernet mais antigas com `topologia de barramento`, os dispositivos **verificam se o meio está livre antes de transmitir**.

Se detectarem que o meio está ocupado, aguardam até que ele fique disponível. Caso dois dispositivos **transmitam simultaneamente**, ocorre uma **colisão**. Quando isso acontece, os dispositivos param de transmitir, esperam um **tempo aleatório** e tentam novamente, garantindo a resolução do conflito.

|Etapa|CSMA/CD (Detecção de Colisão)|
|:---:|:---|
|Verificação do meio|O dispositivo verifica se o meio está livre (Carrier Sense)|
|Início da transmissão|Se o meio estiver livre, o dispositivo começa a transmitir dados|
|Detecção de colisão|Enquanto transmite, o dispositivo "escuta" o meio para detectar colisões|
|Ação após colisão|Após detectar uma colisão, o dispositivo envia um sinal para os outros dispositivos e interrompe a transmissão|
|Retransmissão|O dispositivo espera um tempo aleatório e tenta retransmitir os dados|

### CSMA/CA

No `CSMA/CA` (Carrier Sense Multiple Access with Collision Avoidance), usado principalmente em redes sem fio (Wi-Fi), o dispositivo também **verifica se o meio está livre antes de transmitir**.

Se o meio estiver disponível, ele pode enviar uma **solicitação para enviar** (RTS - Request to Send) e, ao receber a **permissão** (CTS - Clear to Send) do receptor, transmite os dados, reduzindo a probabilidade de colisões.

|Etapa|CSMA/CA (Prevenção de Colisão)|
|:---:|:---|
|Verificação do meio|O dispositivo verifica se o meio está livre (Carrier Sense)|
|Solicitação de Transmissão|Se o meio estiver livre, o dispositivo envia uma solicitação de transmissão (RTS - Request to Send)|
|Espera por Autorização|O dispositivo aguarda uma resposta de autorização (CTS - Clear to Send) do destinatário|
|Início da Transmissão|Se a resposta CTS for recebida, o dispositivo começa a transmitir os dados|

# Quadros

A `camada de enlace de dados` prepara os dados recebidos da camada 3 para o transporte pela mídia local, encapsulando-o com um **cabeçalho** e um **trailer** para criar um quadro.

Todos os protocolos da camada de enlace de dados encapsulam os dados dentro do campo de dados do quadro. No entanto, a estrutura do quadro e os campos contidos no cabeçalho e trailer variam de acordo com o protocolo.

Cada quadro contém diversos campos que desempenham funções específicas, e a estrutura desses campos pode variar conforme o protocolo utilizado.

<p align="center">
<img src="https://www.ccna.network/wp-content/uploads/2020/11/Campos-de-quadro-Rede.png" width="450px" height="300px">
</p>

|Campos|Descrição|
|:---:|:---|
|Sinalizadores de início e fim do quadro|Usado para identificar os limites de início e fim do quadro|
|Endereçamento|Indica os dispositivos de origem e destino na mídia|
|Tipo|Identifica o protocolo da camada 3 no campo de dados|
|Controle|Identifica serviços especiais de controle de fluxo|
|Dados|Contém a carga útil do quadro (cabeçalho do pacote, cabeçalho do segmento e os dados)|
|Detecção de Erro|Incluído após os dados para formar o trailer|

## Detecção de erros

Os protocolos da camada de enlace de dados acrescentam um `trailer` ao final de cada quadro. Em um processo chamado `detecção de erros`, o trailer **determina se o quadro chegou sem erros**. Ele coloca um **resumo** lógico ou matemático **dos bits** que compõem o quadro no trailer. 

A camada de enlace de dados adiciona detecção de erro porque os sinais na mídia podem estar sujeitos a interferências, distorções ou perdas que alterariam substancialmente os valores de bits que esses sinais representam.

## Endereços MAC

A camada de enlace provê o endereçamento usado no transporte de quadro através de **dispositivos na mesma rede IP**. Os endereços de dispositivos nesta camada são chamados de endereços físicos.

Esse `endereço físico (MAC)` da camada de enlace de dados está contido no `cabeçalho` do quadro e especifica o **dispositivo de destino** do quadro na rede local.

Normalmente, ele está no **início do quadro**, portanto, a `NIC` pode determinar rapidamente se ela corresponde ao seu próprio endereço antes de aceitar o restante do quadro. O cabeçalho do quadro também pode conter o endereço do **dispositivo de origem** do quadro.

O endereço da camada de enlace de dados é usado **apenas para entrega local**. Os endereços nessa camada não têm significado além da rede local.

























<br><br><br><br><hr>
<div align="center">
    <p><strong>Módulo Anterior:</strong> Camada de enlace de dados</p>
    <p><strong>Próximo Módulo:</strong> Switching Ethernet</p>
    <a href="#redes-de-computadores-i">Voltar ao topo &#8593;</a>
</div>
<hr><br><br><br><br>


















# Definição

Ethernet é uma tecnologia fundamental para redes locais `LAN`, oferecendo um **método padronizado** para **conectar dispositivos** e permitir a troca de dados. A Ethernet utiliza comunicações com fios, incluindo par trançado, ligações de fibra óptica e cabos coaxiais.

Ela opera na `camada de enlace de dados` e na `camada física`. É uma **família de tecnologias de rede** definidas nos padrões **IEEE 802.2** e **802.3**.

<p align="center">
<img src="https://www.ccna.network/wp-content/uploads/2020/11/Padroes-Ethernet-no-Sublayer-MAC.png" width="550px" height="400px">
</p>

Ethernet herdada usando uma topologia de `barramento` ou `hubs`, é um meio compartilhado e `half-duplex`. Ethernet sobre um meio half-duplex usa um **método de acesso baseado em contenção** (CSMA/CD). As LANs Ethernet de hoje usam switches que operam em `full-duplex`. As comunicações full-duplex com switches Ethernet **não exigem** controle de acesso através do CSMA/CD.

A `subcamada MAC` é responsável pelo **encapsulamento de dados** e **acesso à mídia**. O `encapsulamento` de dados IEEE 802.3 inclui o seguinte:

- Quadro Ethernet - Esta é a estrutura interna do quadro Ethernet.
- Endereçamento Ethernet - O quadro Ethernet inclui um endereço MAC de origem e de destino.
- Detecção de erro Ethernet - O quadro Ethernet inclui um trailer de sequência de verificação de quadros (FCS) usado para detecção de erros.

# Quadro Ethernet

O tamanho mínimo de quadro Ethernet é **64 bytes** e o máximo é **1518 bytes**. Isso inclui todos os bytes do campo de endereço MAC de destino através do campo FCS (Frame Check Sequence). Se o tamanho de um quadro transmitido for **menor que o mínimo** ou **maior que o máximo**, o dispositivo receptor **descarta** o quadro.

<p align="center">
<img src="https://www.ccna.network/wp-content/uploads/2020/11/Campos-Ethernet-Frame.png" width="750px" height="350px">
</p>

|Campos|Descrição|
|:---:|:---|
|Preâmbulo|O preâmbulo (7 bytes) permite que o receptor se ajuste ao sinal e esteja pronto para processar o quadro que está prestes a ser recebido|
|SFD|O delimitador de quadro (1 byte) é utilizado para indicar o início real do quadro. Ele sinaliza ao dispositivo receptor que os dados que se seguem fazem parte de um quadro Ethernet|
|Endereço MAC de destino|Este campo (6 bytes) é o identificador do destinatário desejado. Se houver uma correspondência, o aceita o quadro|
|Endereço MAC de origem|Esse campo (6 bytes) identifica a NIC ou interface de origem do quadro|
|Tipo/Comprimento|Um campo (2 bytes) que indica o protocolo da camada superior encapsulado no quadro, com valores comuns como 0x800 para IPv4 e 0x86DD para IPv6|
|Dados|Este campo (46 - 1500 bytes) contém os dados da camada superior, como um pacote IPv4|
|FCS|A sequência de verificação de quadro (4 bytes) utiliza uma verificação de redundância cíclica (CRC) para detectar erros. Se os cálculos não coincidem, o quadro é descartado, indicando possível alteração nos dados|

## Processamento de quadros Ethernet

O endereço MAC é codificado na memória somente leitura (ROM) na NIC. **Quando o computador é inicializado**, a NIC copia seu endereço MAC da ROM para a RAM. 

Quando uma NIC recebe um quadro Ethernet, examina o **endereço MAC de destino** para verificar se corresponde ao endereço MAC físico armazenado na RAM. Se não houver correspondência, o dispositivo descartará o quadro. 

Caso haja, ele passará o quadro para cima nas camadas OSI, onde o processo de desencapsulamento ocorre.

**Qualquer dispositivo** que seja a origem ou o destino de um quadro Ethernet terá uma NIC Ethernet e, portanto, um endereço MAC.

# Endereço MAC

O `endereço MAC`, ou endereço Ethernet, é usado para **identificar os dispositivos físicos** de origem e destino (NICs) no segmento de rede local. O endereçamento MAC fornece um método para identificação de dispositivo na camada de enlace de dados do modelo OSI.

Um endereço MAC Ethernet consiste em um **valor binário de 48 bits**. `Hexadecimal` é usado para **identificar um endereço Ethernet** porque um único dígito hexadecimal representa quatro bits binários. Portanto, um endereço MAC Ethernet de 48 bits pode ser expresso usando apenas 12 valores hexadecimais.

Todos os endereços MAC **devem ser exclusivos** do dispositivo Ethernet ou da interface Ethernet. Para garantir isso, todos os fornecedores que vendem dispositivos Ethernet **devem se registrar** no `IEEE` para obter um código hexadecimal exclusivo chamado `identificador exclusivo organizacionalmente` (OUI).

Quando um fornecedor atribui um endereço MAC a um dispositivo ou interface Ethernet, o fornecedor deve fazer o seguinte:

1. Use sua OUI atribuída como os primeiros 6 dígitos hexadecimais.
2. Atribua um valor exclusivo nos últimos 6 dígitos hexadecimais.

Portanto, um endereço MAC Ethernet consiste em um código OUI do fornecedor hexadecimal seguido por um valor hexadecimal atribuído ao fornecedor.

Na Ethernet, são utilizados diferentes endereços MAC para comunicação unicast, broadcast e multicast da Camada 2.

## Endereço MAC unicast

Um `endereço unicast` identifica um dispositivo específico em uma rede. Quando um quadro Ethernet é enviado para um endereço MAC unicast, ele é entregue apenas ao dispositivo que possui esse endereço.

O processo que um host de origem usa para determinar o endereço MAC de destino associado a um endereço IPv4 é conhecido como `ARP` (Address Resolution Protocol). Para um endereço IPv6, é conhecido como `ND` (Neighbour Discovery Discovery).

O endereço MAC de origem **deve ser sempre** unicast.

## Endereço MAC multicast

Um `endereço multicast` é utilizado para enviar dados a um **grupo específico** de dispositivos. O primeiro byte de um endereço MAC multicast **sempre começa com 01-00-5E**, seguido pelo identificador do grupo. 

Apenas os dispositivos que fazem parte desse grupo específico processam o quadro multicast.

Protocolos de roteamento e outros protocolos de rede usam endereçamento multicast. Aplicativos como software de vídeo e imagem também podem usar endereçamento multicast, embora aplicativos multicast não sejam tão comuns.

## Endereço MAC broadcast

Um `endereço broadcast` é usado para enviar dados para todos os dispositivos em uma rede local (LAN). O endereço MAC de broadcast **é sempre** FF:FF:FF:FF:FF:FF.

Quando um quadro é enviado para esse endereço, **todos os dispositivos conectados à mesma rede** recebem o quadro, independentemente do seu endereço MAC específico.

# Tabela de endereçamentos MAC

Um switch Ethernet da camada 2 usa endereços MAC da camada 2 para **tomar decisões de encaminhamento**. Um switch Ethernet examina sua `tabela de endereços MAC` para tomar uma decisão de encaminhamento para cada quadro.

O switch **cria a tabela de endereços MAC dinamicamente** examinando o endereço MAC de origem dos quadros recebidos em uma porta. O switch **encaminha** os quadros procurando uma correspondência entre o **endereço MAC de destino no quadro** e uma **entrada na tabela de endereços MAC**.

|Porta|Endereço|
|:---:|:---:|
|1|00-0A-0A-23-1F-12|
|2|AA-O2-FF-00-0D-57|

## Aprendizado

**Todo quadro que entra em um switch é verificado** quanto ao aprendizado de novas informações. Isso é feito examinando o **endereço MAC de origem** do quadro e o **número da porta** em que o quadro entrou no switch. 

Se o endereço MAC de origem **não existe**, **é adicionado à tabela** juntamente com o número da porta de entrada. 

Se o endereço MAC de origem **existir**, o switch **atualizará o cronômetro** de atualização para essa entrada na tabela.

## Encaminhamento

Se o endereço MAC de destino for um `endereço unicast`, o switch procurará uma correspondência em sua tabela de endereços MAC.

Se o endereço MAC de destino **estiver** na tabela, ele encaminhará o quadro pela **porta especificada**.

Se o endereço MAC de destino **não estiver** na tabela, o switch encaminhará o quadro por **todas as portas**, exceto a de entrada. Isso é chamado de unicast desconhecido.



















<br><br><br><br><hr>
<div align="center">
    <p><strong>Módulo Anterior:</strong> Switching Ethernet</p>
    <p><strong>Próximo Módulo:</strong> Camada de rede</p>
    <a href="#redes-de-computadores-i">Voltar ao topo &#8593;</a>
</div>
<hr><br><br><br><br>


















# Fundamentos

A `camada de rede`, ou Camada OSI 3, fornece serviços para **gerenciar o endereçamento** e o **roteamento** de pacotes de dados entre **diferentes redes**. Ela determina como os dados são enviados de um dispositivo de origem para um dispositivo de destino, potencialmente através de múltiplas redes.

O IP versão 4, *IPv4*, e IP versão 6, `IPv6`, são os principais protocolos de comunicação de camada de rede. Outros protocolos de camada de rede incluem protocolos de roteamento, como `OSPF` (Open Shortest Path First) e protocolos de mensagens, como `ICMP` (Internet Control Message Protocol).

Ao contrário da camada de enlace de dados, que utiliza `endereços físicos` (como endereços MAC), a camada de rede utiliza **endereços lógicos**, como endereços `IP`. Isso permite que os dispositivos sejam **identificados em uma rede global**, como a Internet.

Para realizar comunicações de ponta a ponta através dos limites da rede, os protocolos de camada de rede executam quatro operações básicas:

|Operações|Descrição|
|:---:|:---|
|Endereçamento|Os dispositivos finais devem ser configurados com um endereço IP exclusivo para identificação na rede|
|Encapsulamento|A camada de rede encapsula a unidade de dados de protocolo (PDU) da camada de transporte em um pacote|
|Roteamento|A camada de rede fornece serviços para direcionar os pacotes para um host de destino em outra rede. Para trafegar para outras redes, o pacote deve ser processado por um roteador|
|Desencapsulamento|Desencapsula o pacote recebido, se o endereço IP de destino corresponder com o próprio endereço IP|

# Endereçamento

O `endereçamento` na camada de rede envolve a **atribuição de endereços IP** a dispositivos, permitindo que pacotes de dados sejam enviados e recebidos de forma correta. 

**Cada dispositivo** em uma rede recebe um **endereço IP único**, que serve como seu identificador. O endereço IP é crucial para **definir a origem e o destino dos pacotes**, permitindo que os dados sejam encaminhados pelos roteadores até o destinatário correto. 

O endereçamento IP pode ser tanto `IPv4` quanto `IPv6`, com o IPv6 oferecendo uma maior capacidade de endereçamento.

# Encapsulamento

A camda de rede encapsula o **segmento** da `camada de transporte` ou outros dados adicionando um **cabeçalho IP**. O cabeçalho IP é usado para entregar o pacote ao host de destino.

O cabeçalho IP é examinado por dispositivos de Camada 3, **roteadores** e **switches**, à medida que viaja através de uma rede até seu destino.

É importante notar que as informações de endereçamento IP **tendem a permanecer as mesmas** desde o momento em que o pacote sai do host de origem até chegar ao host de destino.

# IP

O IP foi desenvolvido como um protocolo com baixa sobrecarga. Ele fornece apenas as funções necessárias para **enviar um pacote de uma origem a um destino** por um sistema interconectado de redes. 

O protocolo não foi projetado para rastrear e gerenciar o fluxo de pacotes. Essas funções, se exigido, são realizadas por outros protocolos em outras camadas, principalmente TCP na Camada 4.

### Sem conexão

O IP opera de forma "sem conexão", o que significa que não estabelece uma conexão dedicada antes de enviar pacotes. Em vez disso, **cada pacote é enviado independentemente**, sem uma sessão pré-estabelecida entre o remetente e o destinatário. 

Essa abordagem torna o IP mais leve e rápido, já que **não há necessidade** de configurar uma conexão antes de enviar dados.

### Melhor esforço

O IP é descrito como um protocolo "melhor esforço", o que significa que **não oferece garantias sobre a entrega de pacotes**. 

Não há mecanismo para garantir que os pacotes sejam entregues ou que sejam entregues na ordem correta. Pacotes podem ser perdidos, duplicados ou chegar fora de sequência, e o IP não tem como detectar ou corrigir esses problemas. 

Essa característica é uma das razões pelas quais outros protocolos, como o `TCP`, são frequentemente usados em conjunto com o IP para aplicações que exigem entrega confiável.

### Independente da mídia

O IP é projetado para ser **independente do meio físico** utilizado para transmitir os dados. Isso significa que ele pode funcionar sobre diferentes tipos de tecnologias de rede, como cabos de cobre, fibra ótica ou conexões sem fio. 

Essa flexibilidade permite que o IP seja amplamente adotado em várias plataformas e tecnologias de rede, facilitando a comunicação entre dispositivos diversos.

## IPv4

O `IPv4` é um dos principais protocolos de comunicação de camada de rede. O **cabeçalho** do pacote IPv4 é usado para **garantir** que esse pacote seja **entregue para sua próxima parada** no caminho para seu dispositivo final de destino.

Os valores binários de cada campo do cabeçalho **identificam várias configurações** do pacote IP.

<p align="center">
<img src="https://www.ccna.network/wp-content/uploads/2020/12/Campos-no-cabecalho-do-pacote-IPv4.png" width="550px" height="400px">
</p>

Campos significativos no cabeçalho IPv4 incluem o seguinte:

|Campos|Descrição|
|:---:|:---|
|Versão|Contém um valor binário de 4 bits definido como 0100 que identifica isso como um pacote IPv4|
|Serviços diferenciados (DS)|Anteriormente chamado de campo tipo de serviço (ToS), o campo DS é um campo de 8 bits usado para determinar a prioridade de cada pacote|
|Tempo de vida (TTL)|Contém um valor binário de 8 bits usado para limitar a vida útil de um pacote que é diminuído em um cada vez que o pacote é processado por um roteador|
|Protocolo|Este campo é usado para identificar o próximo nível de protocolo. O valor binário de 8 bits indica o tipo de carga de dados que o pacote está carregando|
|Endereço IPv4 de origem|Contém um valor binário de 32 bits que representa o endereço IPv4 de origem do pacote|
|Endereço IPv4 de destino|Contém um valor binário de 32 bits que representa o endereço IPv4 de destino do pacote|

Para mais informações sobre endereçamento IPv4, [clicar aqui](#estrutura).

## IPv6

O `IPv6` é a **versão mais recente** do protocolo de comunicação da camada de rede, projetada para superar as limitações do IPv4. 

Uma das principais motivações para o desenvolvimento do IPv6 foi o esgotamento dos **endereços disponíveis no IPv4**, que suporta cerca de 4 bilhões de endereços. O IPv6, por outro lado, utiliza **endereços de 128 bits**, permitindo uma quantidade praticamente ilimitada de endereços.

Com um número tão grande de endereços IPv6 públicos, o `NAT` entre um endereço IPv4 privado e um IPv4 público não é necessário. Isso evita alguns dos problemas induzidos por NAT enfrentados por aplicativos que exigem conectividade de `ponta a ponta`.

O cabeçalho IPv6 foi simplificado com menos campos:

<p align="center">
<img src="https://www.ccna.network/wp-content/uploads/2020/12/Cabecalho-de-pacote-IPv6.png" width="550px" height="400px">
</p>

Os campos no cabeçalho do pacote IPv6 incluem o seguinte:

|Campos|Descrição|
|:---:|:---|
|Versão|Este campo contém um valor binário de 4 bits definido como 0110 que identifica isso como um pacote IP versão 6|
|Classe de tráfego|Este campo de 8 bits é equivalente ao campo DSv (Serviços diferenciados de IPv4)|
|Etiqueta de fluxo|Este campo de 20 bits sugere que todos os pacotes com a mesma etiqueta de fluxo recebam o mesmo tipo de manipulação pelos roteadores|
|Comprimento da carga útil|Este campo de 16 bits indica o comprimento da parte dos dados ou da carga útil do pacote IPv6, não incluindo o comprimento do cabeçalho IPv6|
|Próximo cabeçalho|Este campo de 8 bits é equivalente ao campo Protocolo IPv4. Ele exibe o tipo de carga de dados que o pacote está carregando|
|Limite de salto|Este campo de 8 bits substitui o campo TTL IPv4. Esse valor é subtraído de um por cada roteador que encaminha o pacote|
|Endereço IPv6 de origem|Este campo de 128 bits identifica o endereço IPv6 do host de envio|
|Endereço IPv6 de destino|Este campo de 128 bits identifica o endereço IPv6 do host de recebimento.
Um pacote IPv6|

Ao contrário de IPv4, os roteadores **não fragmentam** os pacotes IPv6 roteados.

# Roteamento

O `roteamento` é um processo que envolve a **identificação do melhor caminho** para enviar pacotes de dados entre dispositivos. 

Em **redes locais**, dispositivos como `switches` ou pontos de acesso sem fio facilitam a comunicação entre hosts. Isso permite que pacotes sejam enviados **diretamente entre eles**, **sem a necessidade de roteamento**, quando os dispositivos estão na mesma rede.

Para se comunicar com hosts **fora da rede local,** o **roteamento se torna necessário**. O pacote é **enviado ao gateway padrão**, que é o roteador conectado à rede local. O roteador analisa sua `tabela de roteamento` para determinar o melhor caminho para o destino remoto, encaminhando o pacote através da rede e passando por vários roteadores até que ele chegue ao host de destino.

|Rotas (IP de destino)|Máscara|Gateway (IP do roteador)|Próximo Salto|Tipo|
|:---:|:---:|:---:|:---:|:---:|
|192.168.10.0|255.255.255.0|192.168.10.1|G0/0/0|Estática|
|209.165.200.224|	255.255.255.252|	209.165.200.225|	G0/0/1|	Estática|
|10.1.1.0|	255.255.255.0|	192.168.20.2|	via R2|	Dinâmica|
|0.0.0.0|	0.0.0.0|	192.168.10.254|	via R2|	Estática|

`Roteamento estático` e `roteamento dinâmico` são os dois principais métodos usados para **configurar** e **atualizar** as tabelas de roteamento em roteadores.

## Gateway Padrão

O `gateway padrão` é o dispositivo de rede, roteador ou switch da Camada 3, que pode rotear o tráfego para outras redes. O tráfego não pode ser encaminhado para fora da rede local se **não houver gateway padrão**, o endereço de gateway padrão **não estiver configurado** ou o gateway padrão estiver **inativo**.

Comparando a rede com uma sala, o gateway padrão é a porta. Se você quiser ir para outra sala (rede), vai precisar encontrar essa porta.

A configuração do gateway padrão cria uma **rota padrão** na tabela de roteamento do host. Uma `rota padrão` é a rota ou o caminho que o computador usa quando tenta **entrar em contato** com uma rede remota.

## Tabela de roteamento

A tabela de roteamento é uma ferramenta crítica utilizada tanto por hosts quanto por roteadores para gerenciar a entrega de pacotes de dados em uma rede.

Em um host do Windows, o comando **route print** ou **netstat -r** pode ser usado para **exibir a tabela de roteamento** do host. Ambos os comandos geram a mesma saída.

O comando, executado no modo EXEC privilegiado, **show ip route** é usado para exibir a tabela de roteamento IPv4 em um roteador Cisco IOS.

### Hosts

Para determinar se o pacote deve ser enviado a um host `local` ou `remoto`, o dispositivo de origem utiliza diferentes métodos. Em `IPv4`, ele usa sua **máscara de sub-rede** e seu **próprio endereço IP** para verificar se o endereço de destino está na mesma rede. Em `IPv6`, os roteadores locais anunciam o **prefixo da rede**, permitindo que os dispositivos identifiquem se o destino está na mesma rede.

A tabela de roteamento em hosts inclui uma `rota padrão`, que é o **gateway padrão**, responsável por encaminhar pacotes destinados a redes remotas. Ela também contém informações sobre os **dispositivos na rede local** e **como alcançar o gateway padrão**. 

|Destino|Máscara de Sub-rede|Gateway|
|:---:|:---:|:---:|
|192.168.10.0|255.255.255.0|0.0.0.0|
|0.0.0.0|0.0.0.0|192.168.10.1|

No IPv4, o host recebe o endereço **IPv4 do gateway padrão dinamicamente do DHCP** (Dynamic Host Configuration Protocol) ou configurado manualmente. No IPv6, o roteador anuncia o endereço de gateway padrão ou o host pode ser **configurado manualmente**.

Ao enviar pacotes, um host verifica sua tabela para determinar se o destino está na mesma rede local ou se deve usar o gateway para acessar redes externas.

### Roteadores

Um `roteador` mantém uma tabela que não apenas registra informações sobre **redes locais** e **gateways padrão**, mas também contém informações sobre **várias rotas para diferentes redes remotas**. Essa tabela é **constantemente atualizada** usando protocolos de roteamento dinâmico. 

Os roteadores utilizam suas tabelas para **determinar o melhor próximo salto** para cada pacote, assegurando que ele siga o **caminho mais curto** ou menos congestionado até o destino final. O roteador **examina o endereço IP de destino** do pacote e pesquisa sua **tabela de roteamento** para determinar para onde encaminhar o pacote.

|Rotas (IP de destino)|Próximo salto|
|:---:|:---:|
|192.168.10.0 /24|G0/0/0|
|209.165.200.224 /30|G0/0/1|
|10.1.1.0 /24|via R2|
|Rota padrão 0.0.0.0 /0|via R2|

A tabela de roteamento armazena três tipos de entradas de rota:

- `Redes conectadas diretamente` - Essas são redes às quais o roteador está **diretamente conectado por meio de suas interfaces**. Quando uma interface de roteador está configurada com um endereço IP e está ativa, o roteador automaticamente adiciona uma entrada de rota para essa rede na sua tabela de roteamento.
- `Redes remotas` - Essas entradas de rotas de rede são conectadas a outros roteadores. Os roteadores aprendem sobre redes remotas sendo inseridas manualmente, **usando rotas estáticas**, ou dinamicamente, **usando um protocolo de roteamento dinâmico**.
- `Rota padrão` — A rota padrão é uma "rota de escape" para pacotes cujo **destino não corresponde a nenhuma outra entrada** na tabela de roteamento. O roteador encaminha esses pacotes para um gateway de último recurso, que é **normalmente outro roteador**.

`Roteamento estático` e `roteamento dinâmico` são os dois principais métodos usados para **configurar** e **atualizar** as tabelas de roteamento em roteadores.

## Roteamento estático

No `roteamento estático`, o administrador de rede **configura manualmente as rotas** na tabela de roteamento.. A rota estática inclui o **endereço de rede remota** e o **endereço IP do roteador** de salto seguinte.

Se houver uma alteração na topologia da rede, a rota estática **não será atualizada automaticamente** e **deverá ser reconfigurada manualmente**.

Uma rota estática é apropriada para uma **rede pequena** e quando há poucos ou nenhum vínculo redundante.

Uma rota estática é comumente usada com um **protocolo de roteamento dinâmico** para configurar uma `rota padrão`.

## Roteamento dinâmico

No `roteamento dinâmico`, os roteadores usam **protocolos de roteamento** para trocar informações sobre a rede e automaticamente atualizar suas tabelas de roteamento conforme a topologia da rede muda.

A configuração básica requer apenas que o administrador de rede habilite as `redes conectadas diretamente` dentro do protocolo de roteamento dinâmico. O protocolo de roteamento dinâmico fará automaticamente o seguinte:

- Descobrir redes remotas.
- Manter as informações de roteamento atualizadas.
- Escolha o melhor caminho para as redes de destino.
- Tente encontrar um novo melhor caminho se o caminho atual não estiver mais disponível.

Quando um roteador é configurado manualmente com uma rota estática ou aprende sobre uma rede remota dinamicamente usando um protocolo de roteamento dinâmico, o endereço de rede remota e o endereço de próximo salto são inseridos na tabela de roteamento IP.

























<br><br><br><br><hr>
<div align="center">
    <p><strong>Módulo Anterior:</strong> Camada de rede</p>
    <p><strong>Próximo Módulo:</strong> Roteador básico</p>
    <a href="#redes-de-computadores-i">Voltar ao topo &#8593;</a>
</div>
<hr><br><br><br><br>





















# Roteador básico

# Comandos básicos

Um dispositivo Cisco IOS é compatível com muitos comandos. Cada comando do IOS possui um formato ou sintaxe específica e pode ser executado apenas no modo apropriado.

<p align="center">
<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjNTuuuCRsecEA_XT0d2EAgaiXHehfSyN8UbGhrN6tJhdYPcW600xEbY3-CBSTwBFdYKKlbeGwl4wedBMbsBvh4PE1mxajR3neFORJho-X3g3OtM5mw2ETsLBLoM8L_svT8EnZgLICbU-M/s1600/estrutura_comandos.png" width="550px" height="300px">
</p>

A sintaxe fornece o padrão, ou formato, que deve ser usado ao inserir um comando.

Um comando pode exigir um ou mais argumentos. Para determinar as palavras-chave e os argumentos necessários para um comando, consulte a sintaxe de comando. 

## Modo de configuração

Como recurso de segurança, o software Cisco IOS separa o acesso de gerenciamento nestes dois modos de comando.

- `EXEC de usuário` - Ele permite apenas um número limitado de comandos de monitoramento básicos, mas não permite a execução de nenhum comando que possa alterar a configuração do dispositivo. **Identificado pelo prompt que termina com o símbolo '>'**.
- `EXEC privilegiado` - Ele permite executar comandos de configuração mais altos e permite acesso à outros modos de configuração. **Identificado pelo prompt que termina com o símbolo '#'**.

Para configurar o dispositivo, o usuário deve entrar no modo de configuração global. O Modo de Configuração Global é o nível mais alto de configuração. Permite a configuração de aspectos gerais do dispositivo, como o nome do dispositivo, a senha, e as interfaces.

O modo de configuração global é **identificado por um prompt que termina com "(config)#"** após após o nome do dispositivo.

No modo de configuração global, o usuário pode inserir diferentes modos de subconfiguração. Cada um desses modos permite a configuração de uma parte particular ou função do dispositivo IOS.

- `Modo de configuração de linha` - Usado para configurar o acesso ao console, SSH, Telnet ou AUX.
- `Modo de configuração da interface` - Usado para configurar uma porta de switch ou interface de rede do roteador.

Quando a CLI é usada, o modo é identificado pelo prompt da linha de comandos exclusivo para esse modo. O prompt padrão para o `modo de configuração de linha`a é **Router(config-line)#** e o prompt padrão para o `modo de configuração da interface` é **Router(config-if)#**.

## Navegação entre os modos do IOS

Para configurar dispositivos Cisco, é necessário entender a navegação entre diferentes modos de configuração na CLI.

Para passar do modo EXEC do usuário para o modo EXEC privilegiado, use o comando **enable**. Use o comando **disable** do modo EXEC privilegiado para retornar ao modo EXEC do usuário.

Para entrar no modo de configuração global, use o comando **configure terminal**, estando no modo EXEC privilegiado. Para retornar ao modo EXEC privilegiado, digite o comando **exit**.

Para entrar no modo de subconfiguração de linha, use o comando **line** seguido pelo **tipo** e **número da linha de gerenciamento** que deseja acessar. Use o comando **exit** para sair de um modo de subconfiguração e retornar ao modo de configuração global.

```txt
Router(config)# line console 0
Router(config-line)# exit
Router(config)#
```

Para entrar no modo de subconfiguração de interface, use o comando **interface** seguido pelo **nome da interface** que deseja acessar. Use o comando **exit** para sair de um modo de subconfiguração e retornar ao modo de configuração global.

```txt
Router(config-line)# interface GigabitEthernet 0/1
Router(config-if)#
```

Para passar de qualquer modo de subconfiguração para o modo EXEC privilegiado, insira o comando **end**.

## Resumo

|Modo|Prompt|Comando para Entrar|
|:---|:---|:---|
|EXEC do usuário|**Router>**||
|EXEC privilegiado|**Router#**|`enable`|
|Configuração global|**Router(config)#**|`configure terminal`|
|Configuração de linha|**Router(config-line)#**|`line [tipo] [número]`|
|Configuração da interface|**Router(config-if)#**|`interface [nome]`|

# Configuração primária do roteador

## Nome do roteador

Por padrão, todos os dispositivos recebem um nome padrão de fábrica. Por exemplo, um roteador Cisco IOS é “Router“.

Uma organização deve escolher uma convenção de nomenclatura que torne fácil e intuitivo identificar um dispositivo específico.

No modo de configuração global, digite o comando **hostname** seguido pelo **nome do host**.

```txt
Router# configure terminal
Router(config)# hostname R1
Router(config)#
```

## Configurar senhas do roteador

Quando você se conecta inicialmente a um dispositivo, você está no modo EXEC do usuário. Este modo é protegido usando o console.

No modo de configuração de linha, digite o comando **password [senha]** para configurar uma senha para o modo EXEC do usuário. Por fim, digite **login** habilitar a autenticação de senha.

O acesso ao console agora exigirá uma senha antes de permitir o acesso ao modo EXEC do usuário.

```txt
Router# configure terminal
Router(config)# line console 0
Router(config-line)# password cisco
Router(config-line)# login
Router(config-line)# end
Router#
```

Para proteger o acesso EXEC privilegiado, use o comando **enable secret [senha]** no modo de configuração global.

```txt
Router# configure terminal
Router(config)# enable secret class
Router(config)# exit
Router#
```

Para proteger o acesso remoto via `SSH` ou `Telnet`, digite o comando **password [senha]**, depois digite **login** habilitar a autenticação de senha. Por fim, digite **transport input ssh telnet** para habilitar o acesso SSH e Telnet.

```txt
Router# configure terminal
Router(config-line)# line vty 0 4
Router(config-line)# password password
Router(config-line)# login
Router(config-line)# transport input {ssh | telnet}
```

## Criptografar senhas do roteador

Os arquivos `startup-config` e `running-config` exibem a maioria das senhas em texto simples. Esta é uma ameaça à segurança, porque qualquer pessoa pode descobrir as senhas se tiver acesso a esses arquivos.

Para criptografar todas as senhas de texto simples, use o comando **service password-encryption**.

O comando aplica criptografia fraca a todas as senhas não criptografadas.

O propósito deste comando é proibir que indivíduos não autorizados vejam as senhas no arquivo de configuração.

```txt
Router# configure terminal
Router(config)# service password-encryption
Router(config)#
```

## Mensagens de banner do roteador

Embora a exigência de senhas seja uma maneira de manter pessoal não autorizado fora da rede, é vital fornecer um método para declarar que apenas pessoal autorizado deve tentar acessar o dispositivo.

Banners podem ser uma parte importante do processo legal caso alguém seja processado por invadir um dispositivo. 

Para criar uma mensagem de banner, use o comando de configuração global **banner motd #[mensagem]#**.

O '#' na sintaxe do comando é denominado caractere de delimitação. Ele é inserido antes e depois da mensagem.

```txt
Router# configure terminal
Router(config)# banner motd #acesso autorizado apenas com senha#
```

# Configuração das interfaces do roteador

Os roteadores não podem ser acessados por dispositivos finais até que as interfaces estejam configuradas.

```txt
Router# configure terminal
Router(config)# interface type-and-number
Router(config-if)# description description-text
Router(config-if)# ip address ipv4-address subnet-mask
Router(config-if)# ipv6 address ipv6-address/prefix-length
Router(config-if)# no shutdown
```

Embora o comando **description** não seja necessário para habilitar uma interface, é recomendável usá-lo. Isso pode ser útil na solução de problemas em redes de produção, fornecendo informações sobre o tipo de rede conectada.

O uso do comando **no shutdown** ativa a interface e é semelhante a ligar a interface. A interface também deve ser conectada a outro dispositivo, para que a `camada física` esteja ativa.

## Verificação da configuração

Há vários comandos que podem ser usados para verificar a configuração de uma interface. O mais útil deles é o comandos **show ip interface brief** e **show ipv6 interface brief**.

|Comandos|Descrição|
|:---:|:---|
|show ip interface brief|A saída exibe todas as interfaces, seus endereços IP e seus status atual. No entanto, este exibirá apenas as informações de endereçamento IPv4|
|show ipv6 interface brief|A saída exibe todas as interfaces, seus endereços IP e seus status atual|
|show ip route|Exibe o conteúdo das tabelas de roteamento IP armazenadas na RAM. No entanto, este exibirá apenas as informações de endereçamento IPv4|
|show ipv6 route|Exibe o conteúdo das tabelas de roteamento IP armazenadas na RAM|
|show interfaces|Exibe estatísticas para todas as interfaces no dispositivo. No entanto, este exibirá apenas as informações de endereçamento IPv4|
|show ip interfaces|Exibe as estatísticas do IPv4 para todas as interfaces em um roteador. No entanto, este exibirá apenas as informações de endereçamento IPv4|
|show ipv6 interface|Exibe as estatísticas do IPv6 para todas as interfaces em um roteador|

# Configuração do gateway padrão do roteador

Se sua rede local tiver apenas um roteador, **será o roteador gateway** e todos os hosts e switches da rede deverão ser configurados com essas informações. Se sua rede local tiver vários roteadores, você deverá **selecionar um deles** para ser o roteador de gateway padrão.

O endereço do gateway padrão geralmente é o endereço da interface do roteador associado à rede local do host.

## Gateway padrão em um switch

Para se conectar e gerenciar um switch em uma rede IP local, ele deve ter uma interface virtual de switch (SVI) configurada. O SVI é configurado com um endereço `IPv4` e uma `máscara de sub-rede` na LAN local. O switch também deve ter um endereço de `gateway padrão` configurado para gerenciar remotamente o switch de outra rede.

O endereço de gateway padrão geralmente é configurado em todos os dispositivos que se **comunicam além da rede local**.

Para configurar um gateway padrão IPv4 em um switch, use o comando de configuração global **ip default-gateway [ip-address]**. O ip-address que está configurado é o endereço IPv4 da interface do roteador local conectada ao switch.

```txt
Switch# configure terminal
Switch(config)# ip default-gateway ip-address
```



























<br><br><br><br><hr>
<div align="center">
    <p><strong>Módulo Anterior:</strong> Roteador básico</p>
    <p><strong>Próximo Módulo:</strong> Endereçamento IPv4</p>
    <a href="#redes-de-computadores-i">Voltar ao topo &#8593;</a>
</div>
<hr><br><br><br><br>



















# Estrutura

Um endereço `IPv4` é um endereço hierárquico de 32 bits, composto por uma **parte da rede** e uma **parte do host**.

Os bits na parte de rede do endereço devem ser iguais em todos os dispositivos que **residem na mesma rede**.

Os bits na parte de host do endereço devem ser exclusivos para **identificar um host específico** dentro de uma rede.

# Máscara de sub-rede

Uma `máscara de sub-rede` IPv4 é um valor de 32 bits que **diferencia** a parte da rede do endereço da parte do host.

Ela não contém a parte da rede ou host de um endereço IPv4, apenas informa ao computador onde procurar cada parte do endereço IPv4.

<p align="center">
  <img src="https://www.initialboard.com/wp-content/uploads/2023/02/IP-address-melalui-bilangan-bine.png" width="500px" height="300px">
</p>

Para identificar as partes da rede e do host de um endereço IPv4, a máscara de sub-rede é comparada com o endereço IPv4 **bit por bit**, da **esquerda para a direita**.

# Comprimento do prefixo

O `comprimento do prefixo` é o **número de bits definido como 1 na máscara de sub-rede**. Está escrito em "notação de barra", que é anotada por uma barra (/) seguida pelo número de bits definido como 1.

|Máscara de Sub-Rede|Endereço de 32 bits|Comprimento do Prefixo|
|:---:|:---:|:---:|
|255.0.0.0|11111111.00000000.00000000.00000000|/8|
|255.255.0.0|11111111.11111111.00000000.00000000|/16|
|255.255.255.0|11111111.11111111.11111111.00000000|/24|
|255.255.255.128|11111111.11111111.11111111.10000000|/25|
|255.255.255.192|11111111.11111111.11111111.11000000|/26|
|255.255.255.224|11111111.11111111.11111111.11100000|/27|
|255.255.255.240|11111111.11111111.11111111.11110000|/28|
|255.255.255.248|11111111.11111111.11111111.11111000|/29|
|255.255.255.252|11111111.11111111.11111111.11111100|/30|

# Tipos de endereços IPv4

Dentro de cada rede há três tipos de endereços IP:

- Endereço de rede.
- Endereços de host.
- Endereço de broadcast.

<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRDS8X01Ie1u38JjjNv__88KL8bhy0ahyuV7w&s" width="500px" height="300px">
</p>

|Endereços|Descrição|
|:---:|:---|
|Endereço de rede|Representa uma rede específica. Definido com todos os bits sendo 0 na parte de host do endereço IP|
|Endereço de host|Endereços que podem ser atribuídos a um dispositivo. Podem ter quase qualquer combinação de bits na parte do host|
|Endereço de broadcast|Usado quando é necessário acessar todos os dispositivos na rede IPv4. Definido com todos os bits sendo 1 na parte de host do endereço IP. Roteadores não propagam broadcasts.|

## IPv4 privados e públicos

Alguns endereços IPv4 **não podem ser usados** para sair para a Internet, e outros são especificamente alocados para roteamento para a internet.

- IPv4 públicos: são endereços roteados globalmente entre os roteadores do provedor de serviços de Internet (ISP).
- IPv4 privados: não são endereços exclusivos e podem ser usados internamente em qualquer rede.

|Endereço de rede privado|Intervalo de endereços privados|
|:---:|:--:|
|10.0.0.0/8|10.0.0.0 - 10.255.255.255|
|172.16.0.0/12|172.16.0.0 - 172.31.255.255|
|192.168.0.0/16|192.168.0.0 - 192.168.255.255|

A maioria das redes internas usam endereços IPv4 privados para endereçar todos os dispositivos internos. No entanto, os endereços privados **não são globalmente roteáveis**.

Para comunicações fora da rede local, utiliza-se o [NAT](#nat) para converter um IPv4 privado em um IPv4 público, permitindo o pacote ser roteado globalmente até o destino final.

## Endereços de loopback

Os `endereços de loopback` são mais comumente identificados como apenas 127.0.0.1, esses são endereços especiais usados por um host para direcionar o tráfego para si próprio.

# NAT

A maioria das redes internas usam endereços IPv4 privados para endereçar todos os dispositivos internos. No entanto, os endereços privados **não são globalmente roteáveis**.

Quando um pacote é enviado para fora de sua rede, esse pacote tem um endereço IPv4 privado de origem e um endereço IPv4 público de destino. Antes que o ISP possa encaminhar esse pacote, ele deve traduzir o endereço IPv4 de origem, que é um endereço privado, para um endereço IPv4 público usando a Conversão de Endereços de Rede (NAT).

O `NAT` é usado para **converter entre endereços IPv4 privados e IPv4 públicos**. Isso geralmente é feito no roteador que conecta a rede interna à rede ISP.

# Segmentação de rede

Um grande domínio de broadcast é uma rede que conecta vários hosts. Um problema desse tipo de domínio é que os hosts podem gerar broadcasts em excesso e afetar a rede de forma negativa.

Em redes grandes, para evitar o **excesso de comunicações broadcasts** enviadas pelo ARP, ocorre o processo de `segmentação da rede` em sub-redes menores.

A segmentação da rede **reduz o tráfego total** da rede e **melhora seu desempenho**. Além disso, permite que o administrador **implemente políticas de segurança**. 

<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQD6kjjAR_MWUYh0icSSS1YOccuksRBxegSCKhKXhNECK7P2aNqpHeU4MJasppzr-eaBwM&usqp=CAU" width="500px" height="300px">
</p>


Os administradores de rede podem criar sub-redes usando qualquer outra divisão que faça sentido para a rede, seja por localização em um prédio, grupos, funções ou tipo de dispositivo.

Esta é a base da divisão em sub-redes: usar bits de host para criar sub-redes adicionais.

## Sub-redes IPv4

As `sub-redes IPv4` são criadas com **um ou mais bits de host** sendo usados como **bits de rede**. Isso é feito estendendo-se a máscara de sub-rede para pegar emprestado alguns dos bits da parte de host do endereço e criar bits de rede adicionais.

Quanto mais bits de host forem emprestados, **mais sub-redes poderão ser definidas**. 

Quanto mais bits forem emprestados para aumentar o número de sub-redes **reduz o número de hosts por sub-rede**.

É mais fácil dividir redes em sub-redes **nos limites dos octetos**: /8, /16 e /24.

|Prefixo|Máscara de sub-rede|Máscara de sub-rede (binário)|n° de hosts|
|:---:|:---:|:---:|:---:|
|/8|255.0.0.0|11111111.00000000.00000000.00000000|16.777.214|
|/16|255.255.0.0|11111111.11111111.00000000.00000000|65.534|
|/24|255.255.255.0|11111111.11111111.11111111.00000000|254|

Entretanto, as sub-redes podem pedir emprestado bits de **qualquer posição dos bits de host** para criar outras máscaras.

|Prefixo|Máscara de sub-rede|Máscara de sub-rede (binário)|n° de redes|n° de hosts|
|:---:|:---:|:---:|:---:|:---:|
|/25|255.255.255.128|11111111.11111111.11111111.10000000|2|126|
|/26|255.255.255.192|11111111.11111111.11111111.11000000|4|62|
|/27|255.255.255.224|11111111.11111111.11111111.11100000|8|30|
|/28|255.255.255.240|11111111.11111111.11111111.11110000|16|14|
|/29|255.255.255.248|11111111.11111111.11111111.11111000|32|6|
|/30|255.255.255.252|11111111.11111111.11111111.11111100|64|2|

> Linha /25 - O empréstimo 1 bit do quarto octeto cria 2 sub-redes que suportam 126 hosts cada
>
> Linha /26 - O empréstimo de 2 bits cria 4 sub-redes que suportam 62 hosts cada
>
> Linha /27 - O empréstimo de 3 bits cria 8 sub-redes que suportam 30 hosts cada.
>
> Linha /28 - O empréstimo de 4 bits cria 16 sub-redes que suportam 14 hosts cada.
>
> Linha /29 - O empréstimo de 5 bits cria 32 sub-redes que suportam 6 hosts cada.
>
> Linha /30 - O empréstimo de 6 bits cria 64 sub-redes que suportam 2 hosts cada.

## VLSM

É um método de dividir sub-redes mais eficiente que o tradicional, você pode alocar **somente o número de hosts necessários** da sub-rede utilizando **máscaras de tamanho variáveis**.

Usando as sub-redes VLSM, as redes LAN e entre roteadores podem ser tratadas sem desperdício desnecessário.

# Limitações

Ao longo dos anos, protocolos e processos adicionais foram desenvolvidos para enfrentar novos desafios. No entanto, mesmo com alterações, ele ainda enfrenta três grandes problemas:

|Problemas|Descrição|
|:---|:---|
|Esgotamento do endereço IPv4|O IPv4 tem um número limitado de endereços públicos exclusivos disponíveis|
|Falta de conectividade ponto a ponto|Network Address Translation (NAT) oculta o endereço IPv4 de um host de rede interna, o que pode ser problemático para tecnologias que exigem conectividade de ponta a ponta|
|Maior complexidade da rede|Embora o NAT tenha ampliado a vida útil do IPv4, ele só se destinava a ser um mecanismo de transição para o IPv6. O NAT em suas várias implementações cria complexidade adicional na rede, criando latência e dificultando a solução de problemas|























<br><br><br><br><hr>
<div align="center">
    <p><strong>Módulo Anterior:</strong> Endereçamento IPv4</p>
    <p><strong>Próximo Módulo:</strong> Endereçamento IPv6</p>
    <a href="#redes-de-computadores-i">Voltar ao topo &#8593;</a>
</div>
<hr><br><br><br><br>
















# Formato

Os endereços `IPv6` são muito maiores do que os endereços IPv4, razão pela qual é improvável que fiquemos sem eles.

Os endereços IPv6 têm **128 bits** e são escritos como uma sequência de **valores hexadecimais**. **Cada 4 bits são representados por um único dígito hexadecimal**, totalizando 32 valores hexadecimais.

Os endereços IPv6 não diferenciam maiúsculas e minúsculas e podem ser escritos tanto em minúsculas como em maiúsculas.

o formato preferencial para escrever um endereço IPv6 é x: x: x: x: x: x: x: x, com cada “x” consistindo de **quatro valores hexadecimais**.

Existem duas regras que ajudam a reduzir o número de dígitos necessários para representar um endereço IPv6.

## Omitir zeros à esquerda

A primeira regra para ajudar a reduzir a notação de endereços IPv6 é **omitir os 0s à esquerda** de qualquer seção de 16 bits ou hexteto.

- `01AB` pode ser representado como `1AB`
- `09f0` pode ser representado como `9f0`
- `0a00` pode ser representado como `a00`
- `00ab` pode ser representado como `ab`

Essa regra se aplica **somente aos 0s à esquerda**, e **NÃO aos 0s à direita**.

## Dois pontos duplos

A segunda regra para ajudar a reduzir a notação de endereços IPv6 é o **uso de dois-pontos duplo** (::) para **substituir uma única sequência** de um ou mais segmentos de 16 bits (hextetos) **composta exclusivamente por 0s**.

Aqui está um exemplo do uso incorreto de dois pontos: 2001:db8:0000:0000:0000:abcd:0000:1234.

- `2001:db8:0000:0000:0000:abcd:0000:1234` pode ser representado como `2001:db8::abcd:0000:1234`

Os dois-pontos em dobro (::) só podem ser usados **uma vez em um endereço**.

Se um endereço tiver mais de uma cadeia contígua de todos os hextets 0, a prática recomendada é usar dois pontos duplos (::) **na cadeia mais longa**.

# Comprimento do prefixo

O comprimento do prefixo pode variar de 0 a 128. O comprimento do prefixo IPv6 recomendado para LANs e a maioria dos outros tipos de redes é /64**.

<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR_cpT2kd4qUuC6fadNl-xKhPPUBN28VE9I8A&s" width="500px" height="300px">
</p>

É altamente recomendável usar um ID de interface de 64 bits para a maioria das redes. Isso ocorre porque a configuração automática de endereço sem estado, `SLAAC`, **usa 64 bits para o ID de interface**. Também facilita a criação e o gerenciamento de sub-redes.

# Tipos de endereço IPv6

Tal como acontece com o IPv4, existem diferentes tipos de endereços IPv6. Na verdade, existem três grandes categorias de endereços IPv6:

|Endereços|Descrição|
|:---:|:---|
|Unicast|Um endereço IPv6 unicast identifica exclusivamente uma interface em um dispositivo habilitado para IPv6|
|Multicast|Um endereço IPv6 multicast é usado para enviar um único pacote IPv6 para vários destinos|
|Anycast|Um endereço IPv6 anycast é qualquer endereço IPv6 unicast que possa ser atribuído a vários dispositivos. Um pacote enviado a um endereço de anycast é roteado para o dispositivo mais próximo que tenha esse endereço. Os endereços anycast estão fora do escopo deste curso|

## Unicast

Um endereço IPv6 `unicast` identifica exclusivamente uma interface em um dispositivo habilitado para IPv6.

Existem diferentes tipos de endereços unicast que um dispositivo IPv6 pode receber. Os endereços IPv6 normalmente têm **dois endereços unicast**.

### Endereço unicast global (GUA)

É **semelhante a um endereço IPv4 público**. São endereços de internet **roteáveis** e **globalmente exclusivos**. 

Ele é constituído por três partes: 

- O prefixo de roteamento global
- ID da sub-rede
- ID da interface

<p align="center">
  <img src="https://usercontent.one/wp/ipv6.diginto.se/wp-content/uploads/2023/08/pic001-ccn2-IPv6-GUA.png" width="500px" height="300px">
</p>

|Partes|Descrição|
|:---|:---|
|Prefixo de roteamento global|Parte de rede do endereço IPv6 que é atribuído pelo provedor (ISP),comumente sendo um prefixo de roteamento global /48|
|ID da sub-rede|Parte separada para identificar sub-redes localmente. Quanto maior a ID da sub-rede, mais sub-redes disponíveis|
|ID da interface|Parte de host de um endereço IPv6 que permite único host ter várias interfaces. Sub-redes /64 permitem que  dispositivos com SLAAC  criem seu próprio ID de interface de 64 bits|

No momento, somente endereços unicast globais com os primeiros três bits de **001** ou **2000::/3** estão sendo atribuídos

GUAs podem ser configurados estaticamente ou dinamicamente distribuídos.

### Endereço LLA (Link-Local Address)

Os `LLAs` são usados para se comunicar com outros dispositivos **na mesma sub-rede**. No IPv6, o termo link se refere a uma sub-rede.

Há duas maneiras pelas quais um dispositivo pode obter um LLA:

- Estaticamente - Isso significa que o dispositivo foi configurado manualmente.
- Dinamicamente - Os hosts habilitados para LLA IPv6 criarão um endereço IPv6 mesmo que não tenha sido atribuído um endereço IPv6 GUA.

O endereço link local é atribuído automaticamente utilizando o prefixo **FE80::/64**.

Os roteadores **não encaminham** pacotes com um endereço de link local origem ou destino.

Normalmente, é o LLA do roteador, e não a GUA, que é usado como o gateway padrão para outros dispositivos no link.

### Endereço ULA (Unique Local Address)

Os endereços `ULA` são utilizados para endereçamento local dentro de uma rede ou entre um conjunto de redes interconectadas.

Os endereços ULA podem ser usados para dispositivos que nunca precisarão ou terão acesso por outra rede.

Um endereço ULA **não deve** ser roteável na Internet global.

## Multicast

Um endereço `multicast` é usado para enviar um único pacote a um ou mais destinos (grupo multicast). Os endereços multicast IPv6 têm o prefixo ff00::/8.

|Grupo|Prefixo|Descrição|
|:---:|:---:|:---|
|Grupo de todos os nós|ff02::1|Este é um grupo multicast ao qual todos os dispositivos habilitados para IPv6 se juntam. Isso tem o mesmo efeito que um endereço de broadcast em IPv4|
|Grupo de todos os roteadores|ff02::2|Este é um grupo multicast ao qual todos os roteadores IPv6 ingressam. Um roteador se torna membro deste grupo quando é habilitado como roteador IPv6 com o comando de configuração global **ipv6 unicast-routing**|

# SLAAC

`SLAAC` é um método que permite que um dispositivo **crie seu próprio GUA sem os serviços do DHCPv6**. 

Com SLAAC, os dispositivos **dependem das mensagens ICMPv6 de RA** (Anúncio de Roteador) do roteador local para obter as informações necessárias.

Por padrão, a mensagem de RA sugere que o dispositivo de recebimento **use as informações dessa mensagem para criar** seu próprio endereço `IPv6 unicast global` e para todas as demais informações. Os serviços de um servidor DHCPv6 não são obrigatórios.

SLAAC é stateless, o que significa que não existe servidor central alocando endereços unicast globais e mantendo uma lista de dispositivos e seus endereços.

<p align="center">
  <img src="https://usercontent.one/wp/ipv6.diginto.se/wp-content/uploads/2023/11/ipv6-001-SLAAC.png" width="500px" height="300px">
</p>

- **Prefixo** - Isso é anunciado na mensagem RA.
- **ID da Interface** - Isso usa o processo EUI-64 ou gera um número aleatório de 64 bits, dependendo do sistema operacional do dispositivo.

# Sub-redes IPv6

o IPv6 foi projetado com a sub-rede em mente. Um campo de `ID de sub-rede` separado no GUA IPv6 é **usado para criar sub-redes**.

Com **mais de 65.536 sub-redes** para escolher, a tarefa do administrador de redes é projetar um esquema lógico de endereçamento da rede.

Para a divisão de IPv6 em sub-redes, basta **contar em ordem crescente em hexadecimal**.

<p align="center">
  <img src="https://www.dltec.com.br/blog/wp-content/uploads/2020/01/sub-rede-ipv6-exemplo-1024x471.png" width="500px" height="300px">
</p>





























<br><br><br><br><hr>
<div align="center">
    <p><strong>Módulo Anterior:</strong> Endereçamento IPv6</p>
    <p><strong>Próximo Módulo:</strong> Camada de Transporte</p>
    <a href="#redes-de-computadores-i">Voltar ao topo &#8593;</a>
</div>
<hr><br><br><br><br>





























# Propósito

A `camada de transporte` é responsável pela **comunicação lógica entre aplicativos** executados em hosts diferentes.

Isso pode incluir serviços como o estabelecimento de uma **sessão temporária** entre dois hosts e a **transmissão confiável** de informações para um aplicativo.

A camada de transporte **não tem conhecimento** do tipo de host de destino, o tipo de mídia pela qual os dados devem percorrer, o caminho percorrido pelos dados, o congestionamento em um link ou o tamanho da rede.

Para passar fluxos de dados para os aplicativos adequados, a camada de transporte identifica o aplicativo de destino usando um identificador chamado `número da porta`.

|Responsabilidades|Descrição|
|:---:|:---|
|Rastreamento de dados|É responsabilidade da camada de transporte **manter e monitorar** cada conjunto de dados que flui entre um aplicativo de origem e um aplicativo de destino|
|Segmentação/remontagem|É responsabilidade da camada de transporte **dividir os dados do aplicativo em blocos de tamanho adequado**, sejam segmentos ou datagramas|
|Adicionar cabeçalho|As  informações de cabeçalho permitem que diferentes funções sejam realizadas para o gerenciamento da comunicação de dados|

A camada de transporte inclui dois protocolos:

- Protocolo TCP (Transmission Control Protocol)
- Protocolo UDP (User Datagram Protocol)

# TCP

O `TCP` é considerado um protocolo de camada de transporte **confiável**, completo, que **garante que todos os dados cheguem ao destino**.

O TCP fornece confiabilidade e controle de fluxo usando estas operações básicas:

- Número e rastreamento de segmentos de dados
- Confirmar dados recebidos
- Retransmitir todos os dados não confirmados após um determinado período de tempo
- Dados de sequência que podem chegar em ordem errada
- Enviar dados a uma taxa eficiente que seja aceitável pelo receptor

O TCP deve primeiro **estabelecer uma conexão** entre o remetente e o receptor antes de manter o estado de uma conversa e rastrear as informações.

`FTP`, `HTTP`, `SMTP` e `SSH` são algumas das aplicações que fazem uso do protocolo TCP.

## Recursos TCP

Além de suportar as funções básicas de segmentação e remontagem de dados, o TCP também fornece os seguintes serviços:

- `Estabelece uma sessão` - O TCP é um protocolo orientado à conexão que negocia e **estabelece uma conexão permanente entre os dispositivos** de origem e de destino antes de encaminhar qualquer tráfego. Com o estabelecimento da sessão, os dispositivos **negociam o volume de tráfego** esperado que pode ser encaminhado em determinado momento e os dados de comunicação entre os dois podem ser gerenciados atentamente.
- `Garante a entrega confiável` - O TCP garante que **cada segmento enviado pela fonte chegue ao destino**.
- `Fornece entrega no mesmo pedido` - O TCP garante que os segmentos sejam remontados na ordem correta, enumerando os segmentos em sequência.
- `Suporta controle de fluxo` - O TCP **regula o volume de dados** transmitido pelo dispositivo origem. O controle de fluxo pode impedir a necessidade de retransmissão dos dados quando os recursos do host receptor estão sobrecarregados.

## Cabeçalho TCP

Um segmento TCP adiciona 20 bytes (ou seja, 160 bits) de sobrecarga ao encapsular os dados da camada de aplicativo.

<p align="center">
  <img src="https://imdtec.imd.ufrn.br/assets/imagens/redes-de-computadores-i/red_compt_a13_f04_a.jpg" width="500px" height="300px">
</p>

|Campos|Descrição|
|:---:|:---|
|Porta de origem|Um campo de 16 bits usado para identificar o aplicativo de origem por número de porta|
|Porta de destino|Um campo de 16 bits usado para identificar o aplicativo de destino por porta número|
|Número sequencial|Um campo de 32 bits usado para fins de remontagem de dados|
|Número de Confirmação|Um campo de 32 bits usado para indicar que os dados foram recebidos e o próximo byte esperado da fonte|
|Comprimento do cabeçalho|Um campo de 4 bits conhecido como 'offset de datas' que indica o comprimento do cabeçalho do segmento TCP|
|Reservado|Um campo de 6 bits que é reservado para uso futuro|
|Bits de controle|Um campo de 6 bits que inclui códigos de bits, ou sinalizadores, que indicam a finalidade e função do segmento TCP|
|Tamanho da janela|Um campo de 16 bits usado para indicar o número de bytes que podem ser aceitos de uma só vez|
|Checksum|Um campo de 16 bits usado para verificação de erros do cabeçalho e dos dados do segmento|
|Urgente|Um campo de 16 bits usado para indicar se os dados contidos são urgentes|

Os seis bits no campo Bits de Controle do cabeçalho do segmento TCP são **também conhecidos como flags**.

Uma flag é um bit que é definido como ligado (1) ou desligado (0).

Os seis bits de controle sinalizadores são os seguintes:

- SYN - Sincronizar números de sequência usados no estabelecimento de conexão.
- ACK - Indicador de confirmação usado no estabelecimento de conexão e encerramento de sessão.
- FIN - Não há mais dados do remetente e usados no encerramento da sessão.
- URG - Campo de ponteiro urgente significativo.
- PSH - Função Push.
- RST - Redefina a conexão quando ocorrer um erro ou tempo limite.

## Remontagem TCP

Para que a mensagem original seja entendida pelo destinatário, todos os dados devem ser recebidos e os dados nesses segmentos devem ser remontados na ordem original.

Através do número de sequência, isso permite que cada segmento seja identificado e confirmado de forma única. Segmentos perdidos podem então, ser identificados.

<p align="center">
  <img src="https://www.ccna.network/wp-content/uploads/2021/01/Os-segmentos-TCP-sao-reordenados-no-destino.png" width="500px" height="300px">
</p>

O número de sequência, `SEQ`, e o número de confirmação, `ACK`, são usados juntamente para confirmar o recebimento dos bytes de dados contidos nos segmentos.

Para os segmentos de dados não confirmados, é utilizado um mecanismo para restransmitir apenas os segmentos não recebidos.

<p align="center">
  <img src="https://www.ccna.network/wp-content/uploads/2021/01/Confiabilidade-TCP-perda-de-dados-e-retransmissao.png" width="500px" height="300px">
</p>

## Handshake

Nas conexões TCP, o cliente host estabelece a conexão com o servidor usando o processo de handshake de três vias.

<p align="center">
  <img src="https://i.sstatic.net/nYfsp.png" width="500px" height="300px">
</p>

|Etapas|Flags|Descrição|
|:---:|:---:|:---|
|1|SYN, SEQ = 100|O cliente iniciador requisita uma sessão de comunicação cliente-servidor com o servidor. Envia um SYN e um número de sequência inicial|
|2|SYN, SEQ = 300, ACK = 101|O servidor confirma a sessão de comunicação e requisita uma sessão de comunicação de servidor-cliente. Envia um SYN para sincronizar o número de sequência de destino e o ACK reconhece o número de sequência de origem|
|3|SEQ = 101, ACK = 301|O cliente iniciador confirma a sessão de comunicação de servidor-cliente. Envia um ACK confirmando o recebimento da mensagem de destino|

`SYN` é uma flag usada no cabeçalho TCP para iniciar uma conexão e sincronizar os números de sequência.

`ACK` é uma flag usada para confirmar o recebimento de dados ou mensagens.

### Encerramento da sessão

Para fechar uma conexão, o flag de controle Finish, `FIN`, deve ser ligado no cabeçalho do segmento. 

Para terminar cada sessão TCP de uma via, um handshake de quatro vias, consistindo de um segmento FIN e um segmento ACK é usado.

<p align="center">
  <img src="https://niktips.wordpress.com/wp-content/uploads/2012/06/tcp-fin.jpg?w=238" width="500px" height="300px">
</p>

|Etapas|Flags|Descrição|
|:---:|:---:|:---|
|1|FIN, SEQ = 1000|Quando o cliente não tem mais dados para enviar no fluxo, ele envia um segmento com um flag FIN ligado|
|2|ACK = 1001|O servidor envia ACK para confirmar o recebimento de FIN para encerrar a sessão do cliente com o servidor|
|3|FIN, ACK = 1001, SEQ = 1470|O servidor envia um FIN ao cliente para encerrar a sessão do servidor-para-cliente|
|4|ACK = 1471|O cliente responde com um ACK para reconhecer o FIN do servidor|

## Controle de fluxo

O TCP também fornece mecanismos para controle de fluxo. Controle de fluxo é a **quantidade de dados que o destino pode receber e processar** de forma confiável.

que podem ser enviados antes de esperar uma confirmação

Para definir a taxa de fluxo de dados entre a origem e o destino, o cabeçalho TCP inclui um campo de 16 bits chamado de **tamanho da janela**. O tamanho da janela determina o número de bytes que o **destino pode aceitar e processar** de uma vez, **antes de enviar uma confirmação (ACK)**.

O `MSS` faz parte do campo de opções no cabeçalho TCP que especifica a **maior quantidade de dados úteis**, payload, que um dispositivo pode receber **em um único segmento TCP**.

O número de sequência é o **número do próximo byte esperado**.

<p align="center">
  <img src="https://www.ccna.network/wp-content/uploads/2021/01/Exemplo-de-tamanho-de-janela-TCP.png" width="500px" height="300px">
</p>

Os valores do tamanho da janela e do MSS são definidos durante o handshake de três vias, onde os dispositivos informam seus valores e entram em um acordo (MSS = 1.460, JANELA = 10.000).

|Etapas|Flags|Descrição|
|:---:|:---:|:---|
|1|SEQ = 1|O dispositivo A envia o primeiro segmento de 1.460 bytes para o B com número de sequência 1|
|2|ACK = 2.921|O dispositivo B recebe os dados e responde com um ACK, indicando o próximo segmento a partir do byte 2.921|
|3|SEQ = 2.921|O dispositivo A envia mais 1.460 bytes, começando no byte 2.921|
|4|ACK = 4.381|O dispositivo B recebe os dados e responde com um ACK| 

# UDP

O `UDP` é um protocolo **sem conexão**, que **não fornece** confiabilidade ou controle de fluxo e **não requer** uma conexão estabelecida.

O UDP também é conhecido como um protocolo de entrega de melhor esforço porque **não há confirmação** de que os dados são recebidos no destino.

O UDP fornece as funções básicas para fornecer datagramas entre os aplicativos apropriados, com muito pouca sobrecarga e verificação de dados.

`DNS`, `DHCP` e **aplicativos de vídeo e multimídia ao vivo** são algumas aplicações que fazem uso do protocolo UDP.

## Recursos UDP

O UDP é um protocolo simples, normalmente descrito nos termos do que ele não faz em comparação ao TCP.

Os recursos UDP incluem o seguinte:

- Os dados são reagrupados na ordem em que são recebidos
- Quaisquer segmentos perdidos não são reenviados
- Não há estabelecimento de sessão
- O envio não é informado sobre a disponibilidade do recurso

## Cabeçalho UDP

Os blocos de comunicação no UDP são chamados de datagramas ou segmentos. Esses datagramas são enviados como o melhor esforço pelo protocolo da camada de transporte.

O cabeçalho UDP é muito mais simples do que o cabeçalho TCP porque só tem quatro campos e requer 8 bytes (ou seja, 64 bits).

<p align="center">
  <img src="https://www.bosontreinamentos.com.br/wp-content/uploads/2016/01/formato-cabe%C3%A7alho-protocolo-UDP.png" width="500px" height="300px">
</p>

|Campos|Descrição|
|:---:|:---|
|Porta de origem|Um campo de 16 bits usado para identificar o aplicativo de origem por número de porta|
|Porta de destino|Um campo de 16 bits usado para identificar o aplicativo de destino por porta número|
|Tamanho|Um campo de 16 bits que indica o comprimento do cabeçalho do datagrama UDP|
|Checksum|Um campo de 16 bits usado para verificação de erros do cabeçalho e dos dados do datagrama|

## Remontagem UDP

O UDP **não rastreia os números de sequência** da forma que o TCP faz. 

O UDP **não tem como reordernar** os datagramas na sua ordem de transmissão

<p align="center">
  <img src="https://www.ccna.network/wp-content/uploads/2021/01/UDP-Connectionless-and-Unreliable.png" width="500px" height="300px">
</p>

Os datagramas fora de ordem não são reordenados.

Os datagramas perdidos não são enviados novamente.

# Portas

Os protocolos de camada de transporte TCP e UDP usam números de porta para **gerenciar várias conversas simultâneas**.

O número da porta de origem está associado ao aplicativo de origem no host local, enquanto o número da porta de destino está associado ao tipo de serviço que está sendo solicitado.

## Socket

`Socket` é a combinação dos endereços IP e do número das portas. O socket é usado para **identificar o servidor e o serviço** que está sendo solicitado pelo cliente.

<p align="center">
  <img src="https://academiaderedes.com/wp-content/uploads/2020/12/Imagem5.png" width="500px" height="300px">
</p>

O socket em um servidor da web pode ser 192.168.1.7:80.

### Grupos de número de portas

A Internet Assigned Numbers Authority (IANA) é a organização de padrões responsável por atribuir vários padrões de endereçamento, incluindo os números de porta de 16 bits.

Os 16 bits usados para identificar os números de porta de origem e destino fornecem um intervalo de portas de **0 a 65535**.

|Grupos|Intervalo de números|Descrição|
|:---:|:---:|:---|
|Portas Comuns|0 a 1.023|Portas bem conhecidas definidas para aplicativos comuns de servidor permite para identificar facilmente o serviço associado necessário|
|Portas registradas|1.024 a 49.151|Esses números de porta são atribuídos pela IANA a uma entidade solicitante para usar com processos ou aplicativos específicos|
|Particular e/ou portas dinâmicas|49.152 a 65.535|O sistema operacional do cliente geralmente atribui números de porta dinamicamente quando uma conexão a um serviço é iniciada|
A porta dinâmica é então usada para identificar o aplicativo cliente durante a comunicação|

|Portas|Protocolos|Aplicações|
|:---:|:---:|:---:|
|20|TCP|FTP - Dados|
|21|TCP|FTP - Controle|
|22|TCP|SSH|
|23|TCP|Telnet|
|25|TCP|SMTP|
|53|UDP, TCP|DNS|
|67|UDP|DHCP|
|80|TCP|HTTP|
|443|TCP|HTTPS|

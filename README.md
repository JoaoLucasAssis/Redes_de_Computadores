# Redes de Computadores I

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
<img src="https://www.researchgate.net/publication/310193861/figure/fig1/AS:428418383781889@1479154310501/Figura-3-Modelo-OSI-e-TCP-IP.png" width="450px" height="300px">
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

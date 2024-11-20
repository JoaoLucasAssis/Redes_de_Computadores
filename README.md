# Redes de Computadores I

Este repositório foi criado para armazenar as anotações do curso Redes de Computadores I - Introduction to Networks, da plataforma NetAcad da Cisco, cursado na disciplina de Redes de Computadores I, na Universidade Vila Velha. 

Nele estão registradas as notas sobre os módulos ensinados em sala de aula, bem como sobre os módulos adicionais que, embora não abordados diretamente no semestre, foram estudados para o exame final e a obtenção do certificado de conclusão. 

As anotações incluem pontos-chave dos temas discutidos, destacando partes importantes e grifando palavras-chave essenciais para facilitar o estudo e a revisão.

# Sumário



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
    <p><strong>Módulo Anterior:</strong> Camada de enlace de dados</p>
    <p><strong>Próximo Módulo:</strong> Switching Ethernet</p>
    <a href="#redes-de-computadores-i">Voltar ao topo &#8593;</a>
</div>
<hr><br><br><br><br>































































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

































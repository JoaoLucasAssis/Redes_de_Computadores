# Endereçamento de rede

# Sumário

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

<h1 Align="center">🔗 Switching Ethernet 🌐</h1>

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































<br><br><br><br><br><br><br><br><br><br><hr>
<div align="center">
    <p><strong>Módulo Anterior:</strong> Switching Ethernet</p>
    <p><strong>Próximo Módulo:</strong> Endereçamento IPv4</p>
    <a href="#redes-de-computadores-i">Voltar ao topo &#8593;</a>
</div>
<hr><br><br><br><br><br><br><br><br><br><br>
























<h1 Align="center">🔗 Endereçamento IPv4 🌐</h1>

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























<br><br><br><br><br><br><br><br><br><br><hr>
<div align="center">
    <p><strong>Módulo Anterior:</strong> Endereçamento IPv4</p>
    <p><strong>Próximo Módulo:</strong> Endereçamento IPv6</p>
    <a href="#redes-de-computadores-i">Voltar ao topo &#8593;</a>
</div>
<hr><br><br><br><br><br><br><br><br><br><br>














<h1 Align="center">🔗 Endereçamento IPv6 🌐</h1>

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

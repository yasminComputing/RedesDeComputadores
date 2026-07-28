# Aula 01 – 28/07/2026

# O que é uma rede?

Uma rede é um conjunto de dispositivos interligados que permite a troca de dados e informações entre eles. Esses dispositivos podem ser computadores, celulares, impressoras, servidores, entre outros.

# Como os computadores conseguem se comunicar?
No início da computação, muitos fabricantes utilizavam protocolos de comunicação próprios. Como esses protocolos eram diferentes, computadores de fabricantes distintos não conseguiam se comunicar entre si.
Com o surgimento das interfaces de rede, cada dispositivo passou a possuir um endereço MAC (Media Access Control), que é um identificador único da placa de rede. Esse endereço é composto por 48 bits, representados por 6 pares de números hexadecimais, por exemplo:

> 00:1A:2B:3C:4D:5E

No Prompt de Comando (CMD) do Windows, é possível visualizar o endereço MAC utilizando o comando:

- getmac
O endereço MAC pode ser comparado ao CPF da interface de rede, pois é único para cada dispositivo. Ele permite a identificação dos equipamentos dentro de uma rede local. Entretanto, o endereço MAC não é utilizado para comunicação entre redes diferentes, como a internet. Para isso, utiliza-se o endereço IP, que identifica o dispositivo na rede e possibilita a comunicação entre computadores em diferentes locais.

# Protocolos
Um protocolo é um conjunto de regras que define como os dispositivos trocam informações em uma rede. O TCP/IP é o principal conjunto de protocolos utilizado na internet. Ele é composto por diversos protocolos, sendo os mais conhecidos:
- TCP (Transmission Control Protocol): responsável por garantir que os dados sejam entregues corretamente e na ordem certa.
- IP (Internet Protocol): responsável pelo endereçamento e pelo encaminhamento dos pacotes de dados entre as redes.
Além do modelo TCP/IP, existe o Modelo OSI, criado para padronizar a comunicação entre sistemas. Ele divide a comunicação em sete camadas, facilitando o entendimento, o desenvolvimento e a identificação de problemas em uma rede. Embora o modelo OSI seja amplamente utilizado para fins de estudo e referência, na prática o modelo TCP/IP é o mais utilizado.

# Modelo TCP/IP
O modelo TCP/IP é dividido em quatro camadas:

- Aplicação
- Transporte
- Internet
- Acesso à Rede
  
Esse modelo é mais simples e flexível do que o modelo OSI, pois reúne algumas funções em menos camadas. Cada camada possui uma responsabilidade específica, trabalhando em conjunto para que a comunicação entre os dispositivos aconteça de forma eficiente. Essa divisão facilita o envio e o recebimento de dados, permitindo que diferentes equipamentos "falem a mesma linguagem" por meio de protocolos padronizados.

# Como numa rede LAN sabe que o computador está ligado?
Quando ligado o computador, ele "dá um grito" onde sinaliza que ele está ligado, assim na rede ele vai receber seu protocolo IP. 

Observação: 
> Uma rede em séria é quando não tem redundância.

# HUB X Switch X Roteador
O Hub quando recebe um pacote para chegar no destinatário vai passar por todos os computadores na rede, o que pode ocasionar vulnerabilidade, já o Switch envia somente o pacote para o destinatário. O roteador tem como papel saber em quem é quem e interligar todo mundo.




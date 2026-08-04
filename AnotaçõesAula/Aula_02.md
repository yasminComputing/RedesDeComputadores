# Aula 02 - Dia 04/08/2026
As redes de computadores devem conter, no mínimo, **dois computadores** interligados. Não há um limite máximo para a quantidade de computadores que podem fazer parte de uma mesma rede.

## Usos das redes de computadores
- **Acesso à informação:**
  - Veículos de notícias;
  - Bibliotecas virtuais;
  - Internet (navegação na Web);
  - Aplicações Web (modelo cliente-servidor).

<img width="256" height="192" alt="redirecionador-l" src="https://github.com/user-attachments/assets/17afc5b1-4637-4e5d-9478-fc10f43eeca5"/>

---

## Modelo Peer-to-Peer (P2P)
O modelo **Peer-to-Peer (P2P)** não é hierárquico. Nesse tipo de rede, todos os computadores podem atuar como cliente e servidor ao mesmo tempo.

**Exemplo:** BitTorrent

- Ao utilizar o BitTorrent, outras pessoas podem usar sua conexão para baixar arquivos que você está compartilhando. Esse processo é conhecido como **semeadura (seeding)**.

<img width="572" height="400" alt="overview" src="https://github.com/user-attachments/assets/0729bf35-096e-4770-b5ba-a0364caf59ed"/>

---

## Comércio Eletrônico
Os principais modelos de comércio eletrônico são:

- **Business-to-Consumer (B2C):** empresas vendem diretamente para consumidores. Exemplo: pedidos de livros on-line.
- **Business-to-Business (B2B):** empresas realizam transações entre si. Exemplo: fabricantes de automóveis comprando pneus de fornecedores.
- **Government-to-Consumer (G2C):** serviços prestados pelo governo aos cidadãos.
- **Consumer-to-Consumer (C2C):** negociações entre consumidores.
- **Peer-to-Peer (P2P):** compartilhamento direto de recursos entre usuários, sem um servidor central.
---

## Tipos de Redes
- **Redes de banda larga**: fibra ótica 
- **Redes Móveis e sem fio**: telefones, notebook e Wifi
- **Redes de Provedores de Conteúdo**: Data Centers, Computação em Nuvem, CDN (content delivery network)
- **Redes de Trânsito**: Ligam ISP (Internet Service Provider) ao provedor de conteúdo, redes de Backbone
- **Redes Comerciais**: permitem o compartilhamento de recursos empresariais, a comunicação por **Voice over IP (VoIP)** e o uso de **Redes Privadas Virtuais (VPNs)**. Essas tecnologias possibilitam que diferentes unidades ou filiais de uma empresa, mesmo estando em locais geográficos distintos, compartilhem informações, recursos e se comuniquem de forma segura e eficiente.

---

> `IEEE (Institute of Electrical and Electronics Engineer) que tem como objetivo padronizar tecnologias, publicar pesquisas científicas e conectar profissionais da área tecnológica globalmente.`

---

## Frequência do Wi-Fi
Quando uma frequência é um pouco menor, ela consegue transportar mais energia e mais dados. Por isso, a frequência de 5,825 GHz oferece maior capacidade de transmissão de dados.


## Problemas do Wi-Fi
* Colisão de dados
  
  * Acesso múltiplo com detecção de portadora (CSMA).
  
  * Baseado no protocolo ALOHA.
    
* Segurança
    * Wired Equivalent Privacy (WEP)
      
    * Wi-Fi Protected Access (WPA)
      
    * WPA2

**Observação:**
> Não é recomendado utilizar redes Wi-Fi públicas para acessar serviços que exigem login ou senha. Em redes inseguras ou mal configuradas, um invasor pode interceptar a comunicação ou tentar capturar credenciais utilizando diferentes técnicas de ataque.

---

## Protocolos de Rede
É um acordo entre duas partes, é a forma como se comunica. Cada rede que pode ser montada pode ser escolhido o protocolo. Como escolher um protocolo: 

* **Objetivo de Projeto**

    * **Confiabilidade**
      * Detecção de erros
      * Correção de erros
      * Roteamento automático

    * **Alocação de Recursos**
      * Escalabilidade
      * Multiplexação Estatística: alocar recursos conforme demanda
      * Controle de fluxo: evitar congestionamento
      * Qualidade de serviço

    * **Segurança**
      * Confidencialidade
      * Autenticação: SCL
      * Integridade

    * **Capacidade de Evolução**
      * Endereçamento / nomeação
      * Interligação de redes
      * Camadas de protocolos: modelo OSI

---
## Virtual ou virtualmente
Algo acontece virtualmente quando ocorre de forma indireta, por meio de uma camada intermediária. Um exemplo é quando duas pessoas desejam se comunicar por cartas, mas existe um sistema de tradução entre elas. Assim, cada pessoa escreve em seu próprio idioma, e a tradução permite que ambas conversem indiretamente, sem precisar conhecer a língua da outra.

---

##  Camadas de Protocolos
Uma camada de protocolo abstrai os detalhes de implementação, permitindo que cada parte do sistema se preocupe apenas com sua própria função. Dessa forma, ao desenvolver um sistema, é possível definir quantas camadas serão utilizadas. Esse conjunto de camadas é chamado de **Arquitetura de Rede**.

* Reduzir complexidade
* Pilha de camadas / níveis de protocolos
* Isolamento / abstração da implementação


## Serviço X Protocolos

O serviço somente é o conjunto primitivos (operações),não informa como as operações são implementadas.Protocolo é conjunto de regras, controla formato e significado de mensagens. 



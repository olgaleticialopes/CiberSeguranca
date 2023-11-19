## 📓 Fundamento de redes de computadores

### 📌 Conceito de redes de computadores

- O que é uma rede de computadores?

    - Uma rede de computadores é um conjunto de computadores interligados entre si, de modo que possam trocar informações e compartilhar recursos.

* *Nós* :são os computadores que fazem parte da rede.
* *Links* :são os meios de comunicação que interligam os nós.
* *Arquiterura* :é a forma como os nós e os links estão organizados.
* *Endereço IP* :é o endereço lógico de um nó na rede.
* *Portas* : identifica uma conexão especidia entre dois nós(protocolo TCP).<br>
Como por exemplo 192.168.10.15:8080
192.168.10.15 = IP address,
80: port number
* *Protocolo* :é um conjunto de regras que define como os nós devem se comunicar.

### 📌 Topologias de redes de computadores

 Topologia de rede é a forma como os nós e os links estão organizados.

* *Topologia em barramento* :todos os nós estão conectados a um único link.
* *Topologia em anel* :todos os nós estão conectados a um único link, formando um anel.
* *Topologia em estrela* :todos os nós estão conectados a um único nó central.
* *Topologia em malha* :todos os nós estão conectados a todos os nós.

<div align=center >
<img src="https://anlix.io/wp-content/uploads/2022/02/topologia-exempllo-1024x685.png">
</div>

#### 📍 Tipos de redes: 

* LAN(local area network): Conecta dispositivos proximos, em um mesmo ambiente.
* MAN(metropolitan area network): Conecta dispositivos em uma mesma cidade.
* WAN(wide area network): Conecta dispositivos em uma mesma região geográfica.
* SAN(storage area network): Conecta dispositivos de armazenamento de dados.
* PAN(personal area network): Conecta dispositivos de uma pessoa.
* VLAN(virtual local area network): Conecta dispositivos de uma mesma rede local, mesmo que estejam em locais diferentes.

###  📌  Protocolos de redes de computadores

Protocolo é um conjunto de regras que define como os nós devem se comunicar, como um idioma, não importanto o dispositivo ou sistema operacional.

#### 📍Modelos de camadas

O agrupamento em camadas faciltia o desenvolvimento de protocolos, pois cada camada é responsável por uma parte da comunicação, como: 
* Delimitar as funções de cada camada.
* Facilitar o desenvolvimento de protocolos.
* Servir como referência para o desenvolvimento de novos protocolos.

#### 📍 Modelo OSI

O modelo OSI é um modelo teórico, que define 7 camadas, cada uma com suas funções.


* Aplicação: é a camada mais próxima do usuário, é onde estão os protocolos que definem como os programas devem se comunicar.
* Apresentação: é a camada responsável por definir como os dados devem ser apresentados, como por exemplo, a criptografia.
* Sessão: é a camada responsável por definir como os dados devem ser organizados, como por exemplo, a sessão de um usuário.
* Transporte: é a camada responsável por definir como os dados devem ser transportados, como por exemplo, o protocolo TCP.
* Rede: é a camada responsável por definir como os dados devem ser roteados, como por exemplo, o protocolo IP.
* Enlace: é a camada responsável por definir como os dados devem ser transmitidos, como por exemplo, o protocolo Ethernet.
* Física: é a camada responsável por definir como os dados devem ser transmitidos fisicamente, como por exemplo, o cabo de rede.

<div align=center >
<img src="https://cf-assets.www.cloudflare.com/slt3lc6tev37/6ZH2Etm3LlFHTgmkjLmkxp/59ff240fb3ebdc7794ffaa6e1d69b7c2/osi_model_7_layers.png">
</div>

#### 📍 Protocolo TCP/IP

O modelo TCP/IP é um modelo prático, que define 4 camadas, cada uma com suas funções.

* Aplicação: é a camada mais próxima do usuário, é onde estão os protocolos que definem como os programas devem se comunicar.
* Transporte: é a camada responsável por definir como os dados devem ser transportados, como por exemplo, o protocolo TCP.
* Internet: é a camada responsável por definir como os dados devem ser roteados, como por exemplo, o protocolo IP.
* Acesso à rede: é a camada responsável por definir como os dados devem ser transmitidos, como por exemplo, o protocolo Ethernet.

<div align=center >
<img src="https://www.dltec.com.br/blog/wp-content/uploads/2019/02/osi-tcp-ip.png">
</div>


### 📌 Principais protocolos de redes de computadores

#### 📍 Camada de aplicação

* HTTP: é o protocolo utilizado para acessar páginas web.
* HTTPS: é o protocolo utilizado para acessar páginas web de forma segura.
* FTP: é o protocolo utilizado para transferir arquivos.
* SMTP: é o protocolo utilizado para enviar e-mails.
* POP3: é o protocolo utilizado para receber e-mails.
* IMAP: é o protocolo utilizado para receber e-mails.
* DNS: é o protocolo utilizado para resolver nomes de domínio.
* WWW: é o protocolo utilizado para acessar páginas web.

#### 📍 Camada de transporte

* TCP: é o protocolo utilizado para transportar dados de forma confiável.
* UDP: é o protocolo utilizado para transportar dados de forma rápida.
* RTP: é o protocolo utilizado para transportar dados de áudio e vídeo.
* SCTP: é o protocolo utilizado para transportar dados de forma confiável.
* DCCP: é o protocolo utilizado para transportar dados de forma rápida.

#### 📍 Camada de internet

* IP: é o protocolo utilizado para rotear dados.
* IPV4: é a versão 4 do protocolo IP.
* IPV6: é a versão 6 do protocolo IP.
* ICMP: é o protocolo utilizado para enviar mensagens de controle.
* IPsec: é o protocolo utilizado para criptografar dados.

#### 📍 Camada de acesso à rede

* Ethernet: é o protocolo utilizado para transmitir dados.
* Wi-Fi: é o protocolo utilizado para transmitir dados sem fio.
* Modem: é o protocolo utilizado para transmitir dados por linha telefônica.
* PPP: é o protocolo utilizado para transmitir dados por linha telefônica.

#### 📍 Portas e protocolos

<div align=center>
<img src="https://cdn.discordapp.com/attachments/1020872567738863716/1175786357361213550/image.png?ex=656c7f60&is=655a0a60&hm=55aafb980fcfeac43e6c044c52c30927cd591f178a3b865d3807124bfe5cb701&">
</div>


### 📌 Endereçamento IP

#### O que é um endereço IP?

* Um endereço IP é uma sequencia de numeros separados por pontos, representado por um conjunto de quatro numeros conhecidos como octetos, Como por exemplo: 192.158.1.38. Cada octeto pode representar um numero de 0 a 255.

<div align=center>
<img src="https://www.dltec.com.br/blog/wp-content/uploads/2015/11/endereco-ip.jpg">
</div>

#### 📍 Mascara de IP

* A mascara de IP é uma sequencia de numeros separados por pontos, representado por um conjunto de quatro numeros conhecidos como octetos, Como por exemplo:

<div align=center>
<img src="data:image/png;base64,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">
</div>

#### 📍 Classes de IP 

Pincipais classes: 

- A: 255.0.0.0
- B: 255.255.0.0
- C: 255.255.255.0

<div alin=center>
<img src="https://cdn.discordapp.com/attachments/1020872567738863716/1175787862021648464/image.png?ex=656c80c7&is=655a0bc7&hm=1dfcd4e44df850612cde36bae9c9263463a90153d846bac280718b575d9e9092&">
</div>

#### 📍 Ataques conta IPs

* Engenharia social: é uma forma de ataque que consiste em manipular o usuário para que ele forneça informações confidenciais.
* Ciberstalking: é uma forma de ataque que consiste em perseguir uma pessoa na internet, enviando mensagens ameaçadoras e/ou ofensivas.
* Dowload de conteúdo ilegal: é uma forma de ataque que consiste em baixar conteúdo ilegal, como filmes, músicas, jogos, etc.
* Rastrear sua localização: é uma forma de ataque que consiste em rastrear sua localização através do seu IP.
* Ataques DDoS: é uma forma de ataque que consiste em sobrecarregar um servidor com requisições, fazendo com que ele fique indisponível.
* Ataque direto: é uma forma de ataque que consiste em atacar diretamente o seu computador, através de uma vulnerabilidade.
* Ataque em seu dispositivo: é uma forma de ataque que consiste em atacar diretamente o seu dispositivo, através de uma vulnerabilidade.


### 📌 Privacidade com Proxy e VPN

#### 🔗 Proxy

##### 📍 O que é um proxy? 
* Um proxy é um servidor que atua como um intermediário entre o seu computador e a internet. 
* Quando você acessa um site através de um proxy, o proxy envia uma requisição para o site e, em seguida, envia a resposta para você. 
* O proxy pode ser usado para ocultar o seu IP, para acessar sites bloqueados, para acessar sites de forma anônima, etc.

##### 📍Como funciona um proxy?

 * Quando você acessa um site através de um proxy, o proxy envia uma requisição para o site e, em seguida, envia a resposta para você. 
* O proxy pode ser usado para ocultar o seu IP, para acessar sites bloqueados, para acessar sites de forma anônima, etc.

##### 📍 Tipos de proxy

* Proxy HTTP: é um proxy que funciona com o protocolo HTTP.
* Proxy HTTPS: é um proxy que funciona com o protocolo HTTPS.
* Proxy SOCKS: é um proxy que funciona com o protocolo SOCKS.
* Proxy SOCKS5: é um proxy que funciona com o protocolo SOCKS5.

#### 🔗 VPN

##### 📍 O que é uma VPN?

* Uma VPN é uma rede privada virtual que permite que você crie uma conexão segura com outra rede através da internet.
* Uma VPN pode ser usada para ocultar o seu IP, para acessar sites bloqueados, para acessar sites de forma anônima, etc.


##### 📍 Como funciona uma VPN?

* Quando você acessa um site através de uma VPN, a VPN envia uma requisição para o site e, em seguida, envia a resposta para você.

<div align=center>
<img src="https://www.hostinger.com/tutorials/wp-content/uploads/sites/2/2022/05/what-is-a-vpn-01.webp">
</div>


##### 📍 Tipos de VPN

* VPN PPTP: é uma VPN que funciona com o protocolo PPTP.
* VPN L2TP: é uma VPN que funciona com o protocolo L2TP.
* VPN OpenVPN: é uma VPN que funciona com o protocolo OpenVPN.
* VPN IKEv2: é uma VPN que funciona com o protocolo IKEv2.

##### 📍 Vantagens da VPN

A principal vantagem da VPN é a segurança, como ela criptograca a sua conxão, os potenciais hackers não podem "escutar" sua transmissão para roubar seus dados. Alem de outras vantagens como:

* Acesso a sites bloqueados: você pode acessar sites bloqueados em seu país.
* Acesso a sites de forma anônima: você pode acessar sites de forma anônima.
* Acesso a sites de forma segura: você pode acessar sites de forma segura.
* Acesso a sites de forma privada: você pode acessar sites de forma privada.
* Acesso a sites de forma rápida: você pode acessar sites de forma rápida.
* Acesso a sites de forma ilimitada: você pode acessar sites de forma ilimitada.


#### 🔗 Diferença entre Proxy e VPN

* Proxy: é um servidor que atua como um intermediário entre o seu computador e a internet.
* VPN: é uma rede privada virtual que permite que você crie uma conexão segura com outra rede através da internet.

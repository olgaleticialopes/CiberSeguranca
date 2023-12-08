# 📓 Tencicas de exploração de Vulnerabilidades

## 📌 O que é exploração de vulnerabilidades?

A exploração de vulnerabilidades é uma técnica de segurança que consiste em explorar uma vulnerabilidade de um sistema, como por exemplo, uma vulnerabilidade do sistema operacional, uma vulnerabilidade do servidor web, uma vulnerabilidade do banco de dados, etc.

## 📌 Explorando falhas no FTP

O FTP é um dos metodos de compartilhamento de dados mais antigos e ainda usados atualmente. Embora as equipes de TI e os usuarios de negocios estejam familiarizados com isso, o FTP é um protocolo inseguro que deve ser evitado sempre que possivel.

#### 📍 Vulnerabilidades do FTP 

- **Anonymous authentication** - O FTP permite que os usuarios se conectem anonimamente, sem a necessidade de uma senha. Isso pode ser explorado por um atacante para obter acesso não autorizado a um servidor FTP.

- **Directory traversal** - O FTP permite que os usuarios acessem arquivos e pastas em um servidor FTP. Isso pode ser explorado por um atacante para acessar arquivos e pastas que não deveriam ser acessados.

- **Cross-site scripting** - O FTP permite que os usuarios enviem comandos para um servidor FTP. Isso pode ser explorado por um atacante para executar scripts maliciosos em um servidor FTP.

= **Dridex** - O Dridex é um malware que pode ser usado para roubar credenciais de login. Isso pode ser explorado por um atacante para roubar credenciais de login de um servidor FTP.

#### 📍 Metasploit

O Metasploit é um framework de teste de penetração que pode ser usado para explorar vulnerabilidades. Ele pode ser usado para explorar vulnerabilidades do FTP.

<div align=center>
<img src="https://media.discordapp.net/attachments/1020872567738863716/1182694204061782036/image.png?ex=6585a0cf&is=65732bcf&hm=6bfc5b9a2ade387484d1d2769e6ee626af00974baf69a741dee870f83d60ea8d&=&format=webp&quality=lossless">
</div>

Quais são as ferramentas do MetaSploit?

- **msfconsole** - O msfconsole é uma interface de linha de comando para o Metasploit. Ele pode ser usado para executar comandos do Metasploit.

- **msfweb** - O msfweb é uma interface da web para o Metasploit. Ele pode ser usado para executar comandos do Metasploit.

- **msfplayload** - O msfplayload é um gerador de carga util para o Metasploit. Ele pode ser usado para gerar cargas uteis para o Metasploit.

- **msfcli** - O msfcli é uma interface de linha de comando para o Metasploit. Ele pode ser usado para executar comandos do Metasploit.

- **msflogdump** - O msflogdump é um analisador de log para o Metasploit. Ele pode ser usado para analisar logs do Metasploit.

Os modulos para exploit, sendo de tres tipos:

- **Single** - O modulo single é um modulo de exploração que pode ser usado para explorar uma vulnerabilidade.

- **Stagers** - O modulo stagers é um modulo de exploração que pode ser usado para explorar uma vulnerabilidade.

- **Stages** - O modulo stages é um modulo de exploração que pode ser usado para explorar uma vulnerabilidade.

## 📌 Ataques DoS no Windows RDP

RDP é uma apreviação de Remote Desktop Protocol, sendo uma opção para cntrolar um sistema de um computador remotamente. O serviço RDP é executado na porta 3389. Os ataques RPD são tentativas de agentes de ameaças de acessar um host de desktop remoto ou privilegios administrativos do cliente para reconhecimento, comando e controle e movimentação lateral.

<div alig=center>
<img src="https://cdn.discordapp.com/attachments/1020872567738863716/1182695330089803827/image.png?ex=6585a1dc&is=65732cdc&hm=7a8cfe28d1d827e1b39c750b5534e3b41ab339c256eaf085d6c21ebe6e192158&">
</div>

Outros tipos de ataques comuns: 

- **Calling into Robinhood** - O ataque de chamada em Robinhood é um ataque de negação de serviço que pode ser usado para negar o acesso a um host de desktop remoto.

- **SamSam ransomware** - O SamSam ransomware é um ataque de negação de serviço que pode ser usado para negar o acesso a um host de desktop remoto.


### 📍 Prevenção 

- Autenticação multifator e requisitos complexos de credenciais de acesso
- Estabelceler politicas de bloqueiro de conta para tentativas de força bruta
- Controle de acesso abaseado em função (RBAC) para consoles RDP   
- Restrições de acesso RDP baseadas em firewall

## 📌 Explorando falhas no SSH

O protocolo SSH é utilizado para comunicação remota entre dispositivos, sendo executado na porta 22.

## 📌 Adicionando um backdoor em um executavel

Backdoor é um tipo de malware que permite que um atacante acesse um sistema sem a necessidade de uma senha. Isso pode ser usado para obter acesso não autorizado a um sistema.

<div aling=center>
<img src="https://cdn.discordapp.com/attachments/1020872567738863716/1182696300257476618/image.png?ex=6585a2c3&is=65732dc3&hm=3545cefe9686c0c79e3dc468c529f2050ae9d0cdfdf45160f689aa7a0ab74342&">
</div>

### 📍 Tipos de ataques Backdoor

- **Spyware** - O spyware é um tipo de malware que pode ser usado para espionar um sistema.

- **Keylogger** - O keylogger é um tipo de malware que pode ser usado para espionar um sistema.

- **Ransomware** - O ransomware é um tipo de malware que pode ser usado para espionar um sistema.

- **DDos** - O DDos é um tipo de malware que pode ser usado para espionar um sistema.

- **Cryptojacking** - O cryptojacking é um tipo de malware que pode ser usado para espionar um sistema.

### 📍 Proteção contra backdoors

- **Roatividade de senhas** - A roatividade de senhas é uma técnica de segurança que consiste em alterar as senhas de uma conta em intervalos regulares. Isso pode ser usado para evitar que um atacante acesse uma conta.

- **Monitoramento de atividades da rede** - O monitoramento de atividades da rede é uma técnica de segurança que consiste em monitorar as atividades da rede. Isso pode ser usado para detectar atividades maliciosas.

- **Cautela ao instalar programas** - A cautela ao instalar programas é uma técnica de segurança que consiste em instalar programas apenas de fontes confiáveis. Isso pode ser usado para evitar que um atacante instale programas maliciosos.

- **Atualização do antivirus** - A atualização do antivirus é uma técnica de segurança que consiste em atualizar o antivirus regularmente. Isso pode ser usado para evitar que um atacante instale programas maliciosos.

### 📍 Meterpreter

O meterpreter ou Meta-Interpreter é um payload que funciona por *injeçção dll*. Ele reside inteiramente na memoria do anfitrião e nao deixa vestigios no disco rigido (o que a torna de dificil detecção nas tecnicas forenses). O meterpreter é um payload que pode ser usado para executar comandos em um sistema.
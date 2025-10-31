
## Camada 1 - Física
- Responsável pela transmissão física de bits (sinais elétricos, ópticos ou de rádio).
- Principais protocolos e padrões:
	- Ethernet (IEEE 802.3) - Comunicação via cabos (rede cabeada);
	- Wi-Fi (IEEE 802.11) - Comunicação sem fio (ondas de rádio).
	- Bluetooth - Conexões de curta distância (ondas de rádio).
	- DSL (Sinal elétrico) / Fibra (Sinal de luz) / 4G -5G (ondas de rádio) - Tecnologias de acesso à internet. 

## Camada 2 - Enlace de Dados
- Contra o acesso ao meio físico e detecta erros de transmissão.
- Principais protocolos:
	- Ethernet (MAC / CSMA-CD)
	- PPP (Point-to-Point Protocol)
	- HDLC (High-Level Data Link Control)
	- Frame Relay
	- ATM (Asynchronous Transfer Mode)
	- ARP (Address Resolution Protocol) - Converte IP em endereços MAC.
	- VLAN (IEEE  802.1Q) - Segmentação de redes locais.

## Camada 3 - Rede 
- Responsável pelo endereçamento e roteamento dos pacotes.
- Principais protocolos:
	- IP (Internet Protocol) - IPv4 e IPv6
	- ICMP (Internet Control Message Protocol) - Mensagens de controle (ex: Ping)
	- IGMP (Internet group Management Protocol) - Gerencia grupos multicast.
	- OSPF (Open Shortest Path First) - Roteamento dinâmico.
	- BGP (Border Gateway Protocol) - Roteamento entre redes (na internet).
	- NAT (Network Address Translation) - Tradução de endereços privados / públicos.

## Camada 4 - Transporte
- Garante a entrega confiável e o controle de fluxo de dos dados.
- Principais protocolos:
	- TCP (Transmission Control Protocol) - Confiável, orientado à conexão.
	- UDP (User Datagram Protocol) - Mais rápido, sem verificação de entrega.
	- SCTP (Stream control Transmission Protocol) - Usado em telefonia e streaming.

## Camada 5 - Sessão
- Gerencia sessões de comunicação entre sistemas (ínicio, manutenção e fim).
- Principais protocolos:
	- NetBios - Comunicação entre aplicações em redes Windows.
	- PPTP (Point-to-Point Tunneling Protocol) - Usado em VPNs mais antigas.
	- RPC (Remote Procedure Call) - Chamada de funções remotas.

## Camada 6 - Apresentação
- Cuida da formatação e criptografia dos dados.
- Principais protocolos e padrões.
	- SSL / TSL - Criptografia para HTTPS e outros serviços seguros.
	- JPEG / MPEG / GIF / PNG - Formatos de codificação de dados.
	- ASCII / EBCDIC / Unicode - Codificação de texto.

## Camada 7 - Aplicação
- Camada mais próxima do usuário, responsável pelos serviços de rede.
- Principais protocolos:
	- HTTP / HTTPS - Web
	- FTP / SFTP / TFTP - Transferência de arquivos.
	- SMTP / POP3 / IMAP - E-mails.
	- DNS (Domain Name System) - Conversão de nomes em IPs
	- DHCP (Dynamic Host Configuration Protocol) - Atribuição automática de IP.
	- SNMP (Simple Network Management Protocol) - Gerenciamento de dispositivos
	- SSH / Telnet - Acesso remoto.
	- NTP (Network Time Protocol) - Sincronização de tempo.


## O modelo IoT pode ser um pouco diferente
![[Pasted image 20251031111910.png]]
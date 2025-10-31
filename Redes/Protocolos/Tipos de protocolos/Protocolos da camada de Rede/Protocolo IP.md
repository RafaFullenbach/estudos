
- O Protocolo IP (Internet Protocol), popularmente chamado de endereço IP, é um protocolo de comunicação de rede e na internet (modelo TCP/IP e modelo OSI), é usado para identificar cada equipamento computacional (host) conectado garantindo assim que as informações cheguem no destino (roteamento de dados). Tecnicamente são regras de endereçamento / roteamento dos pacotes de dados. O importante protocolo IP está na camada intitulada de rede.

- Quando você envia um ficheiro (arquivos), eles são enviados via IP, seja um vídeo uma foto ou um documento, ele não é enviado de uma vez. Em vez disso o arquivo é dividido em pequenas partes chamadas pacotes de dados, e esses pacotes são transportados pelo protocolo IP.

- O IP envia os ficheiros divido os arquivos dessa forma:
	- Divisão do arquivo:
		- O sistema pega o arquivo e o divide em blocos menores.
		- Exemplo: Um arquivo de 1MB pode ser dividido em centenas de pacotes de 1.000bytes cada.
		
	- Encapsulamento:
		- Cada pacote recebe um cabeçalho IP, que contém:
			- O endereço IP de origem (quem envia);
			- O endereço IP de destino (quem recebe);
			- Informações de controle (como ordem dos pacotes);
		
	- Transporte:
		- Os pacotes são enviados através da rede eles podem até seguir caminhos diferentes até chegar ao destino (roteamento dinâmico).
		
	- Recepção e remontagem:
		- No destino, o protocolo TCP (ou UDP) reorganiza os pacotes na ordem correta e reconstrói o ficheiro original.

- Roteadores são usados para reencaminhar datagramas IP através de rede interconectadas, usados por provedores de internet, grandes empresas e centro de dados.

## Formato do cabeçalho IPV4

![[Pasted image 20251031141444.png]]

![[Pasted image 20251031141455.png]]

![[Pasted image 20251031141613.png]]
![[Pasted image 20251031141632.png]]![[Pasted image 20251031141644.png]]

![[Pasted image 20251031141657.png]]
![[Pasted image 20251031141712.png]]![[Pasted image 20251031141722.png]]
![[Pasted image 20251031141731.png]]![[Pasted image 20251031141740.png]]

- O Ipv4 a primeira versão tem uma extensão de 32 bits, em teoria com 4 billhões de Ip's disponíveis, para serem usados, porém o Ipv4 foi esgotado em 2014, e desde 1998 foi criado o Ipv6 com 128 bits, que seria 10^38  de combinações possíveis garantindo Ip's por milênios, essa implementação vem sendo feita gradativamente com cautela, porém as duas tecnologias pode coexistir. 
- O protocolo DNS (Domain Name System), é um sistema que associa nomes de domínios mais facilmente memorizáveis a endereços de IP numéricos, esse processo é denominado resolução de nome.

- Existe uma hierarquia em servidores DNS, numa escala de 3 categorias:
	- Servidores-raiz;
	- Servidores de domínio de topo;
	- Servidores com autoridade;

## Servidores Raiz
- No topo da hierarquia estão os 13 servidores raiz. Um servidor-raiz é um servidor de nome para a zona raiz do DNS. A sua função é responder diretamente às requisições de registros da zona raiz e responder outras requisições retornando uma lista dos servidores de nome designados para o domínio de topo apropriado. Os servidores raiz são parte crucial da Internet porque são o primeiro passo em resolver nomes para endereços IP,  esses últimos usados para comunicação entre hosts.

## Servidores de domínio de topo
- Cada domínio é formado por nomes separados por pontos. O nome mais a direita é chamado de domínio de topo. Exemplos de domínios são :
	- .com, .org, .net, .edu, .inf, .gov
	
- Cada servidor de domínio de topo conhece os endereços dos servidores autoritativos que pertencem àquele domínio de topo, ou o endereço de algum servidor DNS intermediário, que conhece um servidor autoritativo.

## Servidores com autoridade
- Cada domínio tem um ou mais servidores DNS autoritativos.
- Esses servidores são os responsáveis por responder oficialmente às perguntas sobre esse domínio.
- Exemplo:
  ![[Pasted image 20251031170117.png]]

## Fluxo de navegação
- Quando você digita https://www.google.com ele ainda não sabe o IP do servidor do Google, oque ele tem é apenas **um nome de domínio**, que é algo legível para humanos.

- Então o computador precisa **descobrir o IP numérico** (ex: `142.250.72.196`) para conseguir se conectar. E é aí que entra o DNS (Domain Name System).

- O computador primeiro **verifica se já sabe o IP** de `google.com`:
	- Se ele tiver salvo (em **cache**), ele usa direto.
    - Se não tiver, ele precisa **perguntar** a alguém.

- Seu roteador ou provedor de Internet (ISP) tem um **servidor DNS recursivo**.  
  É ele que faz o “trabalho sujo” de **descobrir o IP** perguntando aos outros servidores DNS da Internet. Se o servidor recursivo também **não souber**, ele começa a subir a hierarquia:


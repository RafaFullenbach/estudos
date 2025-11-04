- HTTP (Hyper Transfer Protocolo, em português Protocolo de Transferência de Hipertexto), utilizado para sistemas de informação de hipermídia. Ele é a base para comunicação de dados da World Wide Web.

- Hipertexto é o texto estruturado que utiliza ligações lógicas (hiperlinks) entre nós contendo texto. O Http é o protocolo para a troca ou transferência de hipertexto.

- O Htpp funciona como um protocolo de requisição-resposta no modelo computacional cliente-servidor. Um navegador web, por exemplo, pode ser o cliente e uma aplicação em um computador que hospeda um sítio da web pode ser o servidor.

- O cliente submete uma mensagem de requisição Htpp para o servidor. O servidor, que fornece os recursos, como arquivos Html e outros conteúdos, ou realiza outras funções de interesse do cliente, retorna uma mensagem resposta para o cliente. A resposta contém informações de estado completas sobre a requisição e pode também conter o conteúdo solicitado no corpo de sua mensagem.

## Funcionamento

- Um sistema de comunicação de em rede possui diversos protocolos que trabalham em conjunto para fornecimento de serviços. Para que o protocolo Htpp consiga transferir seus dados pela Web, é necessário que os protocolos TCP e IP tornem possível a conexão entre clientes e servidores através de sockets TCP/IP.

## Cookies

- O cookie é usado para identificar um usuário que configurou uma página web, para que na próxima vez que ele entrar ela esteja configurada do modo em que ele deixou. Pode ser usado também quando se faz a solicitação de armazenamento de senha, na vez posterior em que entrar no site, a sua senha será lembrada. É usado também em sites de compra, como e-commerce, armazenando os produtos que o cliente colocou no carrinho para que no final da compra não necessite fazer todo o processo novamente.

- Cada domínio pode armazenar até 20 cookies.

## Sessão HTTP

- Uma sessão HTTP é uma sequência de transações de rede de requisição-resposta. Um cliente HTTP inicia uma requisição estabelecendo uma conexão [Transmission Control Protocol](https://pt.wikipedia.org/wiki/Transmission_Control_Protocol "Transmission Control Protocol") (TCP) para uma [porta](https://pt.wikipedia.org/wiki/Porta "Porta") particular de um servidor (normalmente a porta 80). Um servidor HTTP ouvindo naquela porta espera por uma mensagem de requisição de cliente. Recebendo a requisição, o servidor retorna uma linha de estado, como "HTTP/1.1 200 OK", e uma mensagem particular própria. O corpo desta mensagem normalmente é o recurso solicitado, apesar de uma mensagem de erro ou outra informação também poder ser retornada.

## Conexões Persistentes

- No HTTP/0.9 e 1.0, a conexão é fechada após um único par de requisição/resposta. No HTTP/1.1 um mecanismo de persistência de vida (keep-alive) foi introduzido, onde uma conexão pode ser reutilizada para mais de uma requisição. Tais _conexões persistentes_ reduzem a [latência](https://pt.wikipedia.org/wiki/Lat%C3%AAncia "Latência") de requisição perceptível, pois o cliente não precisa renegociar a conexão TCP após a primeira requisição ter sido enviada. Outro efeito colateral positivo é que em geral a conexão se torna mais rápida com o tempo devido ao mecanismo de [início-lento](https://pt.wikipedia.org/wiki/In%C3%ADcio-lento "Início-lento") do TCP.
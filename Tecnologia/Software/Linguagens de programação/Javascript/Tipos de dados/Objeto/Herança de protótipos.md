- Em programação, herança refere-se à transmissão de características de um pai para um filho, de modo que um novo trecho de código possa reutilizar e se basear nos recursos de um trecho existente. O JavaScript implementa a herança usando objetos. Cada objeto possui um vínculo interno com outro objeto, chamado seu protótipo. Esse objeto protótipo possui seu próprio protótipo, e assim por diante, até chegar a um objeto com null como protótipo. Por definição, null não possui protótipo e atua como o elo final nessa cadeia de protótipos. É possível modificar qualquer membro da cadeia de protótipos ou até mesmo trocar o protótipo em tempo de execução, portanto, conceitos como despacho estático não existem em JavaScript.

## Herança com a cadeia de protótipos

##### Herança de propriedades
- Objetos JavaScript são "conjuntos" dinâmicos de propriedades (chamadas de propriedades próprias). Objetos JavaScript possuem um link para um objeto protótipo. Ao tentar acessar uma propriedade de um objeto, a propriedade será buscada não apenas no objeto em si, mas também no protótipo do objeto, no protótipo do protótipo e assim por diante, até que uma propriedade com um nome correspondente seja encontrada ou o final da cadeia de protótipos seja alcançado.

- Existem várias maneiras de especificar o [[Protótipo]] de um objeto, que serão listadas em uma seção posterior. Por ora, usaremos a sintaxe `__proto__` para fins de ilustração. Vale ressaltar que a sintaxe `{ __proto__: ... }` é diferente do acessador `obj.__proto__`: a primeira é padrão e não está obsoleta.

- Em um literal de objeto como `{ a: 1, b: 2, __proto__: c }`, o valor `c` (que deve ser nulo ou outro objeto) se tornará o [[Protótipo]] do objeto representado pelo literal, enquanto as outras chaves, como `a` e `b`, se tornarão propriedades do próprio objeto. Essa sintaxe é bastante natural, já que `[[Protótipo]]` é apenas uma "propriedade interna" do objeto.

![[Pasted image 20251105172530.png]]

- Nesse exemplo abaixo, é mostrado um algoritmo de acesso a propriedades que o Javascript possui, caso eu acesse uma propriedade que não exista no objeto, ele procura no protótipo, e se não achar, ele procura no próximo protótipo, até chegar em um objeto que não tenha protótipo (ou seja "null") : 

![[Pasted image 20251106112807.png]]


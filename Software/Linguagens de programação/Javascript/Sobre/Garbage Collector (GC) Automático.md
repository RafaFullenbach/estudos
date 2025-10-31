- Javascript possui GC automático, que é a coleta de lixo na tradução, é o mecanismo que libera memória ocupada por valores/objetos que não são mais alcançáveis pelo seu programa.

![[Pasted image 20251031090957.png]]

### Closure

- Temos que tomar cuidado com closures, que nada mais são que referências guardadas de escopo, como variáveis que já usamos, e podem estar sendo referenciadas na memória, impedindo o GC de coletar, um exemplo a seguir:

![[Pasted image 20251031091841.png]]

- Nesse caso o array gigante mesmo após o retorno, a variável "grandeObjeto" continua em memória, no caso a melhor forma de resolver isso é :

![[Pasted image 20251031092041.png]]
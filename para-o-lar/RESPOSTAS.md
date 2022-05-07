# Respostas
1) qual nivel de maturidade corresponde ao CRUD (Create, Read, Update, Delete)? 
É o API REST Maturidade 2, que possui os métodos GET (Recuperar dados), PUT(Gravar dados), Delete(Excluir dados) e POST(Gravar dados).

2) qual a relação entre os metodos HTTP e o CRUD?
os verbos HTTP se relacionam com os termos CRUD, por exemplo:  HTTP: POST, GET, PUT e DELETE e CRUD - Create, Read, Update e Delete (Criar, Ler, Atualizar e Excluir)

3) o que é HATEOAS? Ele é obrigatório para que uma API seja considerada RESTfull?
O acrônimo HATEOAS vem de Hypermedia As the Engine Of Application State e o termo “hypermedia” no seu nome já dá uma ideia de como este componente funciona em uma aplicação RESTful. Ao ser implementado, a API passa a fornecer links que indicarão aos clientes como navegar através dos seus recursos.

4) O que quer dizer quando dizemos que uma API é indepotente?
Se uma requisição idêntica pode ser feita uma ou mais vezes em sequência com o mesmo efeito enquanto deixa o servidor no mesmo estado.

5) Qual a diferença entre os métodos PUT e PATCH?
Ao usar o PUT é visivel que a alteração do dado será com referência a entidade completa, enquanto o PATCH é usado para atualização parcial, quando você não quer mandar o payload completo.

referencias: 
https://pt.stackoverflow.com/questions/217894/qual-%C3%A9-a-diferen%C3%A7a-entre-o-m%C3%A9todo-put-e-o-patch#:~:text=Em%20poucas%20palavras%2C%20os%20m%C3%A9todos,com%20refer%C3%AAncia%20a%20entidade%20completa.&text=O%20PATCH%20%C3%A9%20usado%20para,quer%20mandar%20o%20payload%20completo.

https://www.treinaweb.com.br/blog/o-que-e-hateoas

https://www.infoq.com/br/news/2009/08/CRUDREST/

https://www.programmers.com.br/blog/niveis-de-maturidade-de-uma-api-rest/

https://rivaildojunior.medium.com/modelo-de-maturidade-de-richardson-para-apis-rest-8845f93b288


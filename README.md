# Teste para vaga de estágio

## Instruções
- Tente sempre utilizar a abordagem ES6+ para resolver os exercícios;
- Os exercícios devem ser realizados no codesandbox, utilizando o template [que pode ser encontrado aqui](https://codesandbox.io/s/teste-estagio-template-mnqlh).
- Ao finalizar o teste, envie o link do seu codesandbox por mensagem lá na gupy.


## Desafio
### Resolver os seguintes exercícios
- **E.1** Crie uma função que recebe duas strings e retorna a de maior comprimento.
- **E.2** Dado a seguinte string `‘teste 1 de 2 string 3’`, substitua todas as ocorrências de números por `$`.
- **E.3** Dado o objeto `{4: ‘a’, 3: ‘e’, 1: ‘i’, 5: ‘s’}` substitua os números na frase `‘T35t3 d3 35t4g1o’` conforme a sua respectiva letra.
- **E.4** Utilizando a api da viacep (https://viacep.com.br/) e o seu cep como entrada imprima o seu endereço no formato `‘ENDERECO, NUMERO, CIDADE/ESTADO’`. Utilize a [fetch API]([https://developer.mozilla.org/pt-BR/docs/Web/API/Fetch_API](https://developer.mozilla.org/pt-BR/docs/Web/API/Fetch_API)) para realizar a requisição.

#### Para os exercícios seguintes considere o array de objetos:
```
[
    {id: 1, first_name: ‘Juca’, last_name: ‘Da Silva’, age: 42},
    {id: 2, first_name: ‘Daniel’, last_name: ‘Gonçalves’,  age: 21},
    {id: 3, first_name: ‘Matheus’, last_name: ‘Garcia’, age: 28},
    {id: 4, first_name: ‘Gabriel’, last_name: ‘Dorneles’,  age: 21}
]
```
- **E.5** Imprima uma mensagem de saudação com o nome completo para cada um dos objetos.
```
Ex.:
Olá, Fulano de tal!
Olá, Juca da silva!
...
```
- **E.6** Imprima a soma das idades (sugestão: utilizar o método [reduce]([https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)))
- **E.7** Encontre o primeiro objeto que possui uma pessoa com a idade menor que 25 e imprima seu nome. Caso não encontre, imprima que nenhum resultado foi encontrado.
- **E.8** Imprima todos os elementos em que a idade é menor que 30.
- **E.9** Ordene o array de forma decrescente por idade, em caso de empate o desempate é pelo id(em ordem crescente).

#### Para o exercício seguinte, considere os arrays de objetos:
```
const movies = [
	{ id: 1, name: 'Joker' },
	{ id: 2, name: 'Parasite' },
	{ id: 3, name: 'Avengers' },
	{ id: 4, name: 'Her' }
]
const actors = [
	{ id: 1, name: 'Cho Yeo-jeong', movie_ids: [2] },
	{ id: 2, name: 'Robert Downey Jr.', movie_ids: [3] },
	{ id: 3, name: 'Joaquin Phoenix', movie_ids: [1, 4] },
	{ id: 4, name: 'Scarlett Johansson', movie_ids: [3] }
]
```
- **E.10** Faça uma função que receba 2 parâmetros: um array de `movies` e um array de `actors`. A função deve retornar um array de `movies`, onde cada `movie` possui a propriedade `actors`, que sera um array com os nomes dos atores. Por ex:
```
[
  {
	id: 99,
	name: 'Lorem Ipsum',
	actors: ['John Doe', 'Jane Doe']
  }
]
```

Essa é a parte de anotações onde escrevemos tudo o que aprendemos.

#html
*marcações de texto*
- tag faz parte do html;
- tem abertura e fechamento;
- a escrita é fundamental, se estiver errado não funciona! ;

tag <table></table> : cria tabelas no html;
cada tabela tem uma <thead></thead> que é o cabeçalho da tabela;
cada <thead></thead>b tem uma <tr></tr> que é cada uma das linhas da tabela;
cada <tr></tr> tem um <th></th> serve para criar os cabeçalhos da tabela;
cada tabela tem o corpo dela, assim como o cabeçalho. Vamos utilizar a tag <tbody></tbody>
para criarmos o corpo da nossa tabela.
Dentro do <tbody></tbody> temos as linhas (<tr></tr>) e temos também os <td></td>;

#JavaScript 
```js
// variaveis 
const mensagem = "ola, mundo!"
// tipo de dados
  //string: caracteres
  //number: numeros
  //boolean: verdadeiro/falso
//funcao
  alert(mensagem)
```
```js
//Objeto em javaScript são as {}
const participante = {
  nome: "Jhony Cortez", // tem que colocar a Vírgula para separar 
  email: "jhony@gmail.com",
  dataInscricao: new Date(2024, 2, 22, 19, 20),
  dataChekIn: new Date(2024, 2, 25, 22, 00)
}

//array
let participantes = [
  {
   nome: "Jhony Cortez", // tem que colocar a Vírgula para separar 
   email: "jhony@gmail.com",
   dataInscricao: new Date(2024, 2, 22, 19, 20),
   dataChekIn: new Date(2024, 2, 25, 22, 00)
  },
]
```
# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 

<div align="center">
  
# *Um pouco sobre história*
### (JavaScript)

O javascript foi desenvolvido com o intuito de tornar mais interativo a relação de diversos documentos entre si. Através de Brendan Eich (funcionário de uma empresa chamada Netscape a própria empresa que criou a mozilla) foi o responsável por criar essa linguagem de programação tão conhecida nos dias atuais.
Muitas pessoas, confudem as vezes javascript, java e EcmaScript, explicando de uma forma bem prática e objetiva, java foi o primeiro a ser criado e se tornou muito popular, saindo em diversas noticias como "Java:A linguagem do futuro". O ex-funcionário da Netscape juntamente com sua equipe, numa jogada de marketing pensou "poxa, já que todos estão falando sobre java, java pra lá, java pra cá, vamos mudar invés de ser livescript (o primeiro nome da linguagem) vamos tirar o 'live' e pôr o 'java' já que está tão bem falado esse termo", e foi assim que se originou o javascript, mas, é importante ressaltar que apesar dos dois levarem o termo 'java' em seu começo, ambos não tem nada haver. O Ecmascript já é uma pegada diferente, por causa de uma confusão enorme entre a Microsoft (que copiou a ideia da Netscape, na criação da internet explorer apenas dando algumas melhoorias ao comando primário) e a Netscape, em uma jogada de mestre a netscape correu atrás de padronizar sua linguagem, através de uma empresa de padronização chamada Ecma e foi ai que surgiu o EcmaScript, uma versão padronizada do Js para evitar futuros conflitos com grandes empresas.

<img src="https://i.pinimg.com/564x/c5/20/81/c520818d9f9c98e15fcc19117b0d6e46.jpg" width="510">

<div align="center">
Brendan Eich

<div align="center">
  
# *Desenvolvimento web*

Para a criação de um bom site é necessário que contenha HTML (linguagem de marcação e Hipertexto) que vai servir para você colocar todo o conteúdo necessário, o CSS (Cascading Style Sheets. Mecanismo para adicionar estilos a uma página web) e alguma linguagem de programação para criar interações na página (alguns exemplos de linguagem: Java, JavaScript,pyton e muitas outras.)

<img src="https://i.pinimg.com/736x/5e/3f/80/5e3f80b0b4a1d9393179b79d04b1bf97.jpg" width="510">

<div align="center">

# *Estrutura de dados do javaScript*

Para programarmos em js é necessario apredermos sobre as propriedades que esta linguagem possui. Entre eles podemos citar:
- Tipos primitivos;
- Operadores;
- variáveis;
- Estruturas Condicionais.

A qual abordaremos cada um detalhadamente...

<div align="center">

# *Variáveis*

Variaveis como o próprio nome diz é um valor atribuido a algo, ficou confuso? sim? Então vamos imaginar a seguinte situação: Uma estante

<img src="https://i.pinimg.com/564x/fe/8c/c3/fe8cc38a002579a0932c0bf541293c9c.jpg" width="510">

Essa estante é a memória do computador e cada quadradinho que a compõe é considerado uma variável. Variáveis tem diversas funções e finalidades e pode representar as mais variadas coisas...

Para declarar uma variavel é necessário:

<img src="https://media.licdn.com/dms/image/v2/C4D12AQFL4z6IZ-XSHA/article-inline_image-shrink_1000_1488/article-inline_image-shrink_1000_1488/0/1610459789730?e=1729728000&v=beta&t=Zl71GsOicyvB0XE5p6ncOwc5lMGvvZmqkhRC4rkj-5w">

Demostrar ao computador que você que declarar uma variável (no exemplo temos o LET representado de roxo)

*OBS*: Existe diferentes formas que você pode declarar uma váriavel são elas:

- var: É mais antiga forma de definir variáveis no javascript. Ela pode ser reatribuída e redeclarada.
Diferentemente da const e da let ela não tem escopo de bloco.
- let: A let junto com a const vieram no ES6 (atualização de 2015). Ela também pode ter o seu valor reatribuido
mas não pode ser redeclarado.
- const: A const (constante) não pode ter seu valor reatribuído nem redeclarado. Diferentemente da let e da var. E
assim como a let ela também tem escopo de bloco.

Segundo passo é você denominar o nome da variável (por exemplo, DizerOi) e por fim eu digo para o computador que DizerOi é igual (é necessário utilizar o sinal de igual como mostra na imagem) ao valor da minha variável (no caso do exemplo acima, DizerOi tem a palavra atribuida *OI*).

Voltando para a estante que imaginamos o DizerOi seria um bloquinho da nossa estante e ocupando esse bloquinho estaria a palavra escrita *OI*.

<div align="center">

# *String*
String é um dado do tipo primitivo, onde o computador reconhece de forma literal o texto envolvido no programa. Na maioria dos casos, quando utilizamos esse tipo de dado é comum usarmos o sinal de aspas "" , crase `` ou apóstrofo '' 

``` js
console.log ("Exemplo1")
console.log (`Exemplo2`)
console.log ('Exemplo3')
```

### *Concactando string*
Concactar é um termo que utilizamos quando queremos ligar duas strings: Para concactar temos 3 métodos:
``` js
var Ex = "Exemplo"
console.log ('Primeiro'+''+"Exemplo")
console.log ("Segundo"+"Exemplo")
console.log (`Terceiro ${Ex}`)
```
# *Number*

<div align="center">
  
Number são valores numéricos (Podem ser inteiros ou decimais)

<div align="center">
  
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRq6e4KodwHTFcqVqcRaeyq99Wh9IPOahhF_w&s" width="510">

<div align="center">
  
# *Operadores*

Os operadores matématicos são de extrema importância na construção dos algoritmos, com eles podemos criar situações matemáticas e o próprio computador irá resolver (ex: equação do primeiro grau, uma fórmula de bhaskara, a velocidade média de um corpo e muito mais). Para isso utilizamos alguns sinais seja eles matemáticos, comparação e lógicos:

## *Matématicos:*
- "+" Mais;
- "-" Menos;
- "*" Multiplicação;
- "/" Divisão;
- "%" Módulo (ou resto);
- "**" Portência.

## *Comparação:*
- "==" Igual (Double equals);
- "===" Igual (Triple equals);
- ">" Maior que;
- "<" Menor que;
- ">=" Maior ou igual a;
- "<=" Menor ou igual a;
- "!==" Diferente;
- "!=" Diferente;

### Obs: Double equals
é um modo de afirma que algo é correto mesmo não sendo inteiramente fato.
Ex:
``` js
2==2 //true
2=="2" //true
```
Note que ambos vão me retornar veradeiro(true), mesmo o primeiro exemplo ser dois numbers e o segundo ser composto por um number e uma string.
### Obs: Triple equals
é um modo onde analisa ao pé da letra se os dados apresentados possuem a mesma estrutura de dados (Number ou String).
Ex:
``` js
2===2 //true
2==="2" //false
```
Note que no primeiro caso ele me retorna verdadeiro(true) por se tratar de dois numbers e no segundo me retorna falso(false) justamente por identificar que um é um number e o outro uma string.
Por isso recomendamos que as pessoas sempre utilize o triple equals, para evitar possíveis erros.

## *Lógicos*
Nesse tipo de operador temos dois sinais o "&&" que significa "E" e o "||" que significa "OU".
<div align="center">
  
Vamos imaginar a seguinte situação...

<div align="center">
  
Situação 1: Para eu ficar feliz, Mário *E* Ana deverão estar feliz
Nota: Perceba que para que uma função ocorra, ou seja, para eu ficar feliz, as duas condições deveram ocorrer, que no caso Mário e Ana estarem felizes.

<div align="center">
  
Situação 2: Para eu ficar feliz Bruno *OU* Arianne deverão estar feliz.
Nota: Veja que diferente do caso 1, para que a função ocorra não obrigatóriamente as duas condições deverão ocorrer, só precisa que ou Bruno ou Arianne estejam felizes

<div align="center">
  
<img src="https://i.pinimg.com/236x/2a/d7/9b/2ad79baf783bd0689e5d769615fc4291.jpg" width="510">

# *Estrutura Condicional*
## *If else*
A estrutura condicional é um recurso muito utilizado nos algoritmos, quando precisams criar uma condição, por exemplo, se acontecer tal coisa, execute isso, se não, então execute isso.
Exemplificando:

Se (10>=5) então

escreva 10 é maior que cinco

se não então

escreva 10 não é maior que cinco

A sintexe no JavaScrip

``` js
var A = 10
var B = 5
if (A>B){
console.log ("10 é maior que 5")
} else {
console.log (5 é mnenor que 10)
}
```
*OBS*: Se você quiser criar mais de duas condições, você irá colocar o "else if" da segunda em diante condição, e na sua última condição, você irá fechar a estrutura com o "else" como mostra o exemplo a cima.

## *Switch Case*
O switch case pode ser considerado como "Escolha caso", e como o próprio nome sugere, o código irá apresentar ao usuário diversas opções e ele fará a escolha da opção.

<img src="https://puzzleweb.ru/images/teacher/switch.jpg">

Lembre sempre de colocar em seu algoritmo, os comandos básicos do switch case, como: Switch(), case, break e o default...

- *Switch*: Normalmente é um dado de entrada que vai ser comparado com as condições propostas.
- *Case*: Condições propostas 
- *Break*: É utilizado para "quebrar" a lógica da condição, para ser apresentada outra proposta\condição
- *Default*: Esse comando deve estar presente no final de todo switch case, ele significa que, caso o dado de entrada não seja semelhante com nenhuma das opções acima, então aplicará a condição presente no default

  ## *While*
  O while pode ser considerado como "Enquanto", e normalmente esse comando é utilizado como uma espécie de contador, um looping.

  <img src="https://pimylifeup.com/wp-content/uploads/2022/05/javascript-while-loop-thumbnail.png">

    Nesse exemplo, podemos interpretar da seguinte maneira, Enquanto contador, for menor que cinco, então contador vai receber mais um, e escrever na tela "looping".

  # *Arrays*

Os arrays são como variáveis, mas diferentemente das variáveis simples, os arrys são variaveis compostas\matrizes,ou seja, ela pode ter vários valores atribuidos.

Um fator, que vale a pena ressaltar, é que os arrays são indexados em zero, ou seja, seu primeiro elemento começa com seu índice em zero e segue a diante, caso o algoritmo procure um elemento inexistente o índice que irá retornar será o -1.

### Como declarar uma Array?

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTouJTX1o3UkhmVId9zGPOZxRPA_QaXXSXSkoBBVIfK4Qn5EWsKmD2nm1J5yjNPRNncfXo&usqp=CAU" width="700" >

Para declarar uma array precisamos declarar uma variável normalmete e logo em seguida adicionar os valores atribuidos a essa variável entre os colchetes, como mostra no exemplo acima.

## Metódos de Arrays

### Método atualizar:

Mostra, Deleta e Adiciona elementos de uma array.

```js
const livros = ["Javascript Assertivo", "Engenharia de Testes", "Clean code", "Scrum", "Guia HTML5 e CSS3", "MongoDB"]


var inserir = prompt("Insira um novo livro: ")

const atualizandoLivros = livros.splice(0, 0, inserir)
//(índice localização, nº de elementos p/ deletar, adicionar)

console.log(atualizandoLivros);

console.log(livros)
```

### Método dividir:

Retorna uma cópia do array , passando dois parâmetros:

O primeiro onde deve começar.
O segundo onde dever terminar .

```js
const livros = ["Javascript Assertivo", "Engenharia de Testes", "Clean code", "Scrum", "Guia HTML5 e CSS3", "MongoDB"]

var tamanhoLivros = livros.length;
//Length = contador

var corredorA1 = livros.slice(0,tamanhoLivros/2);

var corredorA2 = livros.slice(tamanhoLivros/2);

console.log(`Os livros do corredor A1 são: `, corredorA1);

console.log(`Os livros do corredor A1 são: `, corredorA2);
```

### Método concatenar

Juntar dois ou mais arrays - retorna um novo array.

```js
const programação = ["Javascript Assertivo", "Engenharia de Testes", "Clean code", "Scrum", "Guia HTML5 e CSS3", "MongoDB"]

const Hq = ["Superman", "X-man", "vingadores", "batman", "mulher maravilha", "feiticeira Escarlate"];

const juntarLivros = programação.concat(Hq)

console.log(juntarLivros)
```

### Método pesquisar

Verificar se o elemento existe no array - retorna um valor boleano.

```js
const programação = ["Javascript Assertivo", "Engenharia de Testes", "Clean code", "Scrum", "Guia HTML5 e CSS3", "MongoDB"]
console.log(programação.indexOf("Clean code"));
console.log(programação.includes("Clean code"));
```

### Método adicionar (final)

Adicionar um ou mais elementos no final do array.

```js
const array = [1,2,3]
console.log(array) // [1,2,3]

array.push(4,5)
console.log(array) // [1,2,3,4,5]
```

### Método deletar (final)

Remover o último elemento do array.

```js
const array = [1,2,3]
console.log(array) // [1,2,3]

array.pop()
console.log(array) // [1,2]
```

### Método adicionar (começo)

Adicionar um ou mais elementos ao início do array.

```js
const array = [3,4,5]
console.log(array) // [3,4,5]

array.unshift(1,2)
console.log(array) // [1,2,3,4,5]
```

### Método deletar (começo)

Remover o primeiro elemento do array.

```js 
const array = [1,2,3]
console.log(array) // [1,2,3]

array.shift()
console.log(array) // [2,3]
```

### Método String

Juntar todos elementos de array em uma string e retorna esta string.

Receber um parâmetro que separar os elementos do array.

```js
const array = ["a", "b", "c"]
const string = array.join("-")

console.log(array) // [ 'a', 'b', 'c' ]
console.log(string) // a-b-c 
```

### Método posição

Retorna o primeiro index do elemento encontrado no array.

```js
const array = ["a", "b", "c", "d", "c"]
const index = array.indexOf("c")

console.log(index) // 2
```

### Método reverter

Inverte o array.

```js
const array = ["a", "b", "c", "d", "e"]
console.log(array) // ['a','b','c','d','e' ]

array.reverse()
console.log(array); // ['e','d','c','b','a' ]
```

# *Função*

As funções são blocos de instruções que devem ser executadas em um algoritmo quando são chamadas.

<img src="https://diegomariano.com/wp-content/uploads/2022/07/interface-grafica-do-usuario-texto-aplicativo-d-7.png">

Lembre sempre de colocar em seu algoritmo, os comandos básicos de qualquer função, como: function, titulo da função, parâmetro, chamada...

- function: Se em seu algoritmo possuir uma função é interessante que você declare logo no início de seu programa para ficar mais organizado.
- título da função: Pode ser qualquer nome, porém é aconselhável que você coloque um nome descritivo da sua função (como mostra no exemplo acima). 
- Parâmetros: Os parâmetros (isto é, os parenteses presentes na sintaxe da função), podem aparecer vazios ou com algum dado de entrada (variável), se estiver vazio é como se a função já estivesse programada para acontecer daquela forma, se estiver com algum dado de entrada a função terá que ter algum valor recebido (como no exemplo acima, recebe algum nome como dado de entrada)
- Chamada: A chamada é de suma importância, é com a chamada que a função irá ser executada, se você se esquecer da chamada sua função será anulada. Para "chamar" a função é nescessário que ao final do bloco da função, na próxima linha, você coloque o titulo da função e o parâmetro (obs: mesmo que o parâmetro esteja vazio você deve colocar).

# Atividades desenvolvidas

## Operadores matemáticos 

Identificador de número Impa ou Par:

https://codepen.io/A-Vital/pen/jOjwLRO

Calculadora:

https://codepen.io/A-Vital/pen/poXwrBJ

Salário do funcionário:

https://codepen.io/A-Vital/pen/dyBzjyw

Média do aluno:

https://codepen.io/A-Vital/pen/yLdzrmr

## Swich Case 

Verd Fruit:

https://codepen.io/A-Vital/pen/JjQOEQw

Pesquisar livros:

https://codepen.io/A-Vital/pen/YzoEZOW

## Index.of

Entrega de frutas:

https://codepen.io/A-Vital/pen/GRbydKV

## If else

Autenticação:

https://codepen.io/A-Vital/pen/OJeaZZg

## Swich case,  else if, função, arrays

Livraria Pensar:

https://codepen.io/A-Vital/pen/yLdZPym

## While, If else, função

Jogo de adivinhação:

https://codepen.io/A-Vital/pen/eYqOOYp

## Função + case

Feriados nacionais:

https://codepen.io/A-Vital/pen/VwojJKZ

## Arrays

Splint, reverse e join:

https://codepen.io/A-Vital/pen/zYgKPGa

## Função + Arrays

Seu computador:

https://codepen.io/A-Vital/pen/dyxpZZb

------------------------------------------------------------------------------------------------------------------------


# Obrigada por ler!
## Espero que tenha gostado do conteúdo

<img src="https://raw.githubusercontent.com/devcode25/devcode25/refs/heads/main/gif.gif">



<img src="https://drive.google.com/file/d/1-2ICA9YuhCPhaNmH9mm3HCGjE3dumHHM/view?usp=drive_link">







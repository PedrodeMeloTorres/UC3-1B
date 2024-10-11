# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 

# Oque é JavaScript 
Permite criar paginas web interativas e dinâmicas

## Conteúdo Técnico
### Boolean: É um tipo de dado primitivo que usa do Verdadeiro(True) ou Falso(False)
### String: É uma junção de elementos que forma uma caixa de texto.
### variáveis: Usado para armazenar informações como um cofre.
### Number: Usado pra definir numeros valores como (R$).
### Function: É um conjunto de instruções que executa uma tarefa e faz contas matemáticas.
### Array: Armazenar dados na memoria do computador.
### Switch Case: usando informações que permite usar blocos de código.
### If e Else: permite o codigo tomar decisões.
```js
const fruta = "Banana"
console.log(fruta)
```

## Atividades desenvolvidas
aprender a vender frutas e livros virtuais com uso de css

```js
const nome = "Pedro"
console.log(nome);

```

```js
const livros = ["javascript asertivo", "engenharias de testes", "clean code", "scrum", "guia html e css3", "mongoDB"];
const mangas = ["vagabond", "dragon ball z", "fire force", "fairy tale", "blood lab"];
const juntarLivros = livros.concat(mangas);
console.log(juntarLivros);

console.log(livros.indexOf("Clean code"));
console.log(livros.includes("Clean codes"));
```
Desenvolvi codigos usando Function e Switch Case

```js
function mostrarMensagem(tipoDeLuta) {
  switch (tipoDeLuta.toLowerCase()) {
    case "muay thai":
      alert("Muay Thai é conhecido como a arte dos oito membros!");
      break;
    default:
      alert("Tipo de luta não reconhecido. Tente novamente!");
  }
}

let tipoDeLuta = prompt(
  "Qual luta você deseja aprender? (Muay Thai, Karatê, Jiu-Jitsu, Taekwondo, Boxe, Capoeira, Luta de Rua, Luta Livre)"
);
mostrarMensagem(tipoDeLuta);
```
https://codepen.io/Pedro-melo-torres/pen/RwXbbdd
```js
function soma (num1, num2) {
console.log(num1 + num2)
}
console.log(soma(7,2))
```
https://codepen.io/Pedro-melo-torres/pen/BaXKGPY

# aula5
/*
* Primeiro programa em JavaScript
* Isabel Borges
*/
/*console.log ("Olá mundo!");
//prompt ("Qual é o seu nome?");
const VariavelA = 100;
const VariavelB = VariavelA + 50;
const VariavelC = VariavelA / VariavelB;
console.log(VariavelA);
console.log(VariavelB);
console.log(VariavelC);

//Variavel let
let numero = 5;
console.log(numero);
numero = 120;
console.log(numero);
numero = 120 + 5; 
console.log(numero);

//Concatenar textos
let nome = "Isabel";
let sobrenome = "Borges";
let idade = 17;
console.log("Olá" , nome, sobrenome,"voce tem", idade, "anos" );
*/
//booleanas
const variavelfalsa =false;
const variavelverdadeira = true;

console.log("Variavelfalsa: + variavelFalsa");
console.log("Variavelverdadeira: + variavelVerdadeira");

//Exercício
let nome = "Isabel";
let sobrenome = "Borges";
let idade = 17;
let estudante = "estudante";
console.log("Meu nome é", nome, sobrenome, "voce tem", idade, "anos", " e sou estudante");

//typeof
console.log(typeof nome);
console.log(typeof idade);
console.log(typeof estudante);

let banana;
console.log(typeof banana);
banana = "fruta";
console.log(typeof banana);

const vazio = null;
console.log(typeof vazio);

//PROMPT



let valor = prompt("seu nome");
console.log(valor);
let valor2 = prompt ("idade");
console.log(typeof valor);
console.log(typeof Number (valor2)); 

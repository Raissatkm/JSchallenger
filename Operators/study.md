Operações em JavaScript

JavaScript é uma linguagem de programação de alto nível amplamente utilizada para desenvolvimento web. Ela suporta diversos tipos de operações para manipular dados e executar cálculos. Neste estudo, iremos abordar os principais tipos de operações em JavaScript:

Operações Aritméticas:
JavaScript permite realizar operações matemáticas comuns, como adição, subtração, multiplicação, divisão, e outras.

Exemplos:
let a = 10;
let b = 5;

let soma = a + b;        // 15
let subtracao = a - b;   // 5
let multiplicacao = a * b;  // 50
let divisao = a / b;     // 2
let restoDivisao = a % b;   // 0
Operações de Atribuição:
É possível atribuir valores a variáveis utilizando operadores de atribuição. Esses operadores podem ser combinados com operações aritméticas.

Exemplos:

let x = 10;
x += 5;   // x agora é 15 (x = x + 5)
x -= 3;   // x agora é 12 (x = x - 3)
x *= 2;   // x agora é 24 (x = x * 2)
x /= 4;   // x agora é 6 (x = x / 4)
x %= 5;   // x agora é 1 (x = x % 5)
Operações de Comparação:
JavaScript permite comparar valores usando operadores de comparação, que retornam um valor booleano (true ou false).

Exemplos:

let a = 10;
let b = 5;

let igual = a === b;        // false
let diferente = a !== b;    // true
let maiorQue = a > b;       // true
let menorQue = a < b;       // false
let maiorOuIgual = a >= b;  // true
let menorOuIgual = a <= b;  // false
Operações Lógicas:
As operações lógicas permitem combinar expressões booleanas para formar condições mais complexas.

Exemplos:

let x = true;
let y = false;

let resultadoE = x && y;   // false (AND lógico)
let resultadoOU = x || y;  // true (OR lógico)
let resultadoNao = !x;     // false (NOT lógico)
Operações de Concatenação:
Em JavaScript, é possível concatenar strings para combinar diferentes valores em uma única string.

Exemplo:


let nome = "João";
let sobrenome = "Silva";

let nomeCompleto = nome + " " + sobrenome;  // "João Silva"
Operações com Arrays:
JavaScript possui diversas operações úteis para trabalhar com arrays, como adicionar, remover ou pesquisar elementos.

Exemplos:


let numeros = [1, 2, 3, 4, 5];

numeros.push(6);           // Adiciona o elemento 6 ao final do array
numeros.pop();             // Remove o último elemento do array (neste caso, o 6)
let indice = numeros.indexOf(3);   // Retorna o índice do elemento 3 (índice 2)
Essas são apenas algumas das operações mais comuns em JavaScript. A linguagem possui muitas outras funcionalidades, incluindo operações de bitwise, ternárias, entre outras. Com o conhecimento dessas operações, você poderá desenvolver algoritmos e scripts mais complexos para suas aplicações web.
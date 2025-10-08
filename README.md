# FuncoesJs
1° Atividade de linguagem de script  - Tutorial de como criar funções em javascript 
## Definições:
### DECLARATION:
**A função declaration é responsável por declarar uma função,ou seja tem como objetivo "dizer" ao compilador que a função existe,mais também pode ser chamada antes da declaração ser escrita,com por exemplo: Um aluno ler um texto e "anota" as palavras-chaves do texto,se fazermos uma pergunta para esse aluno ele irá responder corretamente, teria uma "base" para tal questão,da mesma forma é o compilador que lê o código e "anota" as declaration das funções. Por esse motivo pode-se usar em qualquer lugar do escopo.**

CÓDIGO DE EXEMPLO:


'''

function saudarPessoa(nome, sobrenome)

  return `Olá, ${nome} ${sobrenome}! BEM-VINDA:).`;

}

const mensagem1 = saudarPessoa('Kamily', 'Guedes');


console.log(mensagem1); 

'''

### EXPRESSION:
**É uma forma de definir uma função que é criada como parte de uma expressão maior.Tem como objetivo principal tratar as funções como valores, sendo assim o código vai se tornar mais flexível e fácil.**


CÓDIGO DE EXEMPLO:

'''

const calcularArea = function(largura, altura) {
  return largura * altura;
};


const area = calcularArea(15, 2);
console.log(`A área é: ${area}`);

'''

### ARROW:
**Tem como objetivo 
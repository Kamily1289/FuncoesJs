# FuncoesJs

1° Atividade de linguagem de script  - Tutorial de como criar funções em javascript 

## Definições:

## DECLARATION:
**A função declaration é responsável por declarar uma função,ou seja tem como objetivo "dizer" ao compilador que a função existe,mais também pode ser chamada antes da declaração ser escrita,com por exemplo: Um aluno ler um texto e "anota" as palavras-chaves do texto,se fazermos uma pergunta para esse aluno ele irá responder corretamente, teria uma "base" para tal questão,da mesma forma é o compilador que lê o código e "anota" as declaration das funções. Por esse motivo pode-se usar em qualquer lugar do escopo.**

> [!NOTE]
> CARACTERÍSTICAS-GERAIS:


##### -VANTAGENS: 
**Versatilidade, durabilidade, sensação de confiança.**

##### -DESVANTAGENS:
**Não é flexivel.**


> [!TIP]
> CÓDIGO DE EXEMPLO:

```

function saudarPessoa(nome, sobrenome) { 
  return `Olá, ${nome} ${sobrenome}! BEM-VINDA:)`; 
} 

const mensagem1 = saudarPessoa('Kamily', 'Guedes'); 
console.log(mensagem1); 


```

## EXPRESSION:
**É uma forma de definir uma função que é criada como parte de uma expressão maior.Tem como objetivo principal realizar tarefas específicas de um código e trata as funções como valores, sendo assim o código vai se tornar mais flexível e fácil. A maioria das funções expression são anônimas.**

> [!NOTE]
> CARACTERÍSTICAS-GERAIS:


##### -VANTAGENS:
**Funções anônimas, atribuição a variáveis ,possibilidade de autoexecução, não há elevação (hoisting).**

##### -DESVANTAGENS:
**Não é ultilizado para códigos grandes pela falta de estrutura, segurança e dificuldades no desenpenho.**


> [!TIP]
> CÓDIGO DE EXEMPLO:

```

const calcularArea = function(largura, altura) {
  return largura * altura;
};


const area = calcularArea(15, 2);
console.log(`A área é: ${area}`);

```

### ARROW:
**Tem como objetivo reduzir/responder códigos curto, deixa o código mais limpos e consequentemente aumentado a legibilidade, 
ultiliza o sinal "=>" para subistituir o (fuction).**


> [!TIP]
> CÓDIGO DE EXEMPLO:

```
 const cumprimentar = (sobrenome) => `Olá, ${sobrenome}!`;
    console.log(cumprimentar("sra.Guedes")); 
  ```  


> [!NOTE]
> CARACTERÍSTICAS-GERAIS:

##### -VANTAGENS:
**Retorno implícito, simplificação de callbacks , sintaxe concisa.**

##### -DESVANTAGENS:
**Falta do ```this``` (herdando ```this``` do escopo).**

> [!TIP]
> CÓDIGO DE EXEMPLO:

```
const soma = (U, P) => U+ P;

```
> [!IMPORTANT]
> CONCLUSÃO:

**Portanto pode-se conccluir que as funçoẽs tem como objetivo principal organizar em pequenos blocos para facilitar o gerênciamento do código,os quais estão sendo ultilizado. De modo, que as funções iram automatomatizar as tarefas.**



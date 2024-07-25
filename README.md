"# learning_javascript" 

- Aula 1

*instalaão completa de node-js (COMPLETA)

version
´´´
node -v
´´´

Sem necessidade de finalizar as linhas de comando com o amado ";"


Para imprimir o texto sem precisar de um browser, apenas no terminal executando node "nome_arquivo.js"
´´´
console.log("Alô mundo") 
´´´

#Comentários em // para linha e comentários /**/ em bloco


Java script é exacutada em tempo real, é um linguagem interpretava pelo node ou via browser por ele mesmo.


- Aula 2 

Oque é Strict Mode?

O "strict mode" em JavaScript é uma forma de executar o código em um modo mais restrito, ajudando a identificar erros e a evitar alguns comportamentos problemáticos que são permitidos no modo normal. Ele foi introduzido no ECMAScript 5 (ES5).

Principais Benefícios do Strict Mode:
- Elimina alguns erros silenciosos:

No strict mode, algumas operações que normalmente falham silenciosamente vão lançar exceções. Por exemplo, atribuir um valor a uma variável não declarada lançará um erro.
- Previne o uso acidental de variáveis globais:

No strict mode, atribuir um valor a uma variável que não foi declarada com var, let, ou const resultará em um erro.
- Proíbe a duplicação de nomes de propriedade e parâmetros:

No strict mode, não é permitido definir duas propriedades com o mesmo nome em um objeto ou definir dois parâmetros de função com o mesmo nome.
- Modifica o comportamento do this em funções:

No strict mode, se this for usado em uma função que não é chamada como um método de objeto, ele será undefined em vez de referir-se ao objeto global.
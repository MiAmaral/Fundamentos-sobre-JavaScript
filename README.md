## ✨ Projeto desenvolvido para estudo do JavaScript, promovido pelo programa START da Capgemini e elaborado pela ProWay ✨

### 📝  JavaScript é uma linguagem de programação de alto nível, dinâmica e interpretada que é amplamente usada para criar páginas web interativas e aplicações web. É uma das principais linguagens de programação da web e é executada no lado do cliente (navegador do usuário) e no lado do servidor (servidor web). JavaScript é conhecido por sua capacidade de manipular e controlar o conteúdo da página web, permitindo a criação de animações, efeitos visuais e interações de usuário.

📌 **INTRODUÇÃO**

• **Variáveis**: Variáveis em JavaScript são usadas para armazenar valores que podem ser usados ​​em um programa. Elas podem ser declaradas usando as palavras-chave "var", "let" ou "const", e podem conter diferentes tipos de dados, como números, strings, booleanos, arrays, objetos, entre outros.

• **Operadores Relacionais**: Operadores relacionais em JavaScript são usados para comparar valores e verificar se uma determinada condição é verdadeira ou falsa.

    · Igualdade (==): Compara se dois valores são iguais em valor, ignorando o tipo de dados. Por exemplo, "3" == 3 é verdadeiro porque ambos são iguais em valor, mas "3" === 3 é falso porque são diferentes em tipo.

    · Desigualdade (!=): Compara se dois valores são diferentes em valor, ignorando o tipo de dados. Por exemplo, "3" != 4 é verdadeiro porque são diferentes em valor, mas "3" !== 3 é verdadeiro porque são diferentes em tipo.

    · Estritamente igual (===): Compara se dois valores são iguais em valor e tipo de dados. Por exemplo, "3" === 3 é falso porque são diferentes em tipo.

    · Estritamente desigual (!==): Compara se dois valores são diferentes em valor e tipo de dados. Por exemplo, "3" !== 3 é verdadeiro porque são diferentes em tipo.

    · Maior que (>): Compara se o primeiro valor é maior que o segundo valor.

    · Menor que (<): Compara se o primeiro valor é menor que o segundo valor.

    · Maior ou igual (>=): Compara se o primeiro valor é maior ou igual ao segundo valor.

    · Menor ou igual (<=): Compara se o primeiro valor é menor ou igual ao segundo valor.

• **Condicional Simples**: As estruturas condicionais são usadas para executar diferentes ações com base em uma condição. A condicional simples é a mais básica e é representada pelo "if", que verifica se uma condição é verdadeira e, em seguida, executa um bloco de código se ela for verdadeira. Se a condição for falsa, o bloco de código não será executado.

• **Condicional Aninhada**: A condicional aninhada é uma estrutura de controle de fluxo em que uma instrução condicional é colocada dentro de outra instrução condicional. Essa estrutura permite verificar múltiplas condições em uma ordem específica e executar diferentes blocos de código com base nessas condições. No entanto, o uso excessivo de condicionais aninhadas pode tornar o código difícil de ler e entender, tornando necessário encontrar um equilíbrio entre a legibilidade e a funcionalidade do código.

• **Operador Lógico E**: O operador lógico "E" é representado por "&&" e é usado para combinar duas ou mais expressões booleanas. Ele retorna "true" se todas as expressões forem verdadeiras e "false" se pelo menos uma delas for falsa.

• **Operador Lógico OU**: O operador lógico "OU" é representado por "||" e é usado para combinar duas ou mais expressões booleanas. Ele retorna "true" se pelo menos uma das expressões for verdadeira e "false" somente se todas as expressões forem falsas.

• **Operador Lógico NÃO**: O operador lógico "Não" é representado por "!" e é usado para negar uma expressão booleana. Ele inverte o valor de verdade da expressão. Se a expressão for verdadeira, o operador "Não" retorna "false". Se a expressão for falsa, o operador "Não" retorna "true".

• **Estrutura de escolha SWITCH**:  A estrutura de escolha "switch" é usada para avaliar uma expressão e executar um bloco de código dependendo do valor dessa expressão. É geralmente utilizada quando se tem várias opções a serem escolhidas.
Na expressão, é passada a variável ou valor a ser avaliado(expressão). Nos casos, são listados os valores que a expressão pode assumir e o bloco de código correspondente a ser executado. O "break" é utilizado para indicar que a execução deve parar após o bloco de código ser executado.
Se a expressão não corresponder a nenhum dos valores listados nos casos, então o bloco de código dentro do "default" é executado, sendo possível ter somente um valor "default".

• **Estrutura de repetição WHILE**: A estrutura de repetição "while" é utilizada para repetir um bloco de código enquanto uma condição especificada for verdadeira. A condição é verificada no início de cada iteração do "while". Se a condição for verdadeira, o bloco de código é executado. Depois disso, a condição é verificada novamente, e assim por diante, até que a condição se torne falsa. Quando a condição se torna falsa, a execução do "while" é encerrada e o controle é passado para a próxima linha de código após o bloco de "while".
É importante garantir que a condição dentro do "while" eventualmente se torne falsa, caso contrário, o bloco de código será executado indefinidamente, o que é conhecido como um "loop infinito".

• **Estrutura de repetição DO - WHILE**: A estrutura de repetição "do-while" é semelhante à estrutura "while", mas com uma diferença fundamental: a condição é verificada após a execução do bloco de código, garantindo que o bloco de código seja executado pelo menos uma vez, independentemente da condição ser verdadeira ou falsa. Assim como com a estrutura "while", é importante garantir que a condição dentro do "do-while" eventualmente se torne falsa, caso contrário, o bloco de código será executado indefinidamente, o que é conhecido como um "loop infinito".

• **Estrutura de repetição FOR**: A estrutura de repetição "for" é usada para executar um bloco de código repetidamente por um número específico de vezes, com base em um contador. O "for" é especialmente útil quando você sabe de antemão quantas vezes um bloco de código precisa ser executado.

>***Quando usar a estrutura WHILE e a FOR?***

    ↳ O "while" é geralmente usado quando você não sabe quantas vezes um bloco de código precisa ser executado. Você pode usar uma condição para verificar se o bloco de código precisa ser executado novamente ou não. Além disso, o "while" é útil para repetir o código enquanto uma condição específica for verdadeira, por exemplo, até que um usuário digite uma entrada válida.

    Por outro lado, o "for" é usado quando você sabe de antemão quantas vezes um bloco de código precisa ser executado. Isso porque você pode especificar um número específico de iterações, com base em um contador. Além disso, o "for" é útil quando você precisa percorrer uma lista de itens ou executar o mesmo bloco de código várias vezes com valores diferentes de variáveis.

• **Vetor(Array)**: Um vetor é uma estrutura de dados que armazena um conjunto de valores em uma única variável. Cada valor em um vetor é identificado por um índice numérico inteiro, que começa em 0 para o primeiro valor, 1 para o segundo valor e assim por diante. Esses valores podem ser de qualquer tipo de dado, como números, strings ou objetos.

• **Vetor de Objetos**: Um vetor de objetos é uma estrutura de dados que armazena um conjunto de objetos em uma única variável. Cada objeto dentro do vetor é identificado pelo seu índice numérico inteiro, assim como em um vetor de valores simples.
Cada objeto dentro do vetor pode ter propriedades e métodos que podem ser acessados usando a notação de ponto. Isso significa que podemos definir um objeto com suas próprias propriedades e métodos, como se fosse uma variável única, e então armazená-lo em um vetor juntamente com outros objetos semelhantes.
Essa estrutura de dados é muito útil quando precisamos armazenar e manipular um conjunto de objetos relacionados, como por exemplo uma lista de usuários em um sistema, uma lista de produtos em uma loja virtual, ou uma lista de tarefas em um aplicativo de gerenciamento de projetos.

📌 **FUNÇÕES**

• **O que são funções?**: Uma função é um bloco de código que executa uma tarefa específica. Ela pode ser definida para executar uma ação específica, como calcular um valor, exibir uma mensagem na tela ou interagir com outros elementos da página da web.
Uma função é definida usando a palavra-chave 'function', seguida pelo nome da função e, entre parênteses, uma lista de parâmetros que a função pode receber. Em seguida, o corpo da função é definido entre chaves '{ }', onde o código que a função deve executar é escrito.

📌 **EVENTOS**

• **O que são eventos?**: Eventos são ações que ocorrem em resposta a uma interação do usuário com a página web ou ações do próprio navegador. Esses eventos podem ser usados para disparar funções ou executar códigos específicos em resposta a essas interações.
Existem muitos tipos de eventos em JavaScript, incluindo eventos de mouse, eventos de teclado, eventos de formulário, eventos de carregamento de página e eventos personalizados. Exemplo de eventos:

    · onclick - É acionado quando um elemento HTML, como um botão, é clicado. É uma das formas mais simples de lidar com eventos em JavaScript.

    · onchange -  E acionado quando o valor de um elemento HTML, como um input ou select, é alterado. É útil para lidar com interações do usuário que exigem atualizações dinâmicas na página.

    · onload - É acionado quando um objeto, como uma imagem, é carregado na página. É útil para lidar com ações que devem ocorrer assim que um objeto é carregado, como exibir uma imagem ou executar uma função depois que a página é carregada.

    · onkeypress - É acionado quando uma tecla é pressionada e mantida pressionada. O evento ocorre continuamente enquanto a tecla é pressionada e pode ser usado para executar ações que exigem entrada contínua do usuário, como mover um personagem em um jogo.

    · onkeyup - É acionado quando uma tecla é solta após ser pressionada. O evento ocorre apenas uma vez e pode ser usado para executar ações que exigem entrada única do usuário, como enviar um formulário quando o usuário pressiona a tecla Enter.
    
    · onkeydown - É acionado quando uma tecla é pressionada, mas antes de ser mantida pressionada. O evento ocorre apenas uma vez e pode ser usado para executar ações que exigem entrada única do usuário, como navegar em uma lista usando as teclas de seta.

📌 **SELETORES DE CONTEÚDO**

• **O que são seletores de conteúdo?**: Em JavaScript, os seletores de conteúdo são usados para selecionar e manipular elementos HTML com base em critérios específicos, como sua classe, id, tag ou atributos personalizados. Esses seletores são semelhantes aos usados em CSS e são uma maneira poderosa de acessar e manipular elementos HTML em uma página.

✌️  

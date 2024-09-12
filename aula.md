## Linguagem de programação

Maneira de dar instrução ao computador.
Como um lego, você irá utilizar peças para criar algoritmos, ou seja, para resolver problemas.

> 💡 **Algoritmo**: Sequência de passos lógica e finita para resolução de um problema.

## Peças de uma linguagem

- Comentários
- Declaração de variáveis (const, let)
- Operadores (atribuição, concatenação, matemáticos, lógicos )
- Tipos de dados (string, number, boolean)
- Estrutura de dados (functions, object, array)
- Controle de fluxo (if/else)
- Estrutura de repetição (for, while)

# Fases da resolução de um problema

Coletar os dados
Processar os dados (manipular, alterar ...)
Apresentar os dados

## Escopo e variáveis:

- [x] Variáveis globais e locais
- [x] Constantes

## Tipos de dados:

- [x] Strings (texto): "" '' ``
- [x] Numbers: 2 1.4
- [x] Boolean: true, false

# Operadores

- [x] Operadores de atribuição de valor: =
- [x] Operador de contatenação: +
- [x] Spread operator: ...

## Estruturas de dados:

### Arrays: 

- [x] Uma lista que contém qualquer tipo de dado 
- [x] Métodos de array: push, [find, forEach, filter] : HOF (Higher order Functions)

### Objetos:

- [x] Atributos e métodos
- [x] Criação e manipulação de objetos
- [x] Acesso a propriedades de objetos

### Functions

- [x] criar, passar argumento
- [x] excutar
- [x] arrow function / named function

## Explicação do código function com Gemini
Linha a Linha
1. function start() {

Declaração de função: Cria uma função chamada start. As instruções dentro das chaves serão executadas quando a função for chamada.
2. let count = 0

Declaração de variável: Cria uma variável chamada count e atribui o valor 0 a ela. Essa variável será usada para controlar o loop.
3. while(count < 10){

Início do loop: Inicia um loop while. O loop continuará enquanto a condição count < 10 for verdadeira.
4. console.log(count)

Impressão no console: Imprime o valor atual da variável count no console do navegador ou terminal.
5. count = count + 1

Incremento da variável: Adiciona 1 ao valor atual da variável count.
6. }

Fim do loop: Indica o final do loop while.
7. start()

Chamada da função: Chama a função start, iniciando sua execução.
Resumo
O código acima define uma função chamada start que imprime os números de 0 a 9 no console. A função utiliza um loop while para repetir o processo de impressão até que o valor de count atinja 10.

# Estrutura de repetição

- [x] while

# Condicionais

- [x] switch
- [x] if/else

## Módulos em Node.js:

- [x] Importação de módulos (require, CommonJS)
- [x] Biblioteca 'inquirer' para criar prompts interativos

## Programação assíncrona e Promises:

- [x] Uso de funções assíncronas (async/await)
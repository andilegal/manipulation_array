# manipulation_array
manipulation array (split, splice, slice, unshift, shift, pop, push)

//                 -6       -5         -4          -3         -2        -1
//                  0        1          2           3          4         5
// const names = ["zero",'primeiro',"segundo", "terceiro", "quarto", "quinto"]

// APENAS UTILIZAR SPLICE COM STRING RETORNA O VALOR
// SPLICE COM NUMBER TE RETORNA O ARRAY TODO SE VC CHAMAR O ARRAY DEPOIS QUE A MANIPULAÇÃO FOR FEITA

// splice 
// foi criado para simplicifacar a busca simulando os outros metodos (split, splice, slice, unshift, shift, pop, push) de um jeito mais simples
// Exemple:
// splice('index', 'delete', 'elemt1', 'elemt2', 'elemt3')

// pop -> remove o ultimo elemento e retorna o próprio (splice simulando), mais fácil usar o próprio método
// let removed = names.splice(-1, 1)
console -> 'quinto'

// push -> insere na última posição um elemento no array (splice simulando), mais fácil usar o próprio método
// let removed = names.splice(names.length, 0 , "sexto")
console -> 'sexto'

// unshift -> adiciona um elemento na primeira posição (splice simulando), mais fácil usar o próprio método
// let removed = names.splice(0, 0, "antes do zero")
console -> 'antes do zero'

// shift -> removendo o primeiro elemento no array (splice simulando), mais fácil usar o próprio método
// let removed = names.splice(0, 1, 'Removido o primeiro elemento')
console -> 'zero'

// join
// Junta os elementos do array. 
// o primeiro parametro determina qual o critério de junção do array. (' ', ',' , '/')
// Exemple:
// let joy = names.join(' ')

// split
// Separa os elementos do array.
// o primeiro parametro determina qual o critério de separação do array. (' ', ',' , '/')
// Exemple:
// let split = names.split(' ')

// slice 
// Determina onde começa a fazer a busca no array e termina
// primeiro parametro é o indice que começa e o segundo é onde termina.
// splice(1, 4)
// console -> [ 'primeiro', 'segundo', 'terceiro', 'quarto' ]

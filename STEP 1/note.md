LECON DU  25 /10 /2022

 <h1>Cours 1</h1>
        <ol>
            <li>Introduction sur JS</li>
            <li>Déclaration des variables</li>
            <li>Les conditions </li>
            <li>Les Boucles</li>
            <li>Les tableaus</li>
            <li>Functions</li>
        </ol>


BOUCLE WHILE
const value = prompt('Max : ');
let i = 0;
while (i < value) {
// Incrémenter
 i++
 console.log(value - i);
}

BOUCLE FOR 
for(initialisation; condition d'arrêt ; step){
    
}

## Table de Multiplication

let x = 13
let y = 13
for(let i = 0; i < x; i++){
    for(let j = 0; j <y; j++){
        console.log(`${i} x ${j} =${i*j} `)
        }
    console.log("===============")
}

###  
const x = prompt('Enter X : ')
   const y = prompt('Enter Y : ')
   for(let i = 0; i <x ; i++){
    for(let j = 0; j <y; j++){
        console.log(` ${i} X ${j} = ${i * j}`)
    }
    console.log(":================")
   }

# JavaScript Data Types

let length = 16;                               // Number <br>
let lastName = "Johnson";                      // String <br>
let x = {firstName:"John", lastName:"Doe"};    // Object <br>

## Exemple d'une Fonction 

<pre>

function direBonjour(name){
        console.log(name +" ,  Good Morning !!")
    }
    
    function countTo(value){
        for(let i=1; i<=value ; i++)
            console.log(i)
    }

    function tableMultiplication(v){
        for(let i=1;i < v; i++){
            for(let j=0; j < v; j++){
                console.log(`${i} X ${j} = ${ i * j}`)
            }
            console.log('===============')
        }
    }

    tableMultiplication(5)

</pre>
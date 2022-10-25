LECON DU  25 /10 /2022

 <h1>Cours 1</h1>
        <ol>
            <li>Introduction sur JS</li>
            <li>Declaration des variables</li>
            <li>Les conditions </li>
            <li>Les Boucles</li>
            <li>Les tableau</li>
            <li>Function</li>
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
<pre>
'use strict'

const Elodie = {
    firstName: 'Ishwimwe',
    lastName: 'Elodie',
    age: '22',
    gender: 'F',
    greeting: function(name) {
        console.log(this.firstName + ' Says  ' +"Hello " + name)
    },
    calculate: ()=>{
        console.log(this)
        // Calacule
        console.log("Je pense 0.......... ccalalalal")

    }
}
    console.log(this)
    Elodie.calculate()
</pre>
//!Contador Ascendente: Imprime los números del 1 al 10 en orden ascendente.
//!Contador Descendente: Imprime los números del 10 al 1 en orden descendente.
//!Suma de Números: Calcula la suma de los números del 1 al 10.
//!Tabla de Multiplicar: Pedir al usuario un numero y mostrar su tabla de multiplicar.
//!Contador Pares: Imprime los números pares del 2 al 20.
//!Contador Impares: Imprime los números impares del 1 al 19.
//!Contador de Dígitos: Cuenta la cantidad de dígitos en un número dado.

//let num= 0;

//Contador Ascendente= Imprime los números del 1 al 10 en orden ascendente.

for (let i = 1; i < 10; i++) {
    console.log(i); 
}
let num = 1;

while(num < 10 ){
    console.log(num);
    num++
}

//Contador Descendente=  Imprime los números del 10 al 1 en orden descendente.

for (let i = 10; i < 1; i--) {
    console.log(i); 
}
let num1 = 10;

while(num > 1 ){
    console.log(num);
    num--;
}

//Suma de Números: Calcula la suma de los números del 1 al 10.

 let sum=0
 for(let i=1; i<=10; i++){
    sum=sum+i
 }
 console.log(sum)


//TABLA DE MULTIPLICAR= Pedir al usuario un numero y mostrar su tabla de multiplicar.

  let   num = parseInt(prompt("ingrese un numero:")) 

  for (let i=0; i<=10; i++){
    console.log(num*i)
}



//CONTADOR DE PARES: Imprime los números pares del 2 al 20.

 for(let i=2; i<=20; i=i+2){
     console.log(i)
 }



//CONTADOR DE IMPARES: Imprime los números impares del 1 al 19.

for(let i=1; i<20; i=i+2){
     console.log(i)
}

//CONTADOR DE DIGITOS: Cuenta la cantidad de dígitos en un número dado.

/let num=(parseInt(prompt("Ingrese un numero")))
 let aux=0
 let c=0

 while(num>=1){
    aux=parseInt(num/10)
    num=aux
    c++
}

console.log("Elnumero ingresado tiene ", c, "digitos.")

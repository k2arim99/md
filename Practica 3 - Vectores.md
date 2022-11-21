Fecha de entrega: 16 nov, 23:59



PRACTICA 3 - VECTORES

1. Desarrollar un algoritmo que realice las siguientes operaciones:
a. Almacene los 30 primeros números pares enteros y almacénese en
un vector llamado vec.
b. Calcule e imprima la suma y el promedio de los números
almacenados en el vector vec.

```c

Algoritmo uno{
    Entero vec[30],contador,tiranumeros,suma;
    Mientras(contador<=29){
        Tiranumeros++;
        Si(tiranumeros%2==0){
            Vec[contador]=tiranumeros;
            contador++;
        }
    }
    Para(contador=0,contador<=29,contador++){
        Suma+=vec[contador];
        }
    Imprimir("la suma de los números es", suma, " y el promedio es " suma/30.0 );
    //los promedios son flotantes!! Entero/flotante= flotante
}
````

  

2. Desarrollar un algoritmo que realice las siguientes operaciones:
a. Lea desde el teclado 10 números reales cualesquiera y almacénese en
un vector num.
b. Calcule el promedio de los números almacenados en el vector num.
c. Calcule e imprima cuántos elementos del vector num son mayores
que el promedio y cuántos menores o iguales.

````c

Algoritmo dos{
    Flotante num[10],contador,promedio,cantmayor,suma,cantmenor;
    Para(contador=0,contador<=9,contador++){
        Imprimir("inserte número");
        Leer(num[contador]);    
    }
    Para(contador=0,contador<=9,contador++){
        Suma+=num[contador];
        }
    Promedio=suma/10.0;
    Para(contador=0,contador<=9,contador++){
        Si(num[contador]>promedio)
            Cantmayor++;
        Sino
            Cantmenor++;
    }
    Imprimir("la cantidad de menores o iguales que el promedio es", cantmenor);
    Imprimir("la cantidad de mayores que el promedio es", cantmayor);
}
````


3. Diseñe un algoritmo que realice las siguientes operaciones:
a. Lea 25 números enteros cualquiera y almacénelos en un vector
llamado datos.
b. Imprima la siguiente infotmación:
c. Si el número almacenado en la dirección 5 del vector datos es
positivo, imprima el siguiente mensaje: “EN LA DIRECCIÓN 5 DEL
VECTOR DATOS HAY ALMACENADO UN NUMERO POSITIVO”.
d. Si el número almacenado en la dirección 1 del vector datos es
negativo, imprima el siguiente mensaje: “EN LA DIRECCIÓN 1 DEL
VECTOR DATOS HAY ALMACENADO UN NUMERO NEGATIVO”.
e. Si el número almacenado en la última casilla del vector datos es
cero, imprima el siguiente mensaje: “EN LA DIRECCIÓN 24 DEL
VECTOR DATOS HAY ALMACENADO UN CERO”.
````c

algoritmo tres{
entero datos[25],contador;

mientras(contador<25){
    contador++;
    imprimir("inserte los numeros del vector");
    leer(datos[contador]);
}
si(datos[5]>0)
    imprimir(“EN LA DIRECCIÓN 5 DEL
VECTOR DATOS HAY ALMACENADO UN NUMERO POSITIVO”);
si(datos[1]<0)
    imprimir(“EN LA DIRECCIÓN 5 DEL
VECTOR DATOS HAY ALMACENADO UN NUMERO POSITIVO”);
si(datos[24]==0)
    imprimir(“EN LA DIRECCIÓN 24 DEL
VECTOR DATOS HAY ALMACENADO UN CERO”);

}
````



4. Diseñe un algoritmo que realice las siguientes operaciones:
a. Lea 12 números enteros desde el teclado y almacénelos en un
vector llamado valor.
b. Imprima el 25% de los números almacenados en el vector valor.
````c

algoritmo cuatro{
entero valor[12],contador,suma;
mientras(contador<12){
    contador++;
    imprimir("inserte los numeros del vector");
    leer(valor[contador]);
    suma+=valor[contador];
}
imprimir("el 25% de los numeros ingresados sumados es", suma/4);
}
````


5. Diseñe un algoritmo que realice las siguientes operaciones:
a. Lea 5 números enteros desde el teclado y almacénelos en un vector
llamado numero.

b. Calcule e imprima el cuadrado de cada uno de los datos almacenado
en el vector numero.

````c
algoritmo cinco{
entero numero[5],contador,suma;
mientras(contador<5){
    contador++;
    imprimir("inserte los numeros del vector");
    leer(numero[contador]);
}
mientras(contador<5){
    contador++;
    imprimir(" el cuadrado de los numeros es ", numero[contador]^2);
}
}
````





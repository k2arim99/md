
31/10/2022
Práctica 1 (Vectores)

Escribir un algoritmo que realice las siguientes operaciones:

-   Lea 10 números enteros y almacénese en un vector llamado vec.
    
-   Lea un número entero cualquiera desde el teclado.
    
-   Calcule e imprima cuantas veces se encuentra almacenado el número leído en el punto anterior, dentro del vector vec.
    

SOLUCIÓN:
```c++
algoritmo(uno){
entero indice=0, vec[10]={0},num=0,contador=0;

//En esta sección se lee los números desde el teclado y se almacenan en el arreglo

Para(índice=0;índice<=9,índice=índice+1)

{

  Imprimir(“Entre un numero entero cualquiera: “);

  Leer(arreglo[índice]);

}

  

// Leer un numero entero cualquiera desde el teclado

Imprimir(“Entre un numero entero cualquiera: “);

  Leer(num);
//En esta sección se calcula e imprime cuantas veces se encuentra el número leído en el paso anterior.

Para(índice=0;índice<=9,índice=índice+1)
{
  Si(num==vec[índice])

{

Contador=contador+1;
}
}
 Imprimir(“El numero leído se encuentra: “, contador, “dentro del vector vector”);
}
```
  
  
  

2.  Escribir un algoritmo que realice las siguientes operaciones:

-   Lea 10 letras minúsculas cualquiera y almacénelos en un vector llama letreas
-   Imprima las vocales almacenadas en el vector letras junto con su dirección 

SOLUCIÓN:
```c++
algoritmo(dos){


entero indice=0, letreas[10]={0},contador=0;

//En esta sección se lee las letras desde el teclado y se almacenan en el arreglo

Para(índice=0;índice<=9,índice=índice+1)

{

  Imprimir(“Entre una letra minúscula cualquiera: “);

  Leer(letras[índice]);

}

  

// Leer una letra minúscula cualquiera desde el teclado

Imprimir(“Entre una letra minúscula cualquiera: “);

  Leer(letras[contador]);

  

//En esta sección se calcula e imprime cuantas veces se encuentra la letra leída en el paso anterior.

Para(índice=0;índice<=9,índice=índice+1)
{
  Si(letras[contador]==letras[índice])
compara la letra leída con la almacenada en el vector
{
contador=contador+1;
}
}
 Imprimir(“La letra leída se encuentra: “, contador, “dentro del vector letras”);
}
```
  
  

3.  Escribir un algoritmo que realice las siguientes operaciones:
    
-   Leer 50 números y almacenarlos en un vector llamado num
-   Busque e imprima el mayor valor (y su dirección) almacenado en el vector num.
-   Busque e imprima el menor valor (y su dirección) almacenado en el vector num.
    


```c++
algoritmo(tres){
    entero num[50],contador=0,mayor=0,menor=0;
    Para(contador=0;contador<=49,contador++) {
        Imprimir(“Entre un numero entero cualquiera“); 
        Leer(num[contador]); 
        contador++;
    }
Para(contador=0;contador<=49,contador++) {
        si num[contador]>mayor
            mayor=num[contador]
        si num[contador]<menor
            menor=num[contador]
    }
    imprimir("el mayor valor es ",mayor);
    imprimir("el menor valor es ",menor);
}
```
  
  
  

4.  Escribir un algoritmo que realice las siguientes operaciones:
    

-   Leer 50 números cualquiera y almacenarlos en un vector llamado arreglo
    
-   Calcule e imprima total de números leído menores a 7
    
-   Calcule e imprima el promedio de números leídos que están en el rango de 8 a 48, inclusive,
    
-   Calcule e imprima la suma de los números leídos mayores a 48.  
    

  

```c++
algoritmo(cuatro){
    entero numero,contador=0,arreglo[50],indice,mayor7,contador8,rango8,promedio
    Para(contador=0;contador<=49,contador++) {
        Imprimir(“Entre un numero entero cualquiera“); 
        Leer(arreglo[contador]); 
        contador++;
    }
    Para(contador=0;contador<=49,contador++) {
        si arreglo[contador]<7
            mayor7++;
    }
    imprimir("la cantidad de numeros menores a 7 es:",mayor7);
     Para(contador=0;contador<=49,contador++) {
        si arreglo[contador]>=8 && arreglo[contador]<=48{
            contador8++
            rango8+=arreglo[contador]
        }
    }
    promedio=rango8/contador8
    imprimir("el promedio del rango de 8 a 48 es ",promedio);
    Para(contador=0;contador<=49,contador++) {
        si arreglo[contador]>48
            suma+=arreglo[contador]
    }
    imprimir("la suma de los numeros mayores a 48 es ",suma);
}
```
  
  
  
  

5.  Escribir un algoritmo que realice las siguientes operaciones:
    
-   Leer 20 números cualquiera y almacenarlos en un vector llamado arr
-   Calcular e imprimir el promedio de elementos impares y el promedio de elementos pares almacenados en un vector.  
```c++
algoritmo(cinco){
    entero contador=0,arr[20]={0},promediopares=0,promedioimpares=0,contpares,contimpares;
    imprimir(“el número de números que va a ingresar es:“,contador);
    Para(contador=0;contador<=19,contador++) {
        Imprimir(“Entre un numero entero cualquiera“); 
        Leer(arr[contador]); 
        contador++;
    }
    Para(contador=0;contador<=19,contador++) {
        si contador%2==0
            contpares++;
        si contador%2!=0
            contimpares++;
    }
    promediopares=contpares/contador;
    promedioimpares=contimpares/contador;
    imprimir("el promedio de los numeros pares es ",promediopares);
    imprimir("el promedio de los numeros impares es ",promedioimpares);
}
```



[[Logica de Programacion 2]]
# DESCRIPCIÓN DEL PROBLEMA

Realiza un programa que permita identifcar un numero entero ingresado de la siguiente manera.
1. si es par
2. si es impar
3. si es nulo

# SOLUCIÓN DEL PROBLEMA
#include iostream
#include stdlib.h
#include stdio.h

   using namespace std;
   int main (){
    int num;

    cout "ingrese el numero"
    cin num;

    if ( num == 0){
        cout "el numero es nulo";
    else if (((num%2)==0)){
        cout "el numero es par;
    else if (((num%2)0)){
        cout "el numero es impar;
    }
    else{
        cout "el numero es menor a cero";

        system ("pause");
    }
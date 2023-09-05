# DESCRIPCION DEL PROBLEMA
REaliza un programa que permita determinar la edad mayor de dos hermanos. Muestre la edad mayor en pantalla.

# SOLUCION DEL PROBLEMA
#include <iostream>
#include <stdlib.h>
#include <stdio.h>

using namespace std;
int main(){ 
    int edad_1,edad_2;

    cout<<"ingrese la primera edad";
    cin>>edad_1;
    cout<<"ingrese la segunda edad";
    cin>>edad_2;

    if(edad_1>edad_2){ 
        cout<<"la primera edad es menor";
    }
    else{ 
        cout<<"la segunda edad es mayor";

        system ("pause");
         }
     }
     
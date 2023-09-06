# DESCRIPCION DEL PROBLEMA
Realiza un programa que permita mostrar el resultado de una potencia de base N y exponente X. siclo for

# SOLUCION DEL PROBLEMA
#include <iostream>
#include <stdlib.h>
#include <stdio.h>

using namespace std;
int main()
    int base,expo,cont=0,pot=1;

    cout<<"ingrese la base;
    cin>>base;
    cout<<"ingrese el exponente;
    cin>>expo;
    
    while (cont<expo){ 
        pot*=base;
        cont+=1;
     }
       cout<<"el resultado de la potencia es: "<<pot;
 }    
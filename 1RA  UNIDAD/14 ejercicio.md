# DESCRIPCION DEL PROBLEMA 
Realice un programa que realice un descuento de 3% de una compra si el total de la compra es mayor a Q.500

# SOLUCION DEL PROBLEMA
#include <iostream>
#include <stdlib.h>
#include <stdio.h>

using namespace std;
int main(){ 
    int desc,tot_pag;

    cout<<"ingrese el total de su compra";
    cin>>tot_pag;

    if(tot_pag>5000){ 
        desc=(tot_pag*3)/100;
        cout<<"usted tendra un descuento de 3%";
        desc=(tot_pag*3)/100;
        cout<<"el resultado es "<<(tot_pag,desc);
        }
        else{ 
            cout<<"el total a pagar es de "<<tot_pag;

            system ("pause");
             }
 }
 
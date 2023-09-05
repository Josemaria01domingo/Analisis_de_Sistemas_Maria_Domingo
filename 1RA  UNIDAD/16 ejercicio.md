# DESCRIPCION DEL PROBLEMA
Los clientes de un hospital tienen un credencial en la que ademas de otra informacion registra otra categoria que depende de los ingresos economicos del nucleo familiar del paciente. Teniendo en cuenta la categoria del hospital les hace un descuento cuando tienen que pagar su cuenta con base de la siguiente tabla.

# SOLUCION DEL PROBLEMA
#include <iostream>
#include <stdlib.h>
#include <stdio.h>

using namespace std;
int main(){ 
    float des,tot_pag;

    cout<<"ingrese el total a pagar";
    cin>>tot_pag;
    cout<<"selecciono una categoria "<<endl;
    cout<<"categoria #1--------35%"<<endl;
    cout<<"categoria #2--------22%"<<endl;
    cout<<"categoria #3--------15%"<<endl;
    cout<<"categoria #4--------5%"<<endl;
    cin>>cat;

    switch (cat){ 

        case 1:
        cout<<"usted selecciono la categoria #1"<<endl;
        tot_pag=des*35;
        des=tot_pag*35;
        cout<<"sus categoria es "<<cat;
        cout<<"su nuevo descuento es de "<<35;
        break;

         case 2:
        cout<<"usted selecciono la categoria #1"<<endl;
        tot_pag=des*22;
        des=tot_pag*22;
        cout<<"sus categoria es "<<cat;
        cout<<"su nuevo descuento es de "<<22;
        break;

        case 3:
        cout<<"usted selecciono la categoria #1"<<endl;
        tot_pag=des*15;
        des=tot_pag*15;
        cout<<"su categoria es "<<cat;
        cout<<"su nuevo descuento es de "<<15;
        break;

        case 4:
        cout<<"usted selecciono la categoria #1"<<endl;
        tot_pag=des*5;
        des=tot_pag*5;
        cout<<"su categoria es "<<cat;
        cout<<"su nuevo descuento es de "<<5
        break;

         default;
         cout<<"ingrese una categoria correcta";
          }

          system ("pause");
 }           






















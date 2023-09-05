# DESCRIPCION DEL PROBLEMA 
En un hospital se ha hecho un estudio sobre los pacientes registrados durante los ultimos 10 aNos, con el objetivo de hacer una aproximacion de los costos de internacion por paciente. Se obtuvo un costo promedio diario segun el tipo de enfermedad que aqueja al paciente. Ademas se pudu determinar que un promedio de todos los pacientes con edad de 14 y 22 aNos implica un costo adicional del 10% la siguiente tabla expresa los costos diarios segun el tipo de enfermedad.

# SOLUCION DEL PROBLEMA
#include <iostream>
#include <stdlib.h>
#include <stdio.h>

using namespace std;
int main(){ 
    float tipo_enfer,cos_diario,av,edad_1,edad_2,tot_pag,dias;

    cout<<"seleccione el costo tipo de enfermedad "<<endl;
    cin>>tipo_enfer;
    cout<<"--------#1--------Q250"<<endl;
    cout<<"--------#2--------Q300"<<endl;
    cout<<"--------#3--------Q125"<<endl;
    cout<<"--------#4--------Q100"<<endl;
    cin>>tipo_enfer;
    cout<<"ingrese la primera edad";
    cin>>edad_1;
    cout<<"ingrese la segunda edad";
    cin>>edad_2;

    switch (tot_pag){

        case 1:
        cout<<"ussted selecciono tipo_enfer #1"<<endl;
        cos_diario=(tot_pag*250)/500;
        tipo-enfer=cos_diario/dias;
        cout<<"el tipo de enfermedad es "<<tipo_enfer;
        cout<<"el total a pagar es de "<<250;
        break;

       case 2:
        cout<<"ussted selecciono tipo_enfer #1"<<endl;
        cos_diario=(tot_pag*300)/500;
        tipo-enfer=cos_diario/dias;
        cout<<"el tipo de enfermedad es "<<tipo_enfer;
        cout<<"el total a pagar es de "<<300;
        break;

        case 3:
        cout<<"ussted selecciono tipo_enfer #1"<<endl;
        cos_diario=(tot_pag*125)/500;
        tipo-enfer=cos_diario/dias;
        cout<<"el tipo de enfermedad es "<<tipo_enfer;
        cout<<"el total a pagar es de "<<125;
        break;

        case 4:
        cout<<"ussted selecciono tipo_enfer #1"<<endl;
        cos_diario=(tot_pag*100)/500;
        tipo-enfer=cos_diario/dias;
        cout<<"el tipo de enfermedad es "<<tipo_enfer;
        cout<<"el total a pagar es de "<<100;
        break; 

        deault;
        cout<<"ingrese el tipo de enfermedad "<<topo_enfer;
         }
         system ("pause");
 }         





















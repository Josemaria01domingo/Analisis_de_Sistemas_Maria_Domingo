# DESCRIPCIÓN DEL PROBLEMA

Realice un programa tal que dado como dato la cantidad de minutos.

# SOLUCIÓN DEL PROBLREMA
#include iostream
#include stdlib.h
#include stdio.h

using namespace std; 
int main (){
    float tot_pag,min;
    char cod;

    cout <<"A------Guatemala------Q3.12"<<endl;
    Cout <<"B------Italia---------Q5"<<endl;
    cout <<"C------Mexico---------Q2.75"<<endl; 
    Cout <<"D------Costa Rica-----Q4.75"<<endl;

    cout<<"ingrese la cantidad de minutos que hablo";
    cin>>min;
    cout<<"ingrese el codigo del area a llamar";
    switch (cod){

        case "A":
        cout<<"selecciono Guatemala" <<endl;
        tot_pag = min*3.12;
        cout<<"total a pagar es de: "<<tot_pag;
        break;
        cout<<"ingrese la cantidad de minutos que hablo";
        cin>>min;
        cout<<"ingrese el codigo del area a llamar;

        case "B":
        cout<<"selecciono Italia "endl;
        tot_pag=min*5;
        cout<<"total a pagar es de: "<<tot_pag;
        break;
        cout<<"ingrese la cantidad de minutos que hablo";
        cin>>min;
        cout<<"ingrese el codigo del area a llamar;
        cin>>cod;

        case "c":
        cout<<"selecciono Mexico "endl;
        tot_pag=min*2.10;
        cout<<"total aa pagar es de: "<<tot_pag;
        break;
        cout<<"ingrese la cantidad que hablo";
        cin>>min;
        cout<<"ingrese el codigo del area a llamar;
        cin>>cod;

        case "D":
        cout<<"selecciono Costa Rica "<<endl;
        tot_pag=min*4.75;
        cout<<"total aw pagar es de: <<tot_pag;
        break;

        defaul:
        cout<<"ingrese un codigo correto";
        system ("pause");
      }
}







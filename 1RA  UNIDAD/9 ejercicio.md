# DESCRIPCION DEL PROBLEMA 
Realiza un programa que permita ser la conversion de grados centigrados a grados farenheit tomando en cuenta la siguiente formula. F=(9/5)*c+32

# SOLUCION DEL PROBLEMA 
#include <iostream>
#include <stdlib.h>
#include <stdio.h>

using namespace std;
int main(){ 
    int c,conv;

    cout<<"ingrese los grados centigrados";
    cin>>c;

    conv=((c*9/5))+32;
    cout<<"los grados centigrados son de: "<<conv<<endl;

    system ("pause");
 }
 
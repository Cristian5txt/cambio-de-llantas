#include <iostream>
using namespace std;

int main() {

    int gata=1;
    int llave_inglesa=1;
    int llanta=1;
    int correcto=0;

    cout<< "BAJAMOS A VERIFICAR QUE LLANTA ES LA BAJA"<<endl;

    if (llanta==1 && gata==1 && llave_inglesa==1){
        cout<< "PROCEDEMOS A CAMBIAR LA LLANTA"<<endl;
        cout<< "COLOCAMOS LA GATA"<<endl;
        cout<< "DESTORNILLAMOS LOS TORNILLOS"<<endl;
        cout<< "SACAMOS LA LLANTA1"<<endl;
        cout<< "COLOCAMOS LA LLANTA2"<<endl;
        cout<< "AJUSTAMOS LOS TORNILLOOS"<<endl;
        cout<< "SACAMOS LA GATA"<<endl;
        cout<<"VERIFICAMOS"<<endl;
        correcto++;
        if(correcto==1){
            cout<<"ARRANCAMOS EL CARRO Y NOS VAMOS";
        }
        else
            cout<<"LLAMAMOS A LA GRUA"<<endl;
       }
    else
        cout<< "FALTAN HERRAMIENTAS"<<endl;
    return 0;
}

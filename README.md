/*sopa
Programa que lee una variable y determina su tamaño*/
#include <iostream>
using namespace std;
int main()
{
	cout << "\n\tTAMA\xA5O DE VARIABLES\n\n";
	char caracter;
	char cadena[10];
	short int entero_corto;
	int entero;
	long int entero_largo;
	long long int entero_muy_largo;
	float real;
	double doble;
	cout << "Caracter: \t\t" << sizeof(caracter) << endl;
	cout << "Cadena de 10: \t\t" << sizeof(cadena) << endl;
	cout << "Entero Corto:\t\t" << sizeof(entero_corto) << endl;
	cout << "Entero: \t\t" << sizeof(entero) << endl;
	cout << "Entero Largo:\t\t" << sizeof(entero_largo) << endl;
	cout << "Entero Muy Largo:\t" << sizeof(entero_muy_largo) << endl;
	cout << "Float:  \t\t" << sizeof(real) << endl;
	cout << "Doble:  \t\t" << sizeof(doble) << endl;
	cout << endl;
	system("pause");
	return 0;
}

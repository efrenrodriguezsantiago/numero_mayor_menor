//dado un numero cualquiera, mostrar un mensaje que nos diga si es positivo o negativo

#include<iostream>
using namespace std;
int main()
{
	int numero;
	cout<<"\ningrese el numero:";cin>>numero;
	
	if(numero > 0)
	{
		cout<<"\nel numero es positivo:";
	}
	
	else{
		cout<<"\nel numero es negativo:";
	}
	
	
	return 0;
}

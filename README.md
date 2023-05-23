#include <bits/stdc++.h>
using namespace std;

bool EsMultiplo(int x);
int main(){
	
	int x;
	
	cout<<"Ingrese un numero: ";
	cin>>x;
	
		if(EsMultiplo(x) == true){
			
			cout<<"Es multiplo";
		}
		else{
			
			cout<<"No es multiplo";
		}
	
	return 0;
}

bool EsMultiplo(int x){
	
	bool Multiplo = false;
	
		if(x % 3 == 0){
			
			Multiplo = true;
		}
	
	return Multiplo;
}

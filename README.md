#include <iostream>
using namespace std;

int somma (int m, int n){
	
	int cont, som;
	
	if (m==0 || n==0){
		cout<<"0";
		exit(0);
	}
	
	if(n==0){
		return somma;
	}
	else {
	return n + somma(m, n-1);
	}
	
}

int main(){
	int a, b, cont;
	
	cout<<"inserisci il numero ";
	cin>>a;
	cout<<"\n"<<"inserici il numero ";
	cin>>b;
	
	cout<<somma(a, b);
	
	return 0;
}

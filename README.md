# Funcation-using-Templats-in-c-
//using funcation templats
#include<iostream>
using namespace std;
template <class T>
T number(T a,T b){
	if(a>b){
		return a;
	}
	else
	return b;
}
int main(){
	int n;
	float b;

	n=number(100,50);
		cout<<n;
	b=number(1.3,2.5);
	cout<<b;
	return 0;
}


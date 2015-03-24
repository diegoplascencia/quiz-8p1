#include <iostream>
#include <math.h>
using namespace std;
int function(int a, int b){
	int x=a, y=b,res;
	do{
		res=result(x,y);
		if(res<0)
			{res=res*-1;}
		x=y;
		y=res;
	}while(res!=0);
	return x;
}

int gcd(int a, int b){
	if (a==b){
		return a;
	}
	else{
		if(a>b){
			return gcd(a-b,b);
		}
		else{
			return gcd(a,b-a);
		}
	}
}
int main(){
	float x,y;
	cout<< "GIVE ME THE BIGGER NUMBER: "<<endl;
	cin>> x;
	cout<< "GIVE ME THE SMALLER NUMBER: "<<endl;
	cin>> y;
	cout<<" THE GCD OF THE TWO NUMBERS ARE"<< function(x,y)<<endl;
return 0;
}

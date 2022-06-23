#include<iostream>
using namespace std;
int main(){
	
	int n, mat, matm = 0;
	double nota, notam = 0.0;
	
	cin>>n;
	
	for(int i=0; i<n; i++){
		cin>>mat>>nota;	
		if(nota>=8.00 && nota>notam){
			matm = mat;	
			notam = nota;		
		}
	}
	
	if(notam == 0.0){
		cout<<"Minimum note not reached"<<endl;
	}
	else{
		cout<<matm<<endl;
	}
	
	return 0;
		
}

#include <iostream>
using namespace std;
int ktra_snt(int a){
	if(a<=2) return 0;
	for(int i=2;i<a;i++)
	    if (a%i==0)
	        return 0;
	    return 1;
}
int main(){
	int a,n;
	cout<<"Nhap so n: ";cin>>n;
	if(n<=2){
		cout<<"khong co so nguyen to"<<endl;
	} else {
	
	for(a>2;a<=n;a++)
	   if(ktra_snt(a)==1){
	   cout<<a<<";";	
	    }
	}
}

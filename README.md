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


#include <iostream>
using namespace std;
void nhapmang(int a[],int n){
	for (int i=0;i<n;i++)
	{
		cout<<"a["<<i<<"]=";cin>>a[i];
	}
}
void inmang(int a[],int n)
{
	for(int i=0;i<=n;i++)
	cout<<a[i]<<";";
}

int main(){
	int a[100],i,n;
	cout<<"Nhap so phan tu n= ";cin>>n;
	nhapmang(a,n);
	cout<<"\n Mang vua nhap la:\n";
	inmang(a,n);
	for (int i=0;i<n;i++)
	if(a[i]%3==0){
		cout<<"\n phan tu chia het cho 3: "<<a[i]<<";"<<endl;
	}
}

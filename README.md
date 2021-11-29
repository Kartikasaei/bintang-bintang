/* =============================================
program ini dibuat pada tanggal 29 November 2021
"Barisan bintang-bintang"
===============================================*/

#include <iostream>
using namespace std;
int main(){

int i,j;
//deklarasikan variabel yang ingin digunakan

for(i=1;i<=10;i++){
	//looping pertama untuk membuat bintang tanpa spasi

for(j=1;j<=10;j++){
	//looping kedua untuk membuat bintang dengan spasi

if(i==1) if(((j>=1)&&(j<=10))) cout<<"*"; else cout<<" ";

else if(i==2) if(((j>=1)&&(j<=10))) cout<<" *"; else cout<<" ";
//percabangan else untuk menentukan jarak spasi

else if(i==3) if(((j>=1)&&(j<=10))) cout<<"  *"; else cout<<" ";

else if(i==4) if(((j>=1)&&(j<=10))) cout<<"   *"; else cout<<" ";

else if(i==5) if(((j>=1)&&(j<=10))) cout<<"    *"; else cout<<" ";

else if(i==6) if(((j>=1)&&(j<=10))) cout<<"     *"; else cout<<" ";

else if(i==7) if(((j>=1)&&(j<=10))) cout<<"      *"; else cout<<" ";

else if(i==8) if(((j>=1)&&(j<=10))) cout<<"       *"; else cout<<" ";

else if(i==9) if(((j>=1)&&(j<=10))) cout<<"        *"; else cout<<" ";

else if(i==10) if(((j>=1)&&(j<=10))) cout<<"         *"; else cout<<" ";

}

cout<<"\n";

}

return 0;

}



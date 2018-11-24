# Latihan01

"Program Kalkulator 2 Bilangan"

 Deklarasi :
 1. Start program.
 2. Inputkan bilangan a dan b.
 3. Masukkan kode program operasi ;
 
    (1) untuk penjumlahan
    
    (2) untuk pegurangan
    
    (3) untuk perkalian
    
    (4) untuk pembagian
    
    Jika input 1 maka hitung hasil=a+b dan cetak hasil.
    
    Jika input 2 maka hitung hasil=a-b dan cetak hasil.
    
    Jika input 3 maka hitung hasil=a*b dan cetak hasil.
    
    Jika input 4 maka hitung hasil=a/b dan cetak hasil.
    
4. Program end.

# Program C++

#include <iostream>

using namespace std;

main()

{
   int x,y,hasil;
   
   cout<<"PROGRAM KALKULATOR"<<endl<<endl;
   
   cout<<"Daftar Program Operator:"<<endl;
   
   string jumlah ="(1) penjumlahan (+)";
   
   cout<<jumlah<<endl;
   
   string pengurangan ="(2) pengurangan (-)";
   
   cout<<pengurangan<<endl;
   
   string perkalian ="(3) perkalian   (*)";
   
   cout<<perkalian<<endl;
   
   string pembagian ="(4) pembagian   (/)";
   
   cout<<pembagian<<endl<<endl;

   cout<<"Masukan angka A=";
   
   cin>>x;
   
   cout<<"Masukan angka B=";
   
   cin>>y;
   
   a:

   int z;
   
   cout<<"Masukan Kode Program Operation =";
   
   cin>>z;

   if(z==1)
   
   {
   
   hasil=x+y;
   
   cout<<"Hasil Dari :"<<jumlah<<" , "<<x<<" dan "<<y<<" = "<<hasil<<endl;
   
   }
   
   else if(z==2)
   
   {
   
   hasil=x-y;
   
   cout<<"Hasil Dari :"<<pengurangan<<" , "<<x<<" dan "<<y<<" = "<<hasil<<endl;
   
   }
   
   else if(z==3)
   
   {
   
   hasil=x*y;
   
   cout<<"Hasil Dari :"<<perkalian<<" , "<<x<<" dan "<<y<<" = "<<hasil<<endl;
   
   }
   
   else if(z==4)
   
   {
   
   hasil=x/y;
   
   cout<<"Hasil Dari :"<<pembagian<<" , "<<x<<" dan "<<y<<" = "<<hasil<<endl;
   
   }
   
   else
   
   {
   
   cout<<"Operation Aritmatika Salah"<<endl<<endl;

   goto a;
   
   }
   
     return 0;
     
}

# Foto hasil
![img](https://github.com/arifhanifanudin/praktikum06/blob/master/latihan01/hasil01.PNG)

![img]()

![img]()


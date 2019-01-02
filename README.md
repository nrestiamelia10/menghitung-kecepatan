#include <iostream>

using namespace std;

int main()
{
    int Vo,a,t,Vt,St;
    cout<< "Progam menghitung kecepatan"<<endl;
    cout<< "---------------------------"<< endl;
    cout<< "Masukkan kecepatan awal";
    cin>> Vo;
    cout<< "Masukkan waktu =";
    cin>> t;
    Vt= Vo+a+t;
    St= Vo+t+1/2*a*t;
    cout<< "----------------------------"<<endl;
    cout<< " Kecepatan ="<< Vt<< endl;
    cout<< "Jarak Tempuh ="<< St<< endl;
    return 0;
}

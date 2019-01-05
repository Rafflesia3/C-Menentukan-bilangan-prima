# C-Menentukan-bilangan-prima

    #include <iostream>
    #include <conio.h>
    using namespace std;
    int main()
    {
    int bil,jum,i;

    cout << "\t\t Pelita Bangsa \n\n" << endl;
    cout << "=========================================\n" << endl;
    cout << "Nama    : Rafi Alwan Setyawan \nNIM     : 311810325 \nKelas   : TI.18.D7 \n" << endl;
    cout << "=========================================\n" << endl;

    cout<< "\t     Menentukan bilangan prima\n" << endl;

    cout<<"MASUKKAN BILANGAN BULAT POSITIF = ";
    cin>>bil;
    jum = 0;
    for (i=1;i<=bil;i++)
    if (bil%i==0)
    jum++;
    if (jum==2)
        cout<<"BILANGAN TERSEBUT ADALAH BILANGAN PRIMA\n";
    else
        cout<<"BUKAN BILANGAN PRIMA\n";
    return 0;
    }
    
Hasil
![img](https://github.com/Rafflesia3/C-Menentukan-bilangan-prima/blob/master/C++%20Menentukan%20bilangan%20prima.png?raw=true)

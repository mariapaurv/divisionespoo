# divisionespoo

#include <iostream>
using namespace std;
int main()
{
    /*Escriba un programa que solicite dos numeros enteros
    a.calcule la division entera.
    b. calcule la division real.*/

float a,b;
int r=0;
float r2=0.0;
cin >> a;
cin >> b;
r = a/b;
r2 = a/b;
cin >> a >> b;
cout << "entera: " << r << endl;
cout<< "real: " << r2 << endl;
return 0;
}


#include <iostream>
#include <iomanip>
using namespace std;
int main()
{
    int n=1, l=6;
    for (int i = 1; i <= 10; i++) {
        if (i == 1) {
                for (int j=1;j<=10;j++){
            cout << " *" << endl;
        }}
        else if {{
                for(int k=2;k<=9;k++){
            cout << setw (n) << " *" << setw(l) << " *" << setw(n)<<endl;
            n++;
            l--;
        }
        }
        else
           {
            cout <<"hh"<< setw (5) << "*" << setw (5);
        }
    }

    return 0;
}

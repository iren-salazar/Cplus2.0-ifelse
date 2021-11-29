# Cplus2.0-if_else

contents: determining what letter is greater.

// Iren Mercado Salazar 
// 01-CIT-04
#include <iostream>
using namespace std;

int main()
{
    int iren;
    int a, b, c;
    
    cout << "Please enter the first number= ";
    cin >> a;
    cout << "Please enter the second number= ";
    cin >> b;
    cout << "Please enter the third number= ";
    cin >> c;
    
    if (a>b)
    {
        if (a>c)
          cout << " a is greater " << endl;
        else
          cout << " c is greater " << endl;
    }      
    else 
    {
        if (b>c)      
         cout << " b is greater " << endl;
        else
         cout << " c is greater " << endl;
    }   
    return 0;
}
  /*output:
  
  Please enter the second number= 45
  Please enter the second number= 89
  Please enter the second number= 67
  b is greater 
  */

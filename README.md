# the-fist-one-
#include <iostream>
using namespace std;
int main()
{
    int a;
    cout << "ok, here is ur exam! let's get it started!";
    cout << "\n5+6=?";
    cin >> a;
    if (a != 11)
    {
        cout << "\nexam failed" << endl;
    }
    else if (a == 11)
    {
        cout << "\nur right!";
        int b;
        cout << "\n70-14=?";
        cin >> b;
        if (b != 56)
        {
            cout << "\nexam failed!" << endl;
        }
        else if (b == 56)
        {
            cout << "\nit's right!";
            int c;
            cout << "\n76+24=?";
            cin >> c;
            if (c != 100)
            {
                cout << "\nexam failed" << endl;
            }
            else if (c == 100)
            {
                cout << "\nexam completed!";
            }
        }
    }
}

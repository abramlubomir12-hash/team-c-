#include <iostream>
#include <Windows.h>
#include <random>
using namespace std;
int main()
{   SetConsoleCP(1251);
    SetConsoleOutputCP(1251);
    srand(time(NULL));
    int RandomNumber;
    cout << "гра вгадай число" << endl;
    RandomNumber = rand() % 20;
    cout << "Випадкове число - " << RandomNumber << endl;
    return 0;
}

#include <iostream>
using namespace std;

class Animal {
public:
    void sound() {
        cout << "Animals make different sounds." << endl;
    }
};
class Dog : public Animal {
public:
    void sound() {
        cout << "Dog barks." << endl;
    }
};
int main() {
    Animal a;   
    Dog d;     

    cout << "Base class function call:" << endl;
    a.sound();
    cout << "\nDerived class function call:" << endl;
    d.sound(); 
    cout << "\nUsing base class pointer:" << endl;
    Animal *ptr;
    ptr = &d;
    ptr->sound(); 
    return 0;
}

#include <iostream>
using namespace std;

// Base class
class Animal {
public:
    virtual void sound() {
        cout << "Animals make different sounds." << endl;
    }
};
class Dog : public Animal {
public:
    void sound() {
        cout << "Dog barks." << endl;
    }
};
class Cat : public Animal {
public:
    void sound() {
        cout << "Cat meows." << endl;
    }
};
int main() {
    Animal *ptr;  
    Dog d;
    Cat c;

    ptr = &d;
    ptr->sound();   
    ptr = &c;
    ptr->sound();   
    return 0;
}

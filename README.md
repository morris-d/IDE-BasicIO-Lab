#include <iostream>
#include <iostream>
#include <string>

using namespace std;

int main () {

string name;
int currentYear = 2025;

cout << "Enter your full Name: ";
getline(cin, name);

int age;

cout << "Enter your age: ";
cin >> age;

int yearTurning60 = currentYear + (60 - age);

cout << "Hello " << name << ", you are " << age << " years old! " << endl;

cout << "You will turn 60 years old in the year " << yearTurning60 << "." << endl;


return 0;
}

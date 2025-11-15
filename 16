#include <iostream>
using namespace std;

class PersonalInfo {
protected:
    string name;
    int age;
public:
    void readPersonalInfo() {
        cout << "Enter Name: ";
        cin >> name;
        cout << "Enter Age: ";
        cin >> age;
    }
    void displayPersonalInfo() {
        cout << "Name: " << name << endl;
        cout << "Age: " << age << endl;
    }
};
class JobInfo {
protected:
    int empID;
    string designation;
public:
    void readJobInfo() {
        cout << "Enter Employee ID: ";
        cin >> empID;
        cout << "Enter Designation: ";
        cin >> designation;
    }
    void displayJobInfo() {
        cout << "Employee ID: " << empID << endl;
        cout << "Designation: " << designation << endl;
    }
};
class Employee : public PersonalInfo, public JobInfo {
protected:
    float salary;
public:
    void readEmployeeInfo() {
        readPersonalInfo();
        readJobInfo();
        cout << "Enter Salary: ";
        cin >> salary;
    }
    void displayEmployeeInfo() {
        displayPersonalInfo();
        displayJobInfo();
        cout << "Salary: " << salary << endl;
    }
};
class FullTimeEmployee : public Employee {
private:
    int workingHours;
public:
    void readFullTimeEmployeeInfo() {
        readEmployeeInfo();
        cout << "Enter Working Hours per week: ";
        cin >> workingHours;
    }
    void displayFullTimeEmployeeInfo() {
        cout << "\n--- Employee Details ---" << endl;
        displayEmployeeInfo();
        cout << "Working Hours per week: " << workingHours << endl;
    }
};
int main() {
    FullTimeEmployee e;

    cout << "Enter Employee Details:" << endl;
    e.readFullTimeEmployeeInfo();
    e.displayFullTimeEmployeeInfo();
    return 0;
}

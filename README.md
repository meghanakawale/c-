#include <iostream>
using namespace std;

class Emp{
    
    public: string name;
    public: int age;
    public: int salary;
    public: void getdata();
};
void Emp::getdata()
{
    cout<<"Enter name of the employee :";
     cin>>name;
    cout<<"Enter age of the employee :";
    cin>>age;
    cout<<"Enter salary :";
    cin>>salary;
}
int main()
{
    Student s1;
    s1.getdata();
}


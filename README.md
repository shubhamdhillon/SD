# SD
This is a C++ program of Class.

#include<iostream>
//#include<stdio>
using namespace std;
class Employee 
{
int id;
char name[20];
int balance;
public:
void accept()
{
cout<<"Enter the Employee id,name and balance: ";
cin>>id>>name>>balance;
}
void display()
{
cout<<"Employee id: "<<id<<endl;
cout<<"Employee name: "<<name<<endl;
cout<<"Employee balance: "<<balance<<endl;
}
};
int main()
{
Employee obj;
obj.accept();
obj.display();
//getch();
return 0;
}



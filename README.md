# SD
This is a C++ program of Class.

#include<iostream.h>
#include<stdio.h>
class Employee 
{
int id;
char name;
int balance;
public:
void accept()
{
cout<<"Enter the Employee id,name and balance"<<endl;
cin>>id>>name>>balance;
}
void display()
{
cout<<"Employee id"<<id<<endl;
cout<<"Employee name"<<name<<endl;
cout<<"Employee balance"<<balance<<endl;
}
};
int main()
{
Employee obj;
obj.accept();
obj.display();
getch();
return 0;
}



# SD
This is a Class program in C++ language 

// C++ program 

#include <iostream>
#include <string.h>
#include <algorithm>
using namespace std;

class MyClass {       
  public:             
    int myNum;        
    string myString;  
};
  
int main() {
  MyClass myObj; 
  int date;
  cin>>date;
  myObj.myNum =date; 
  cout << myObj.myNum << "\n";
  cout <<"Shubham's birthday is on"<< myObj.myNum<<"October";
  return 0;
}

//Output of the above program will be :  17
                                         Shubham's birthday is on 17th October

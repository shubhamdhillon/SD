# SD
This is a Class program in C++ language 

// C++ program 

#include <iostream.h>
#include <string.h>
using namespace std;
class MyClass {       
  public:             
    int myNum;        
    string myString;  
};
  
int main() {
  MyClass myObj; 

  myObj.myNum = 17; 
  myObj.myString = "Shubham's birthday is on 17th October";
  cout << myObj.myNum << "\n";
  cout << myObj.myString;
  return 0;
}

//Output of the above program will be :  17
                                         Shubham's birthday is on 17th October

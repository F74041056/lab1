// lab1.cpp
#include <iostream>
using namespace std;
int main()
{
 int n;
 cout << "Please enter a number: ";
 cin >> n;
 do
 {
  if(n==1)
   {
    cout << n << " ";
    break;
   }
   else if(n%2!=0)
         {
          cout << n << " ";
          n = n*3+1;
         }
         else
         {
          cout << n << " ";
          n = n/2;
         }
  }
}

// README
// Showing how to compile my program for question B
g++ -o lab1_1 lab1.cpp
./lab1_1

# Ex.No:1
# Ex.Name: Write a CPP Program to overload a function to perform sum of two integers and sum of three integers
## Date: 14/08/2025
## Aim: 
To write a C++ program that overloads a function to perform the sum of two integers and the sum of three integers.

## Algorithm:
1. Start the program.
2. Define a class Addition with two overloaded functions named sum:
3. One function takes two integer arguments and returns their sum.
4. Another function takes three integer arguments and returns their sum.
5. In the main() function, create an object of the class.
6. Call both overloaded functions to compute the sum of two and three integers.
7. Display the results.
8. End the program.

## Program:
```cpp
#include<iostream>
using namespace std;
class fun{
    public:
    void add(int a,int b){
        cout<<"Sum of two Numbers="<<a+b<<endl;
    }
    void add(int a,int b,int c){
        cout<<"Sum of three Numbers="<<a+b+c;
    }
};
int main()
{
    int a,b,c;
    cin>>a>>b;
    fun f;
    f.add(a,b);
    cin>>a>>b>>c;
    f.add(a,b,c);
}
```



## Output:
<img width="553" height="255" alt="image" src="https://github.com/user-attachments/assets/0e20f780-6729-4655-9a2d-f1129790b11d" />



## Result:
The program successfully demonstrates function overloading by computing the sum of two integers and the sum of three integers using the same function name.

# Ex.No:4
# Ex.Name: Write a program in C++ to convert temperature in  Celsius to Fahrenheit using class methods(define member as private & define methods within class)
## Date: 14/08/2025
## Aim:
To write a C++ program to convert temperature from Celsius to Fahrenheit using class methods, keeping data members private and defining methods within the class.

## Algorithm:
1. Start the program.
2. Define a class Temperature with:
3. A private data member celsius to store the temperature in Celsius.
4. A member function input() to read the Celsius temperature.
5. A member function convert() to calculate and display the Fahrenheit equivalent using the formula:

𝐹=(𝐶×95)+32

6. In main(), create an object of Temperature.
7. Call input() to take Celsius value and convert() to display Fahrenheit value.
8. End the program.




## Program:
```cpp
#include <iostream>
using namespace std ;
class coversion
{
    private:
    int a;
    public:
    void dis()
    {
        cin>>a;
        cout<<"The temperature in Celsius:"<<a<<endl;
        cout<<"The temperature in Fahrenheit:"<<(float(a)*9/5)+32;
    }
};
int main()
{
    coversion v;
    v.dis();
}
```


## Output:
<img width="601" height="275" alt="image" src="https://github.com/user-attachments/assets/43c1c05b-64bf-49ae-8236-ee69fce6f6cd" />



## Result:
The program successfully converts temperature from Celsius to Fahrenheit using class methods, with the data member defined as private and methods defined within the class.

# Ex.No:3
# Ex.Name: Write A CPP Program to create class  Square and calculate the volume of the Square, make use of static member variable in the class Square.(Note: l=b=h)
## Date: 14/08/2025
## Aim:
To write a C++ program to create a class Square and calculate the volume of the square (cube), making use of a static member variable to count the number of objects created.

## Algorithm:
1. Start the program.
2. Define a class Square with:
3. A data member side for storing the length of the square’s side.
4. A static member variable count to keep track of how many objects are created.
5. A constructor to initialize the side and increment the count.
6. A member function volume() to calculate and return the volume of the cube (since l = b = h).
7. A static function getCount() to display the number of objects created.
8. In main(), create multiple Square objects with different side values.
9. Display the volume of each object.
10. Display the total number of objects created using the static function.
11. End the program.

## Program:
```cpp
#include <iostream>
using namespace std;
class Square {
    public:
        static int count;
      // Constructor definition
      Square(double l,double b,double h) 
      {
          length=l;
          breadth=b;
          height=h;
          count++;
          cout<<"Constructor called."<<endl;
          cout<<"Volume :"<<Volume()<<endl;
      }
      double Volume() 
      {
          return height*length*breadth;
      }
      
   private:
      double length;     // Length of a box
      double breadth;    // Breadth of a box
      double height;     // Height of a box
};
int Square::count=0;
int main(void) 
{
  int a,b,c,d,e,f;
  cin>>a>>b>>c>>d>>e>>f;
  Square s1(a,b,c),s2(d,e,f);
  cout<<"Total objects: "<<Square::count;
   return 0;
}
```


## Output:
<img width="460" height="320" alt="image" src="https://github.com/user-attachments/assets/1eb78577-79c5-4598-98a0-881c24b47697" />



## Result:
The program successfully creates a Square class, calculates the volume of each cube using the side length, and uses a static member variable to count the number of objects created.

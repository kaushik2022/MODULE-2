# Ex.No:5
# Ex.Name: Write A CPP Program to allocate memory dynamically for an integer variable. (Note: p_var = new typename;)
## Date: 14/08/2025
## Aim:
To write a C++ program to allocate memory dynamically for an integer variable using the new operator.

## Algorithm:
1. Start the program.
2. Declare a pointer variable of type int.
3. Allocate memory dynamically for the integer using p_var = new int;.
4. Accept a value from the user and store it in the dynamically allocated memory.
5. Display the stored value.
6. Release the memory using the delete operator.
7. End the program.

## Program:
```cpp
#include <iostream>
using namespace std ; 
class var_space
{
    public:
    int *p_var;
  void allocateSpace()
  {
      p_var=new int;
      cin>>*p_var;
      cout<<"Integer Value is : "<<*p_var;
  }
};
int main()
{
    var_space v;
    v.allocateSpace();
}
```



## Output:

<img width="474" height="200" alt="image" src="https://github.com/user-attachments/assets/44efc019-7cea-42b0-94b8-52ddf3d81548" />



##Result:
The program successfully allocates memory dynamically for an integer variable using the new operator, stores a value, displays it, and then frees the memory using delete.

# CLASS SCOPE AND ACCESSING CLASS  MEMBERS & REFERENCE VARIABLES
## PROGRAM STATEMENT :

To write a program in C++ to calculate the volume of a cube(declare side as private member ) using class methods.

## ALGORITHM :

1.	Start the program.
2.	Define a Cube class with private side variable and public methods to set the side length and calculate the volume.
3.	In main, read the side length, create a Cube object, set the side, calculate the volume, and print it.
4.	End the program.

## PROGRAM :

#include <iostream> using namespace std; class Cube{
private:
int side;

public:
void setmember(int s)
{
side=s;
}
int calculate()
{
return side*side*side;
}
};
int main()
{
int sidee; cin>>sidee; Cube cube;
cube.setmember(sidee); int three=cube.calculate();
cout<<"The Volume of Cube is:"<<three;
 
}

## OUTPUT :
![image](https://github.com/user-attachments/assets/fed49b21-a7d1-480b-ae13-c45c1e9de34e)

## RESULT :
Thus, the C++ Program to calculate the volume of a cube(declare side as private member ) using class methods created successfully.
 

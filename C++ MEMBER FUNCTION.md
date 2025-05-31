# C++ MEMBER FUNCTION

## PROGRAM STATEMENT :
To write a C++ program to convert Celsius into Fahrenheit using inline function

## ALGORITHM :

1.	Start the program.
2.	Define an inline function convertToFahrenheit that takes a float celsius as input and returns the Fahrenheit equivalent using the formula (celsius * 9.0 / 5.0) + 32.
3.	In the main function, declare a float variable celsius to store the temperature.
4.	Read the Celsius temperature from the user and store it in celsius.
5.	Call the convertToFahrenheit function with celsius as the argument and store the result in the fahrenheit variable.
6.	Print the converted temperature in Fahrenheit.
7.	End the program.

## PROGRAM :
```
#include <iostream> using namespace std;

// Inline function to convert Celsius to Fahrenheit inline float convertToFahrenheit(float celsius) {
return (celsius * 9.0 / 5.0) + 32;
}

int main() { float celsius;

// Get the Celsius temperature from the user
//cout << "Enter temperature in Celsius: "; cin >> celsius;

// Convert the temperature to Fahrenheit
float fahrenheit = convertToFahrenheit(celsius);
// Display the result
cout << "temperature in Fahrenheit:" << fahrenheit << endl;
 return 0 
}
```
## OUTPUT :
![image](https://github.com/user-attachments/assets/ff554026-e287-437d-bc02-9a0526fd4385)

## RESULT :
Thus, the C++ program to convert Celsius into Fahrenheit using inline function is implemented successfully.


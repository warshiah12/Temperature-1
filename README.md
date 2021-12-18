# Temperature-1
#fahrenheit to celsius conversion (simple code)
#include<iostream>
using namespace std;
int main()
{
	double fahren;  //declaring variable with datatype double
	double cels;    //declaring variable with datatype double
	cout << "Enter the temperature in Fahrenheit: " << endl;
	cin >> fahren;
	cels = (fahren - 32)* 5/9;  //formula to convert temperature from fahrenheit to celsius
	cout << fahren << " Fahrenheit is " << cels << " in Celsius." << endl;
	return 0;

}

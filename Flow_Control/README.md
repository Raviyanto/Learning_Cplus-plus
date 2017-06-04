![](https://github.com/Raviyanto/Learning_Cplus-plus/blob/master/Flow_Control/Flowchart-If-1.jpg)

```
/* Program to print positive number entered by the user
 * If user enters negative number, it is skipped
 */

#include <iostream>
using namespace std;

int main()
{
	int number;
	cout << "Enter an integer: ";
	cin >> number;

	// checks if the number is positive
	if (number > 0)
		{
			cout << "You entered a positive integer: " << number << endl;
		}

	cout << "This statement is always executed." << endl;
	return 0;
}

```
![](http://)

```
/* Program to check whether an integer is positive or negative
 * This program consider o as positive number
 */

#include <iostream>
using namespace std;

int main()
{
	int number;
	cout << "Enter an integer: ";
	cin >> number;

	if (number >= 0)
		{
			cout << "You entered a positive integer: " << number << endl;
		}
	else
		{
			cout << "You entered a negative integer: " << number << endl;
		}
	cout << "This line is always printed.";
	return 0;
}			


```
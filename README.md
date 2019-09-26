# howard-the-duck
Non-school related stuff
//I am currently trying to learn C++ so that I can pass a class in college on it. But also so I can learn how to code.
//Here is a program I wrote today that can calculate the required gallons of paint needed to paint the four walls and ceiling of a room
//Again this is in C++ only

#include <iostream>
using namespace std;
int main()
{

	int l, w, h;
	float A;
	cout << "Please enter width as an integer in feet:\t" << endl;
	cin >> w;
	cout << "\nNow please enter length as an integer in feet:\t" << endl;
	cin >> l;
	cout << "\nArea of ceiling = " << l * w << " feet squared"<<endl;
	cout << "Finally, please enter your height as an integer in feet:\t" << endl;
	cin >> h;
	cout << "\nArea of one side = " << l * h << " feet squared"<<endl;
	cout << "Area of another side = " << w * h <<" feet squared"<< endl;
	A = 2 * h * w + 2*h * l+l*w;
	cout << "Surface Area of 4 walls and ceiling = " << (2 * h * w) + (2*h*l)+l*w <<" feet squared\n"<< endl;
	cout << "Number in gallons of paint required to paint the room = " <<float (A/10) <<" gallons"<< endl;

	return 0;
}
//It works like a charm. That is if you know that the paint you bought can cover 10 square feet for every gallon that you buy

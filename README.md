# Exam-4
#include <iostream>
using namespace std;

//***************************************************
// You must write the getLength, getWidth, getArea, *
// and displayData functions.                       *
//***************************************************

double getLength (double& length) {
  cout << "Enter the rectangle’s length" << endl;
  cin >> length;
  return length;
}
double getWidth (double& width) {
cout << "enter the rectangle’s width" << endl;
cin >> width;
return width;
}
double getArea (double length, double width, double& area) {
  area = length * width;
  return area;
}
void displayData (double length, double width, double area) {
  cout << "-----Rectangle Data---------" << endl;
  cout << "Length : " << length << endl;
  cout << "Width : " << width << endl;
  cout << "Area : " << area << endl;

}
int main()
{
	double length,    // The rectangle's length
			   width,     // The rectangle's width
			   area;      // The rectangle's area

getLength(length);
getWidth (width);
getArea (length, width, area);
displayData (length, width, area); 
}

#include<iostream>
using namespace std;
int main()
{
	int count1 = 0;
	int count2 = 0;
	cout << "plz enter 10 integer number:" << endl;
	int num1; cin >> num1;
	int num2; cin >> num2;
	int num3; cin >> num3;
	int num4; cin >> num4;
	int num5; cin >> num5;
	int num6; cin >> num6;
	int num7; cin >> num7;
	int num8; cin >> num8;
	int num9; cin >> num9;
	int num10; cin >> num10;

	if (num1 % 2 == 0) count1++; 
	if (num2 % 2 == 0) count1++; 
	if (num3 % 2 == 0) count1++; 
	if (num4 % 2 == 0) count1++; 
	if (num5 % 2 == 0) count1++; 
	if (num6 % 2 == 0) count1++; 
	if (num7 % 2 == 0) count1++; 
	if (num8 % 2 == 0) count1++; 
	if (num9 % 2 == 0) count1++; 
	if (num10 % 2 == 0) count1++; 


	if (num1 % 2 != 0) count2++; 
	if (num2 % 2 != 0) count2++;
	if (num3 % 2 != 0) count2++; 
	if (num4 % 2 != 0) count2++; 
	if (num5 % 2 != 0) count2++; 
	if (num6 % 2 != 0) count2++; 
	if (num7 % 2 != 0) count2++; 
	if (num8 % 2 != 0) count2++; 
	if (num9 % 2 != 0) count2++; 
	if (num10 % 2 != 0) count2++; 

	cout << "the number of even numbers is :" << count1 << endl;
	cout << "the numbers of odd numbers is :" << count2 << endl;
	cout << "the count of both even and odd numbers is :" << count1 + count2 << endl;
	return 0;
}

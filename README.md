# C-




// ConsoleApplication1.cpp : Defines the entry point for the console application.
//

#include "stdafx.h"
#include <utility>
#include <iostream>
using namespace std;

/*
unsigned divide(unsigned a, unsigned b, unsigned n)
{
	unsigned result;
	n = a / b;
	result = b  % n;
	cout << result<<endl;
	return result;

}


/*
unsigned add(unsigned a, unsigned b, unsigned n)
{
	//finished
	unsigned result;

	unsigned k = -1;
	result = (a + b) + n * k;
	cout << result << endl;
	return result;

} */

/*
unsigned multiply(unsigned a, unsigned b, unsigned n)
{
	int result;
	int k;

	if (a*b <= 10)
		k = 0;
	else if (a*b <= 20)
		k = -1;
	else if (a*b <= 30)
		k = -2;
	else if (a*b <= 40)
		k = -3;
	else if (a*b <= 50)
		k = -4;
	else if (a*b <=60)
		k = -5;
	
	else
		k = -6;

	result = a * b + n * k;

	cout << result << endl;
	return result;
	//finished
}
*/
unsigned divide(unsigned a, unsigned b, unsigned n)
{
	unsigned result;
	for (int i = 0; i < 10; i++)
	{
		result = i *b;
		cout << i*b << endl;
	}
	if (result = a)
		cout<< "you have found the answer";
	else
		cout<< "d";

	//cout << result;
	return result;
}

int main()
{
	//divide(32, 12, 10);
	//add(9, 5, 10);
	//multiply(4, 3, 9);
	divide(1, 2, 3);
    return 0;
}































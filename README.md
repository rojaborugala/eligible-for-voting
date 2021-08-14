#include<iostream>
using namespace std;

int main()
{
	int age;

	cout<<"Enter your age: ";
	cin>>age;
	if(age>=13 && age<=19)
	{
		cout<<"you are Teenager"<<endl;
	}
	else
	{
		cout<<"you are not a Teenager"<<endl;
	}

    if(age>=18)
	{
		cout<<"you are eligible for voting"<<endl;
	}
	else
	{
		cout<<"you are not eligible for voting"<<endl;
	}

	return 0;
}


output:
  Enter your age: 6
you are not a Teenager
you are not eligible for voting

--------------------------------
Process exited after 5.187 seconds with return value 0
Press any key to continue . . .

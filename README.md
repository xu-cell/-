#include<iostream>
#include<string>
#include<cmath>
using namespace std;
int main() 
{
	string line, word;
	cin >> line >> word;
	if (line == word)
		cout << line << "," << word << endl;
	else
	{
		if (line > word)
			cout << line << endl;
		else cout << word << endl;

	}
	return 0;


}
//c++ primer p81 3.4


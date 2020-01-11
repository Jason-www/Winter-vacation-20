
#include<bits/stdc++.h>
using namespace std;
int main()
{
    char s;
    cin>>s;
    if(s>='a'&&s<='z')
    {
    	cout<<"lowercase";
	}
	if(s>='A'&&s<='Z')
	{
		cout<<"uppercase";
	}
	if(s>=char(0)&&s<=char(64))
	{
		cout<<"notletter";
	}if(s>=char(94)&&s<=char(96)){
		cout<<"notletter";
	}if(s>=char(123)&&s<=char(127)){
		cout<<"notletter";
	}
}

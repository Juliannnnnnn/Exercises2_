# Exercises2_
C++
/// Mark my words ///

#include <iostream>
using namespace std;

int main (){

int percentage;
cout <<"Enter the percentage:" <<endl;
cin>>percentage;

if(percentage >= 70)
{ cout <<"The letter grade is A" <<endl;
}
if ((percentage > 60) && (percentage < 69))
{ cout <<"The letter grade is B" << endl;
}
if ((percentage > 50) && (percentage < 59))
{ cout <<"The letter grade is C" << endl;
}
if ((percentage > 40) && (percentage < 49))
{ cout <<"The letter grade is D" << endl;
}
if (percentage < 40)
{ cout <<"The letter grade is F" << endl;
}
return 0;
}


/// Starting a Band ///

#include <iostream>
using namespace std;

int main() {
	bool musicalfriend = true;  bool nonmusicalfriend = false;
// This is the nested if-else statement that governs the decisions
if (musicalfriend) {
if (nonmusicalfriend) {
cout << "Do you want to be the guitarist of the band?" <<endl;
} else {
cout << "Do you want to be the guitarist of the band?" << endl;
}
} else {
cout << "okay, thank you :D" << endl;
}

int answer;
cout << "Write your answer: 99 - Yes or 00 - No 55 - I want to be the drummer of the band:" <<endl;
cin>>answer;

if(answer == 99)
{ 
    cout <<"Welcome to our band! You are now qualified <333" <<endl;
}
if(answer == 00)	
{
    cout <<"okay, thank you for your time!:D" <<endl;
}
if(answer == 55)
    cout <<"Sure! You are qualified as the drummer!!! Welcome, cool XD" <<endl;
return 0;
}


/// Killing Time ///

#include <iostream>
using namespace std;

int main (){

int minutes;
cout <<"How many minutes will you wait for your friend? She said __ minutes: Enter the minutes" <<endl;
cin>> minutes;

if(minutes >= 15 )
{ cout <<"Oh I will wait too long so I have decided to buy some things. :)" <<endl; 
cout <<"Cashier: Hi madam! your total bill is 170 dhs. (I pay my 200 dhs money)"  <<endl; 
cout <<"Uhmm I still have 30 dhs change"  <<endl; 
cout <<"Imma buy coffee and go for a walk"  <<endl; 
}
if (minutes < 15)
{ cout <<"Oh She will come sooner so I have decided to sit in the food zone and wait :)" << endl;
}

return 0;
}


/// Earthquake ///

#include <iostream>
using namespace std;
int main()
{
	int Magnitude;
	cout <<"Enter the Magnitude of the Earthquake:";
	cin >> Magnitude;
	
	if(Magnitude < 2.0) 
	{
		cout <<"Earthquake is considered to be a micro earthquake" <<endl;
	}
	else if(Magnitude <= 2.9)
	{
         cout <<"Earthquake is considered to be a very minor earthquake" <<endl;	 
	}
	else if(Magnitude <= 3.9)
	{
		cout <<"Earthquake is considered to be a minor earthquake" <<endl;
	}
	else if(Magnitude <= 4.9)
	{
		cout <<"Earthquake is considered to be a light earthquake" <<endl;
	}
	else if(Magnitude <= 5.9)
	{
		cout <<"Earthquake is considered to be a moderate earthquake" <<endl;
	}
	else if(Magnitude <= 6.9)
	{
		cout <<"Earthquake is considered to be a strong earthquake" <<endl;
	}
	else if(Magnitude <= 7.9)
	{
		cout <<"Earthquake is considered to be a major earthquake" <<endl;
	}
	else if(Magnitude <= 9.9)
	{
		cout <<"Earthquake is considered to be a great earthquake" <<endl;
	}
	else if(Magnitude == 10)
	{
		cout <<"Earthquake is considered to be a meteoric earthquake" <<endl;
	}
	else if(Magnitude > 10)
	{
		cout <<"There are no greater than ten" <<endl;
	}
	return 0;
}
         

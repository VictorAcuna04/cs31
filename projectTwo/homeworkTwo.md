# Homework Two 
Prepare your solutions to these homework problems as a single Word document named hw.docx or hw.doc, or a plain text file named hw.txt. Turn in this file as described in the Project 2 specification.

What is the output produced by the following program segment? Don't just run it — trace through it and figure it out by hand (which is a skill you'll need for the exams).

	string grendel = "endl";
	cout << "endl";
	cout << grendel;
	cout << endl;
	cout << "grendel";
Consider the following program:

	#include <iostream>
	using namespace std;

	int main()
	{
	    int side;

	    cout << "Enter a number: ";
	    cin >> side;

	    for (int i = 0; i < side; i++)
	    {
		for (int j = i; j >= 0; j--)
		{
		    cout << "#";
		}
		cout << "\n";
	    }
	}
In a brief, simple English sentence, state what this program does (e.g. "It prints a circle."). Again, figure this out by hand.

Copy the program in problem 2 and change it so that for any input number, the changed program produces exactly the same output as the original, but the changed program uses a while loop instead of a for loop for the inner loop.

Assume codeSection has been previously declared as an int and given as its value the number of a section of the California Penal Code. Write a switch statement that for any value of codeSection, produces exactly the same output as the following if statement.

	if (codeSection == 281)
		cout << "bigamy";
	else if (codeSection == 321  ||  codeSection == 322)
		cout << "selling illegal lottery tickets";
	else if (codeSection == 383)
		cout << "selling rancid butter";
	else if (codeSection == 598)
		cout << "injuring a bird in a public cemetery";
	else
		cout << "some other crime";

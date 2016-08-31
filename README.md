#include "stdafx.h"
#include <iostream>

using namespace std;

char ans;

int main()
{


	cout << "You wake up in a stable, unsure of what is happening." << endl;
	cout << " You have no clothes on and are buried in hay, which " << endl;
	cout << "      a horse is happily eating off of your face.    " << endl << endl;
	cout << "            Would you like to get up? (y/n)          " << endl;

	cin >> ans;

	if (ans == 'y')
	{
		cout << endl;
		cout << "You get up and brush the hay off of yourself." << endl;
		cout << "As you search for some clothing, you hear the" << endl;
		cout << "farmer who probably owns the barn approaching" << endl << endl;
		cout << "            Would you like to hide?          " << endl;

		cin >> ans;

		if (ans == 'y')
		{
			cout << endl;
			cout << "You spring out of the hay and run to the back of the barn" << endl;
			cout << "where you climb the ladder into the hay loft. The farmer " << endl;
			cout << "then enters the barn and talks to his animals for a while" << endl;
			cout << " He seems nice enough, but you see the rifle haning from " << endl;
			cout << "  over his shoulder. The floor groans and suddenly falls " << endl;
			cout << "out from underneath you, causing you to fall to the floor" << endl;
			cout << "below in a tangled, naked mess. The farmer whips his gun " << endl;
			cout << "    around and proceeds to shoot your broken body, not   " << endl;
			cout << "               bothering to ask questions.               " << endl;
			cout << "                     You are dead.                       " << endl << endl;
			cout << "               Would you like to try again?              " << endl;

			cin >> ans;

			if (ans == 'y')
			{
				main();
			}


			else
			{
				return 0;
			}
		}

		else if (ans == 'n')
		{
			cout << "You stand where you are, unsure if you should try to be" << endl;
			cout << "covering yourself. It's a rather unfortunate situation " << endl;
			cout << "  to be in. The farmer walks in with a rifle strapped  " << endl;
			cout << " over his shoulder. His eyes go wide when he sees you  " << endl;
			cout << "         and he slowly reaches back towards it.        " << endl << endl;
			cout << "              Do you want to surrender?                " << endl;

			cin >> ans;

			if (ans == 'y')
			{
				cout << endl;
			}

			else if (ans == 'n') 
			{
				cout << endl;
			}

			else
			{
				cout << "I'm sorry. Try again please sir. I'm not" << endl;
				cout << "    entirely sure I followed that.      " << endl << endl << endl;

				main();
			}
		}

		else
		{
			cout << "I'm sorry. try again please sir. I'm not" << endl;
			cout << "    entirely sure i followed that.      " << endl << endl << endl;

			main();
		}
	}
	else if (ans == 'n')
	{
		cout << "You stay within the hay, the horse eating it " << endl;
		cout << "off of your face, covering you in drool. You " << endl;
		cout << "jerk up as you hear the farmer approach the  " << endl;
		cout << "                     barn.                   " << endl << endl;
		cout << "     Do you want to get out of the hay?      " << endl;

		cin >> ans;

		if (ans == 'y')
		{
			cout << "You get out and frantically start looking for clothing." << endl;
			cout << "You stand where you are, unsure if you should try to be" << endl;
			cout << "covering yourself. It's a rather unfortunate situation " << endl;
			cout << "  to be in. The farmer walks in with a rifle strapped  " << endl;
			cout << " over his shoulder. His eyes go wide when he sees you  " << endl;
			cout << "         and he slowly reaches back towards it.        " << endl << endl;
			cout << "              Do you want to surrender?                " << endl;
		}

		else if (ans == 'n')
		{
			cout << " You stay in the hay, the horse munching happily at the " << endl;
			cout << "hay covering your chest. The farmer walks into the barn " << endl;
			cout << "and walks over to the horse. He pats the horse and looks" << endl;
			cout << " down and sees you there in the hay. He pulls the rifle " << endl;
			cout << "out from around his back and proceeds to point it at you" << endl;
			cout << "He yells at you in a language you dont understand before" << endl;
			cout << "shoving the muzzle into your face. He then shoots next  " << endl;
			cout << "to your head when you don't move. When you freak out, he" << endl;
			cout << "  gets startled and puts another round into your head.  " << endl;
			cout << "                      You are dead.                     " << endl << endl;
			cout << "               Would you like to try again?             " << endl;

			cin >> ans;

			if (ans == 'y')
			{
				main();
			}


			else
			{
				return 0;
			}
		}

		else
		{
			cout << "I'm sorry. Try again please sir. I'm not" << endl;
			cout << "    entirely sure I followed that.      " << endl << endl << endl;

			main();
		}


	}
	else
	{
		cout << "I'm sorry. try again please sir. I'm not" << endl;
		cout << "    entirely sure i followed that.      " << endl << endl << endl;

		main();
	}
    return 0;
}

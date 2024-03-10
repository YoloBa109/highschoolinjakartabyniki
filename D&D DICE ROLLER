//this is for u sean...

#include <iostream>
using namespace std;

int main (){
int dice;
char keepRolling;

srand (time(NULL));
cout << "welcome to dnd dice roller\n";
cout << "author: usagi\n" << endl;
cout << "choose which dice you would like to roll:\n";
cout << "1.d20\n2.d4\n3.d8\n4.d6\n5.d10\n6.d12\n";
cout << "input choice of dice:";

  cin >> dice;

switch (dice) {
    // D20
    case 1:
    int d20;
    d20 = rand() % 20 + 1;
    cout << "D20 ---> you rolled a " << d20 << ". \n";
    break;

    case 2:
    // D4
    int d4;
    d4 = rand() % 4 + 1;
    cout << "D4 ---> you rolled a " << d4 << ". \n";
    break;

    case 3:
    // D8
    int d8;
    d8 = rand() % 8 + 1;
    cout << "D8 ---> you rolled a " << d8 << ". \n";
    break;
  
    case 4:
    // D6
    int d6;
    d6 = rand() % 6 + 1;
    cout << "D6 ---> you rolled a " << d6 << ". \n";
    break;

    case 5:
    // D10
    int d10;
    d10 = rand() % 10 + 1;
    cout << "D10 ---> you rolled a " << d10 << ". \n";
    break;

    case 6:
    // D12
    int d12;
    d12 = rand() % 12 + 1;
    cout << "D12 ---> you rolled a " << d12 << ". \n";
    break;
}
  cout << "keep rolling? (y/n) ";
  cin >> keepRolling;
 if (keepRolling == 'y' || keepRolling == 'Y'){
   cout << "=========restarting==========\n";
   main();
   cout << "keep rolling (y/n) ";
   cin >> keepRolling;
 }
else {
   cout << "autobots, roll out" << endl;
}

return 0;
}

// NEVER APPLIED DOT AN ACTUAL CAMPAIGN, WILL ALLOW PUBLIC USAGE AND FORMAL CRITIQUE FOR IMPROVEMENT

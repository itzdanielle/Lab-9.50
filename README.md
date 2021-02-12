# Lab-9.50
#include <iostream>
#include <iomanip>
using namespace std;

int main() {
 cout << setprecision(2) << fixed;	
 double bill1;
 double bill2;
 double bill3;
 double bill4;
 double averageBill;
  cout << "Input your water bill for quater 1" << endl;
  cin >> bill1;
  cout << "Input your water bill for quater 2" << endl;
  cin >> bill2;
  cout << "Input your water bill for quater 3" << endl;
  cin >> bill3;
  cout << "Input your water bill for quater 4" << endl;
  cin >> bill4;

  averageBill = (bill1 + bill2 + bill3 + bill4)/4;
  cout << "Your average bill for the month is $ " << averageBill << endl;
  if (averageBill >= 75) {
    cout << "You are using excessive amounts of water" << endl;
  }
  else if ((averageBill >= 25) && (averageBill <= 75)) {
    cout << "You are using the typcial amount of water" << endl;
  }
  else if (averageBill <= 25) {
    cout << "Thank you for conserving water" << endl;
  }



}

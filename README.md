#include <iostream>

using namespace std;

int main()
{
    int numberoffriends;
    double amountofbill;
    int percentagetip;
    cout << "Please enter the number of people" << endl;
    cin >> numberoffriends;
    cout << "Please enter the bill" << endl;
    cin >> amountofbill;
    cout << "What is the percentage tip?"<< endl;
    cin >> percentagetip;
    double actualpercentage = percentagetip / 100;
    double total = (actualpercentage * amountofbill) / numberoffriends;
    cout << "Each person will pay" << total << "cedis" << endl;

    return 0;
}

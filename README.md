# s1_Jake-Laurence-De-Guzman-Paz

      #include <iostream>
        #include <string>
        using namespace std;

        int main()

        {
            char transport;
            string userInput;
            cout << "Please enter you're full name:" << endl;
            cin >> userInput;

            int num;
            cout << "Please enter you're age:" << endl;
            cin >> num;

            string location;
            cout << "Where do you live?" << endl;
            cin >> location;

            if ((location == "Abu Dhabi")) {
                cout << "This Transportaion has a delivery charge or 1000" << endl;

            }
            else if ((location == "Sharjah")) {
                cout << "This Transportaion has a delivery charge or 500" << endl;

            }
            else if ((location == "Ajman")) {
                cout << "This Transportaion has a delivery charge or 390" << endl;

            }
            else if ((location == "Dubai")) {
                cout << "This Transportaion has a delivery charge or 650" << endl;

            }
            else if ((location == "Ras-Al Khaimah")) {
                cout << "This Transportaion has a delivery charge or 250" << endl;

            }
            else if ((location == "Umm-Al Quin")) {
                cout << "This Transportaion has a delivery charge or 300" << endl;

            }
            else if ((location == "Fujairah")) {
                cout << "This Transportaion has a delivery charge or 300" << endl;

            }
            else if ((location == "Al Ain")) {
                cout << "This Transportaion has a delivery charge or 300" << endl;

            }
            else if ((location == "Ajman")) {
                cout << "This Transportaion has a delivery charge or 1000" << endl;

            }
            else
                cout << "There is no more other transport, If you live some where else" << endl;

            cout << "Would you like to cancel your transportation?" << endl;
            cout << "Please press 'Y' to continue." << endl;
            cout << "Please press 'N' to cancel." << endl;
            cin >> transport;

            switch (transport) {
            case 'y':
            case'Y':
                cout << "I would like to cancel this transport." << endl;
                break;

            case 'n':
            case 'N':
                cout << "I wanna continue and ride this transport." << endl;
                break;

            defult:
                cout << "invalid input" << endl;

            }

        }

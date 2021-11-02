Assessment 1

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        string name{};
        double age;
        int input{};
        char answer{};
            cout << "Type your name: ";
            cin >> name;
            getline(cin, name);
            cout << "Type your age: ";
            cin >> age;
            cout << "1. Abu dhabi, trasportation charges are AED 1000\n"
                "2. Sharjah, transportation charges are AED 500\n"
                "3. Ajman, transportation charges are AED 390\n"
                "4. Dubai, transportationo charcges are AED 650\n"
                "5. RAK, trasnportation charges are AED 250\n"
                "6. Umm Al-Quwain, transportation charges are AED 300\n"
                "7. Fujairah, trasnportion charges are AED 300\n"
                "8. Al Ain, transportation charges are AED 1000\n"
                "9. Other, no transportation\n";
                "Type your location example 1 for Abu Dhabi\n";
        cin >> input;
        switch (input)
            {
            case 1:
                cout << "Your location is Abu Dhabi that would be AED 1000" << endl;
                break;
            case 2:
                cout << "Your locations is Sharjah that would be AED 500" << endl;
                break;
            case 3:
                cout << "Your location is Ajman that would be AED 390" << endl;
                break;
            case 4:
                cout << "Your location is Dubai that would be AED 650" << endl;
                break;
            case 5:
                cout << "Your location is RAK that would be AED 250" << endl;
                break;
            case 6:
                cout << "Your location is Umm Al-Quwain that would be AED 300" << endl;
                break;
            case 7:
                cout << "Your location is Fujairah that would be AED 300" << endl;
                break;
            case 8:
                cout << "Your location is Al Ain that would be AED 1000" << endl;
                break;
            case 9:
                cout << "Please contact the school" << endl;
                break;
            default:
                cout << "Incorrect Command" << endl;
                break;
            }
        cout << "Are you gonna avail transpo? Type Y for yes and N for no\n";
        cin >> answer;
        if (answer == answer)
        {
            switch (answer)
            {
            case 'y':
            case 'Y':
                cout << "You are availing the transportation, Thank you." << endl;
                break;
            case 'n':
            case 'N':
                cout << "The transportation will be cancelled" << endl;
                break;
            default:
                cout << "Incorrect command" << endl;
            }
        }
        else
            {
            cout << "Incorrect Command, Please Try Again." << endl;
            }
        return 0;
     }





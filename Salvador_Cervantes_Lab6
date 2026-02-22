#include <iostream>
using namespace std;

int main() {
    int choice = 0;
    int firstNum = 0, secondNum = 0;
    bool hasInput = false;

    do {
        cout << "=== Week 6 Menu Program ===\n";
        cout << "1) Input two integers (firstNum < secondNum)\n";
        cout << "2) Display all odd numbers between them (while loop)\n";
        cout << "3) Display sum of even numbers between them (for loop)\n";
        cout << "4) Quit\n";
        cout << "Enter your choice: ";
        cin >> choice;

        if (choice == 1) {
            do {
                cout << "Enter first number: ";
                cin >> firstNum;
                cout << "Enter second number: ";
                cin >> secondNum;
                if (firstNum >= secondNum) {
                    cout << "First number must be less than second number. Try again.\n";
                }
            } while (firstNum >= secondNum);
            hasInput = true;
        }

        else if (choice == 2) {
            if (hasInput == false) {
                cout << "Please choose 1 first to input two integers.\n";}
            else {
                cout << "Odd numbers between them:\n";
                int i = firstNum + 1;
                while (i < secondNum) {
                    if (i % 2 != 0) {
                        cout << i << " ";
                    }
                    i++;
                }
                cout << endl;}
        }
        else if (choice == 3) {
            if (hasInput == false) {
                cout << "Please choose 1 first to input two integers.\n";
            }
            else {
                int sum = 0;
                for (int i = firstNum + 1; i < secondNum; i++) {
                    if (i % 2 == 0) {
                        sum = sum + i;
                    }
                }
                cout << "Sum of even numbers between them: " << sum << endl;
            }

        }
        else if (choice == 4) {
            cout << "Goodbye!\n";
        }
        else {
            cout << "Invalid choice!\n";
        }
        cout << endl;
    } while (choice != 4);
    return 0;
}

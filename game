#include <iostream>
#include <cstdlib>
#include <ctime>

using namespace std;

int main() {
    srand(time(0)); // Seed the random number generator

    int secretNumber = rand() % 100 + 1; // Generate a random number between 1 and 100
    int guess;
    int attempts = 0;

    cout << "Welcome to the Number Guessing Game!\n";

    do {
        cout << "Enter your guess (1-100): ";
        cin >> guess;

        attempts++;

        if (guess < secretNumber) {
            cout << "Too low!\n";
        } else if (guess > secretNumber) {
            cout << "Too high!\n";
        } else {
            cout << "Congratulations! You guessed the secret number in " << attempts << " attempts.\n";
        }
    } while (guess != secretNumber);

}

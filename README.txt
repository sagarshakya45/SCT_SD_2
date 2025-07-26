Number Guessing Game (C++)

This is a simple console-based number guessing game written in C++.  
The program randomly picks a number between 1 and 100, and the user has to guess it.  
Hints are provided if the guess is too high or too low.

Features:
- Random number generation using rand()
- Seeding with current time using srand(time(0))
- Hints to guide the user
- Simple loop with while until the correct guess

How to Run:

Requirements:
- A C++ compiler (like g++, MinGW, or an IDE such as Code::Blocks or VS Code)

Steps:
1. Download or clone the repository
2. Open your terminal or command prompt
3. Compile the program using this command:
   g++ guessing_game.cpp -o guess
4. Run the program:
   ./guess

How to Play:
- The program will ask you to guess a number between 1 and 100.
- Enter your guess and press Enter.
- The program will tell you if your guess is too high or too low.
- Keep guessing until you find the correct number.
- Have fun!

Example Output:
Welcome to the Number Guessing Game!
Guess a number between 1 and 100:
50
Too low! Try again:
75
Too high! Try again:
63
Congratulations! You guessed the number!

License:
This project is free to use under the MIT License.

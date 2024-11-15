Number Guessing Game 🎲
A simple C++ program where the user attempts to guess a randomly generated number between 1 and 100. The program provides feedback on each guess, guiding the user toward the correct number.

Features 🌟
Generates a random number between 1 and 100.
Provides hints if the user's guess is too high or too low.
Infinite attempts (or configure a maximum attempt limit).
Easy-to-use text-based interface.
Extendable for features like replay, input validation, and hints.
Requirements 🛠
C++ Compiler (e.g., GCC or Clang).
Works on any platform: Windows, macOS, or Linux.
Standard C++ libraries: <iostream>, <cstdlib>, <ctime>.
How to Use 🚀
Clone the repository:
bash
Copy code
git clone https://github.com/<your-username>/number-guessing-game.git
cd number-guessing-game
Compile the program:
bash
Copy code
g++ -o number_guessing_game number_guessing_game.cpp
Run the program:
bash
Copy code
./number_guessing_game
Follow the instructions in the terminal to guess the number.
How It Works ⚙️
The program generates a random number between 1 and 100 using the current time as a seed for randomness.
Users input guesses, and the program responds with:
"Too low!" if the guess is below the number.
"Too high!" if the guess is above the number.
"Congratulations!" when the guess matches.
The loop continues until the user guesses correctly.
Example Run 🖥️
plaintext
Copy code
I'm thinking of a number between 1 and 100. Can you guess it?
Enter your guess: 50
Too low! Try again.
Enter your guess: 75
Too high! Try again.
Enter your guess: 63
Congratulations! You guessed the correct number.
Possible Enhancements ✨
Input validation: Handle non-integer inputs gracefully.
Replay option: Allow users to play multiple rounds without restarting the program.
Hint system: Provide hints like ranges or proximity to the correct number.
Max attempts: Add a limit to the number of guesses.
Contributing 🤝
Fork the repository.
Create a new branch:
bash
Copy code
git checkout -b feature-name
Make changes and commit:
bash
Copy code
git commit -m "Added new feature"
Push your branch:
bash
Copy code
git push origin feature-name

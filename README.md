# Guess the Number (C Version)

A simple number guessing game written in C. The program randomly generates a secret number between 1 and 99. The user keeps guessing until the correct number is found. After each guess, the program gives feedback and counts the number of attempts.

---

Compile the program using a standard C compiler like gcc:

gcc guess_game.c -o guess_game  
./guess_game

---

Sample Output:

Enter your guess:  
50  
You should make it higher.  
Enter your new guess:  
75  
You should lower your guess.  
Enter your new guess:  
67  
You just found the secret number in your 3. try!

---

Features:
- Uses srand(time(NULL)) to initialize random number generation
- Random number is always between 1 and 99
- Uses while loop and conditionals to guide the player
- Tracks how many tries the user needed

---

System Requirements:
- A C compiler (GCC recommended)
- Terminal / Command Line access
- Compatible with Linux, macOS, or Windows

---

Created with ❤️ by İnci Mercan Abacıoğlu  
Project for C practice: loops, conditions, and randomness.

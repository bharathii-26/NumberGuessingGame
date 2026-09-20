# 🎯 Number Guessing Game

## 📌 Project Overview

The Number Guessing Game is a Java console-based game where the computer generates a random number and the player tries to guess it within a limited number of attempts.

The game provides different difficulty levels and gives hints such as "Too High" or "Too Low" after each guess.

## 🚀 Features

- Random number generation
- Three difficulty levels
- Easy: 1–50 with 10 attempts
- Medium: 1–100 with 7 attempts
- Hard: 1–200 with 5 attempts
- Too High / Too Low hints
- Attempt counter
- Input validation
- Play Again option
- Multiple rounds
- Score history
- Final score summary

## 🛠️ Technologies Used

- Java
- Java Collections
- Random class
- Scanner class
- Eclipse IDE

## 🎮 How to Run

1. Clone or download this repository.
2. Open the project in Eclipse IDE.
3. Open the `NumberGuessingGame.java` file.
4. Run the Java program.
5. Select a difficulty level.
6. Enter your guesses.
7. Continue until you guess the number or use all attempts.

## 📂 Project Structure

```text
NumberGuessingGame/
│
├── src/
│   └── numberguessing/
│       └── NumberGuessingGame.java
│
├── .classpath
├── .project
├── module-info.java
└── README.md

Sample Output

==============================
     NUMBER GUESSING GAME
==============================
1. Easy   (1-50, 10 attempts)
2. Medium (1-100, 7 attempts)
3. Hard   (1-200, 5 attempts)

Choose difficulty (1-3): 2

Round 1
Difficulty: Medium
Guess a number between 1 and 100
You have 7 attempts.

Enter your guess: 50
Too Low!

Enter your guess: 75
Too High!

Enter your guess: 63
Correct!

You guessed it in 3 attempts.

Learning Outcomes

Through this project, I practiced:

Java programming fundamentals
Loops and conditional statements
Random number generation
User input handling
Input validation
ArrayList
Exception-safe input handling
Basic problem-solving and game logic

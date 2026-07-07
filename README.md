# 🎯 Guess The Target Number

A simple Python console game where the computer randomly generates a target number between **1 and 100**, and the player tries to guess it correctly. After each incorrect guess, the game provides a helpful hint indicating whether the guessed number is too high or too low. The game continues until the player guesses the correct number or chooses to quit.

---

## 📖 Overview

**Guess The Target Number** is a beginner-friendly Python project designed to practice fundamental programming concepts. It demonstrates how to generate random numbers, accept user input, implement loops, and make decisions using conditional statements.

This project is ideal for Python beginners who want hands-on experience building an interactive console application.

---

## ✨ Features

- 🎲 Randomly generates a number between **1 and 100**
- 🎮 Interactive command-line gameplay
- 📉 Displays a hint when the guess is too low
- 📈 Displays a hint when the guess is too high
- ✅ Displays a success message when the correct number is guessed
- ❌ Allows the user to quit the game anytime by entering **Q**
- 🐍 Simple and beginner-friendly implementation

---

## 🛠️ Technologies Used

- Python 3
- Built-in `random` module

---

## 📂 Project Structure

```
guess-the-target-number/
│── guess_number.py
└── README.md
```

---

## ⚙️ How It Works

1. The program generates a random number between **1 and 100**.
2. The player enters a guess.
3. If the guess is:
   - Smaller than the target → A "Too Small" hint is displayed.
   - Greater than the target → A "Too Big" hint is displayed.
   - Equal to the target → The player wins.
4. The player can quit the game at any time by entering **Q**.

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/FauziaDev/guess-the-target-number.git
```

### Navigate to the Project Folder

```bash
cd guess-the-target-number
```

### Run the Program

```bash
python guess_number.py
```

---

## 💻 Sample Output

```text
Guess the target or Quit(Q): 30
your number was too small. Take a bigger guess..

Guess the target or Quit(Q): 75
your number was too big. Take a smaller guess..

Guess the target or Quit(Q): 63
Success : Correct Guess!!

-----GAME OVER-----
```

---

## 📚 Python Concepts Used

This project demonstrates the following Python concepts:

- Variables
- User Input (`input()`)
- Type Conversion (`int()`)
- Infinite Loops (`while`)
- Conditional Statements (`if`, `elif`, `else`)
- Random Number Generation (`random.randint()`)
- Program Flow Control
- Importing Modules

---

## 🎯 Learning Outcomes

After completing this project, you will understand how to:

- Generate random numbers in Python
- Build an interactive console application
- Accept and process user input
- Compare values using conditional statements
- Control program execution with loops
- Import and use Python modules

---

## 🔮 Future Improvements

Possible enhancements for future versions:

- Input validation for invalid values
- Attempt counter
- Difficulty levels (Easy, Medium, Hard)
- Score system
- Play Again option
- High score tracking
- Time limit mode
- Colored terminal output
- GUI version using Tkinter
- Web version using Flask

---

## 🤝 Contributing

Contributions are welcome.

If you'd like to improve this project:

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 📄 License

This project is created for educational and learning purposes.

---

## 👩‍💻 Author

**Fauzia Nishat**

GitHub: **https://github.com/FauziaDev**

---

### ⭐ If you found this project useful, don't forget to give it a Star!
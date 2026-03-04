# 🎯 Number Guessing Game (Python)

A simple and fun **Number Guessing Game** built using Python.

The program randomly generates a number between **1 and 100**, and the user has to guess it.
The game continues until the correct number is guessed.

This project demonstrates random number generation, loops, and conditional statements.

---

## 📌 Features

* 🎲 Generates a random number between 1 and 100
* 🔁 Allows unlimited guesses
* 📈 Tells the user if the guess is too high or too low
* ✅ Displays total number of attempts after correct guess
* 🎮 Simple and interactive gameplay

---

## 🛠️ Technologies Used

* Python 3
* `random` module
* While loop
* Conditional statements (`if-elif-else`)

---

## 📂 Project Structure

```id="p8n2yk"
Number_Guessing_Game.py
README.md
```

---

## ▶️ How to Run the Program

1. Make sure Python 3 is installed on your system.
2. Download or clone this repository:

   ```
   git clone https://github.com/your-username/your-repo-name.git
   ```
3. Navigate to the project folder:

   ```
   cd your-repo-name
   ```
4. Run the program:

   ```
   python Number_Guessing_Game.py
   ```

---

## 💻 How the Game Works

1. The program generates a random number using:

   ```python
   random.randint(1, 100)
   ```
2. The user enters a guess.
3. The program checks:

   * If guess is higher → prints **"Too high"**
   * If guess is lower → prints **"Too low"**
   * If guess is correct → prints success message
4. Displays total number of attempts.
5. Game ends when correct number is guessed.

---

## 📘 Example Output

```id="o3e7kd"
Enter your guess: 50
Too low
Enter your guess: 75
Too high
Enter your guess: 63
Correct guess
Number of attempts: 3
```

---

## 🎯 Learning Objectives

This project helps beginners understand:

* Random number generation
* Infinite loops (`while True`)
* Loop breaking using `break`
* Counting attempts using variables
* Basic game logic implementation

---

## 🚀 Future Improvements

* Add difficulty levels (Easy/Medium/Hard)
* Limit number of attempts
* Add replay option
* Add score system
* Convert into GUI version using Tkinter

---

## 👩‍💻 Author

**Swathi Shettigar**
BCA Student

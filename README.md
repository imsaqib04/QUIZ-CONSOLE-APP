### README.md

# Quiz Console App

This is a simple **command-line quiz application** built in Java.
It presents a set of multiple-choice questions, lets the user answer them, and then calculates and displays the final score.

---

## 📂 Files Overview

* **`Question.java`** – Defines the `Question` class, which acts as a blueprint for creating question objects.
  Each object stores:

  * Question ID
  * Question text
  * Four possible options
  * The correct answer

* **`QuestionService.java`** – Contains the core quiz logic.
  It:

  * Initializes an array of `Question` objects
  * Handles user input for answers
  * Calculates the score by comparing answers

* **`Test.java`** – Contains the `main` method, which serves as the **entry point** of the application.
  It:

  * Creates an instance of `QuestionService`
  * Calls `playQuiz()` and `printScore()` to run the quiz

---

## ▶ How to Run

1. **Compile the Java files**
   Navigate to the `src` directory and run:

   ```sh
   javac Question.java QuestionService.java Test.java
   ```

2. **Run the application**
   From the same directory:

   ```sh
   java Test
   ```

3. **Play the quiz**

   * The program will display a series of questions
   * Enter your answer (option number or letter) for each question
   * Your **final score** will be displayed at the end

---

## 🖥 Sample Output

```
Welcome to the Quiz!

Q1: What is the capital of France?
1. Berlin
2. Madrid
3. Paris
4. Rome
Enter your answer: 3

Q2: Who developed Java?
1. Microsoft
2. Sun Microsystems
3. Google
4. Oracle
Enter your answer: 2

Q3: Which planet is known as the Red Planet?
1. Venus
2. Mars
3. Jupiter
4. Saturn
Enter your answer: 2

Quiz Completed!
Your final score: 3/3
```

# Firstproject_Quiz
Python program that implements a simple quiz game based on some requirements. The game includes multiple-choice questions, a scoring system, user input handling, and feedback.

### Project Description: Simple Quiz Game in Python

#### Overview
This project involves creating a simple quiz game in Python that asks users a series of multiple-choice questions, evaluates their answers, and provides feedback. It is designed to reinforce Python fundamentals including data structures, control flow, and user input handling. The quiz game features a scoring system to track the user's performance and offers immediate feedback on each question.

#### Features
- **Questions and Options**: The quiz includes three questions, each with four multiple-choice options.
- **Scoring System**: The game tracks the number of correct answers and calculates the final score.
- **User Input Handling**: The game validates user input to ensure it corresponds to one of the provided options.
- **Feedback**: Users receive feedback on whether their answer was correct or incorrect, along with the correct answer if they were wrong.
- **Final Score**: At the end of the quiz, the user’s final score is displayed.
- **Customization**: The quiz can be easily customized by modifying the list of questions, options, and correct answers.

#### Requirements
- Basic understanding of Python programming.
- Python environment setup on your computer.

#### Code Structure
1. **Function: `ask_question`**
   - **Parameters**: 
     - `question` (str): The question to ask.
     - `options` (list): A list of answer options.
     - `correct_answer` (str): The correct answer to the question.
   - **Functionality**:
     - Prints the question and its options.
     - Validates and handles user input.
     - Provides feedback on the user's answer.
     - Returns 1 if the answer is correct, otherwise 0.

2. **Function: `run_quiz`**
   - **Functionality**:
     - Contains a list of dictionaries, each representing a question with its options and correct answer.
     - Initializes the score to 0.
     - Iterates through the questions, calls the `ask_question` function, and updates the score.
     - Displays the final score at the end.

#### How to Customize
To customize the quiz, modify the `questions` list in the `run_quiz` function. Each question is represented as a dictionary with three keys:
- `"question"`: The question text.
- `"options"`: A list of multiple-choice options.
- `"correct_answer"`: The correct answer from the options list.

#### Sample Questions
1. **What is the largest planet in our solar system?**
   - Options: Earth, Jupiter, Saturn, Mars
   - Correct Answer: Jupiter

2. **Who painted the Mona Lisa?**
   - Options: Vincent van Gogh, Pablo Picasso, Leonardo da Vinci, Claude Monet
   - Correct Answer: Leonardo da Vinci

3. **What is the smallest prime number?**
   - Options: 1, 2, 3, 5
   - Correct Answer: 2


This project provides an engaging way to practice Python programming and can be expanded with additional features such as more questions, different types of questions (e.g., true/false), and a graphical user interface (GUI) using libraries like Tkinter.

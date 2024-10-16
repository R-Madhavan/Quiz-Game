# Quiz Game

A simple True/False quiz game built with Python, using Object-Oriented Programming (OOP) principles.

## Features
- Play a multiple-question quiz with True/False answers.
- The quiz automatically tracks your score.
- Questions are fetched from a predefined list of science/computer-related topics.
- Provides instant feedback after each question, and displays the final score at the end of the quiz.

## Files

- **`data.py`**: Contains the list of quiz questions and answers.
- **`question_model.py`**: Defines the `Question` class to structure each quiz question.
- **`quiz_brain.py`**: Contains the `QuizBrain` class which manages the quiz flow, handles user input, and checks the answers.
- **`main.py`**: The main script that runs the quiz, creating a question bank and initiating the quiz process.

## Getting Started

### Prerequisites
- Python 3.x installed on your system.

### Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/quiz-game.git
    ```

2. Navigate to the project directory:
    ```bash
    cd quiz-game
    ```

3. Run the quiz:
    ```bash
    python3 main.py
    ```

## How to Play

1. The quiz will ask you a series of True/False questions.
2. Type your answer as `True` or `False` and press Enter.
3. After each question, you'll see whether you answered correctly and your current score.
4. The quiz ends when you've answered all the questions, and your final score will be displayed.

## Example
```bash
Q.1: Ada Lovelace is often considered the first computer programmer. (True/False): True
You got it right!
The correct answer was: True.
Your current score is: 1/1

Q.2: Linux was first created as an alternative to Windows XP. (True/False): False
You got it right!
The correct answer was: False.
Your current score is: 2/2

...

You've completed the quiz
Your final score was: 10/12
```

## Future Improvements

- Add more categories and difficulty levels.
- Create a graphical user interface (GUI).
- Add randomization of questions.
- Integrate an external API for fetching random quiz questions.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

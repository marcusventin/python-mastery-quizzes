# Python Mastery Quizzes

## Motivation
This repo is inspired by the Makers' Ruby Mastery Quizzes, which served as an introduction to the Ruby programming language. I have converted the questions, and the associated tests, to Python.

## How to Use 
#### Set-Up
1. Fork this repo and clone it to your local machine.
2. Make sure that you have Python installed.
    * If you don't, download it from [Python.org](https://www.python.org/).
3. In your terminal, navigate to the project's root directory and set up a virtual environment with:
    <br>`python3 -m venv venv`
4. Create the virtual environment with:
    <br>`. venv/bin/activate`
5. Install the project's dependencies with:
    <br>`pip install -r requirements.txt`
6. Solve some puzzles!

Stuck on a question? View sample solutions [here](https://github.com/marcusventin/python-mastery-quizzes-solutions).

#### Testing
* To check your solutions against the automated tests, navigate to the project's root directory, then enter into your terminal:  
  `python -m pytest CHAPTERFOLDER/tests`  
  e.g., to run tests on Chapter 1, you would enter:  
  `python -m pytest chapter1/tests`  

* If you want to run tests on a specific question, you can enter:  
    `python -m pytest CHAPTERFOLDER/tests/TEST_QUESTION_NUMBER.py`  
  e.g., to run tests on Question 2 of Chapter 4, you would enter:  
    `python -m pytest chapter4/tests/test_question_2.py`  


## Feedback
Problems with setting things up? Questions not clear? Your solution failing the tests? Having fun? Have any questions or ideas for improvements? Let me know!

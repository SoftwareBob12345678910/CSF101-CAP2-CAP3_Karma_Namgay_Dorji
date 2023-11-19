# CSF101-CAP2-CAP3_Karma_Namgay_Dorji

Test Initialization (test_initialization):

Ensures that Pygame is initialized successfully.
Initializes a QuizGame and checks that the initial score is 0, and the current question is set appropriately.
Test Button Interaction (test_button_interaction):

Tests the Button class by creating a button, simulating a click, and verifying that the button's state reflects the click.
Resets the button state and checks that a button click doesn't occur without a simulated mouse click.
Test Game Logic - Correct Answer (test_game_logic_question_answer):

Initializes a QuizGame, runs the game loop, and simulates selecting a correct answer.
Verifies that the score is incremented by 1 and the current question is updated appropriately.
Test Game Logic - Timeout (test_game_logic_timeout):

Initializes a QuizGame, runs the game loop, and simulates a timeout.
Verifies that the current question moves to the next one and the score remains unchanged.
The code uses the unittest module for writing and running unit tests. Additionally, it utilizes the MagicMock class from unittest.mock for creating mock objects, and it assumes the existence of a QuizGame and Button class in a module called Game. You should replace these placeholders with your actual implementation details.

Resources used in this code:

unittest module: The built-in Python testing framework.
unittest.mock: A module providing a flexible framework for creating mock objects.
pygame: A cross-platform set of Python modules designed for writing video games. It is used for creating the game and handling events like button clicks.

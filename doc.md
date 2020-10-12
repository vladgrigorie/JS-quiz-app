<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

-   [AccountsController][1]
-   [QuizController][2]
-   [UIController][3]
-   [mainController][4]

## AccountsController

This is the Accounts Controller. It is an IIFE function.
It has the following functions :

-   provides a data structure to save the accounts and keep track of the logged in users
-   offers the posibility to download this datastructure as a JSON file (didactic purpose)
-   handles the user registration, login and logout

## QuizController

This is the Quiz Controller. It is an IIFE function.
It has the following functions :

-   Loads the quiz questions for the type of quiz received.
-   Handles the quiz initialization and termination.
-   Checks if the answers received for each question are correct (one at a time).
-   Keeps track of the user's score in the current quiz.
-   Provides a data structure to save all the scores of all users;

## UIController

This is the User Interface Controller. It is an IIFE function.
It has two functions :

-   Handles/modifies the DOM 
-   Collects and returns the data introduced by the user.

## mainController

This is the main controller of the application. It is an IIFE function.
We use the other three controllers (received as parameters) to achive the desired app behaviour.
Returns an object containing the init() function.

[1]: #accountscontroller

[2]: #quizcontroller

[3]: #uicontroller

[4]: #maincontroller
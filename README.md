# Problem Statement:
This quiz app was created using HTML, CSS, and JavaScript so that the user could interact with the quiz. The quiz contains questions that test the user’s understanding of the basics of web development. The app allows the user to answer 5 questions and lets them know the answer after they answer the question or after 15 seconds. The goal of the app is to either teach the user about the basics of web development or to refresh them on abbreviations in web development.
## Functional Features:
- Start/End Quiz Button - The user can begin the quiz by clicking the “Start Quiz” button or exit the quiz by clicking on the “Exit Quiz” button
- Quiz Instructions - The set of rules for the quiz, providing information about the time limit, questions/answers, and quiz duration
- Quiz Question DIsplay - Dynamic container for all questions from the “question.js” file
- Multiple-choice options - a set of possible answers that allows the user to choose the option they think is correct
- Timer - a countdown for each question, showing the user how long they have before the app moves to the next question
- Visual Timer - the line showing the visual progress of the countdown timer
- Selection & Feedback - provides feedback to the user about the answer they selected
- Score - the visual representation of the user’s correct answers
- Next Question Button - allows the user to move to the next question by pressing the “Next Question” button
- Results Display - after the quiz, displays the users final score
- Replay & Quit Buttons - Allows the user to either replay the quiz or close the app by pressing the corresponding button
## Directory Structure:
### Index.html: Primary HTML file for the application
- Contains the base HTML logic including references to the necessary CSS and JavaScript files
- Contains the basic layout for the application with containers for JavaScript generated content
### Style.css
- Contains CSS styling for the entire applications
- Uses HTML classes to define styling
- Controls the appearance of all elements
### Questions.js
- Contains an array of custom question objects
### quizApp.js
- Contains primary JavaScript logic for generating quiz questions
- Uses DOM to interact with HTML elements
- Defines listeners for all button elements
- Handles the flow of the quiz by dynamically updating the visual score and timer elements
- Uses the pre-defined objects in the “questions.js” file to create the questions
## Code Explanation:
- index.html - Defines the structure of the application, including all static elements and containers for dynamic ones
- style.css - Defines the styles used for all different elements, used to modify visual appearance
- questions.js - Contains an array of questions to be used in other JavaScript files
- quizApp.js - Creates questions from the questions.js and manages quiz logic using event listeners and functions

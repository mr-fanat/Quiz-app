# Quiz-app

A JavaScript quiz web application (also used HTML and CSS) that will function as follows:
-It has a radio button choices and it show how much questions we have at all, and position of current question;
-The quiz can show any number of questions and any number of choices;
-It show users score after answering last question and suggers to user try again.

-We used an array to store all the questions. 
Each question, along with its choices and correct answer, stored in an object.
The array of questions look similar to this 
(Notice that only one question is in this example array; you can add many questions):
var allQuestions = [{question: "Who is Prime Minister of the United Kingdom?", 
                    choices: ["David Cameron", "Gordon Brown", "Winston Churchill", "Tony Blair"], 
                    correctAnswer:0}];

Main tasks which i need to implement:
 - Use jQuery to add animation. (fade out/fade in the next question) (maybe refactor app core code using jQuery);
 - Store the quiz questions in an external JSON file;
 - Test app on IE.
 - Add user authentification. Allow users to log in, and save their login credentials to local storage (HTML5 browser storage);
 - Use cookies to remember the User? and show a "Welcome, "First Name" message when the User returns to the quiz.


Tasks and features wich already was implemented:
 - client side validation (to make sure that user answers each question before proceeding to the next question);
 - add a "Back" button to allow user to go back and change answer. The user can go back up to the first question. For the questions that the user has answered already, the radio button will be selected. So, the user is not forced to answed the questions again, which he has completed.

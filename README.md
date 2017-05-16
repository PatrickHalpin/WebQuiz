# WebQuiz
A web quiz application made using Javascript, Html and css

This is an online coding challenge posted by udemy, the quiz features numerous questions about the premier league.
This application is a multiple choice quiz with only one right asnwer for each question.
At the end of the test the users score is returned to them.

This application was made 100% by myself Patrick Halpin.

# How to play
A working version can be found at http://patrickhalpin.github.io/indexQuiz
The quiz is based off of trivia from the english premier league.
Select one answer from each question.
Once the answer is selected the next question will appear.
After all the questions you will recieve a score.


# Documentation 
The solotion to this challange was made using javascript and is a client side application as I found this to be the best and easiest way to create the quiz.
The questions and answers to the questons are both stored in 2 seperate array lists, these answers populate the 4 answer buttons each time a new question is asked.
The buttons contaning the answers call a "getResult" function which checks the selected answer against the correct answer, if the users chosen answer is correct their score is updated.
This then calls the next question function which accesses the next entry in the questions in the array and changes the question on screen.
It also accesses the next 4 answers in the answers array and populates the answer buttons with these 4 statements. Allowing the user to answer the next question.
When the total number of qiestions have been answered the user is then shown their socre which was saved in a score variable whcih only incremented when they got an answer correct.
